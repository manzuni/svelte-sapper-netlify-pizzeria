<script>
  export let controlType = null;
  export let id;
  export let label;
  export let rows = null;
  export let value;
  export let type = "text";
  export let valid = true;
  export let validityMessage = "";
  export let name = "";
  export let placeholder = "";

  let touched = false;
</script>

<style>
  input,
  textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    margin-top: 6px;
    margin-bottom: 16px;
    resize: vertical;
    transition: border-color 0.1s ease-out;
  }

  input:focus,
  textarea:focus {
    border-bottom-color: #e40763;
    outline: none;
  }

  label {
    display: block;
    margin-bottom: 0.5rem;
    width: 100%;
  }

  .form-control {
    padding: 0.5rem 0;
    width: 100%;
    margin: 0.25rem 0;
  }

  .invalid {
    border-bottom-color: red;
    background: #fde3e3;
  }

  .error-message {
    color: red;
    margin: 0.25rem 0;
  }
</style>

<div class="form-control">
  <label for={id}>{label}</label>
  {#if controlType === 'textarea'}
    <textarea class:invalid="{!valid && touched}" {placeholder} {name} {rows} {id} bind:value on:blur={() => touched = true} />
  {:else}
    <input class:invalid="{!valid && touched}" {placeholder} {name} {type} {id} {value} on:input on:blur={() => touched = true} />
  {/if}
  {#if validityMessage && !valid && touched}
    <p class="error-message">{validityMessage}</p>
  {/if}
</div>

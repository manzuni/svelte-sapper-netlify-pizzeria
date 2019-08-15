<style>
  /*! CSS Used from: file:///D:/pizza/css/animate.css */
  .ftco-animated {
    -webkit-animation-duration: 0.5s;
    animation-duration: 0.5s;
    -webkit-animation-fill-mode: both;
    animation-fill-mode: both;
  }
  .fadeInUp {
    -webkit-animation-name: fadeInUp;
    animation-name: fadeInUp;
  }
  /*! CSS Used from: file:///D:/pizza/css/flaticon.css */
  [class^="flaticon-"]:before,
  [class^="flaticon-"]:after {
    font-family: Flaticon;
    font-style: normal;
    font-weight: normal;
    font-variant: normal;
    text-transform: none;
    line-height: 1;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }
  .flaticon-pizza:before {
    content: "\f101";
  }
  /*! CSS Used from: file:///D:/pizza/css/style.css */
  *,
  *::before,
  *::after {
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
  }
  section {
    display: block;
  }
  h2 {
    margin-top: 0;
    margin-bottom: 0.5rem;
  }
  p {
    margin-top: 0;
    margin-bottom: 1rem;
  }
  h2 {
    margin-bottom: 0.5rem;
    font-family: inherit;
    font-weight: 500;
    line-height: 1.2;
    color: inherit;
  }
  h2 {
    font-size: 2rem;
  }
  @media (min-width: 768px) {
    .d-md-flex {
      display: -webkit-box !important;
      display: -ms-flexbox !important;
      display: flex !important;
    }
  }
  .mb-4 {
    margin-bottom: 1.5rem !important;
  }
  @media print {
    *,
    *::before,
    *::after {
      text-shadow: none !important;
      -webkit-box-shadow: none !important;
      box-shadow: none !important;
    }
    p,
    h2 {
      orphans: 3;
      widows: 3;
    }
    h2 {
      page-break-after: avoid;
    }
  }
  span {
    color: #bfbfbf;
  }
  h2 {
    line-height: 1.4;
    color: #fff;
    font-weight: 400;
    font-family: "Josefin Sans", Arial, sans-serif;
  }
  .ftco-about .one-half {
    width: 100%;
    padding: 30px 15px;
  }
  @media (min-width: 768px) {
    .ftco-about .one-half {
      padding: 5%;
      width: 50%;
    }
  }
  .ftco-about .one-half.img {
    display: block;
  }
  @media (max-width: 767.98px) {
    .ftco-about .one-half.img {
      height: 300px;
    }
  }
  .ftco-animate {
    opacity: 0;
    visibility: hidden;
  }
  .heading-section h2 {
    font-size: 30px;
    font-weight: 400;
    position: relative;
    text-transform: uppercase;
  }
  @media (max-width: 767.98px) {
    .heading-section h2 {
      font-size: 28px;
    }
  }
  .heading-section h2 span {
    color: #fac564;
  }
  .img {
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
  }
  /*! CSS Used keyframes */
  @-webkit-keyframes fadeInUp {
    from {
      opacity: 0;
      visibility: hidden;
      -webkit-transform: translate3d(0, 40px, 0);
      transform: translate3d(0, 40px, 0);
    }
    to {
      opacity: 1;
      visibility: visible;
      -webkit-transform: none;
      transform: none;
    }
  }
  @keyframes fadeInUp {
    from {
      opacity: 0;
      visibility: hidden;
      -webkit-transform: translate3d(0, 40px, 0);
      transform: translate3d(0, 40px, 0);
    }
    to {
      visibility: visible;
      opacity: 1;
      -webkit-transform: none;
      transform: none;
    }
  }
  /*! CSS Used fontfaces */
  @font-face {
    font-family: "Flaticon";
    src: url("file:///D:/pizza/fonts/flaticon/font/Flaticon.eot");
    src: url("file:///D:/pizza/fonts/flaticon/font/Flaticon.eot#iefix")
        format("embedded-opentype"),
      url("file:///D:/pizza/fonts/flaticon/font/Flaticon.woff") format("woff"),
      url("file:///D:/pizza/fonts/flaticon/font/Flaticon.ttf") format("truetype"),
      url("file:///D:/pizza/fonts/flaticon/font/Flaticon.svg#Flaticon")
        format("svg");
    font-weight: normal;
    font-style: normal;
  }
  @font-face {
    font-family: "Flaticon";
    src: url("file:///D:/pizza/fonts/flaticon/font/Flaticon.svg#Flaticon")
      format("svg");
  }
  @font-face {
    font-family: "Josefin Sans";
    font-style: normal;
    font-weight: 400;
    src: local("Josefin Sans Regular"), local("JosefinSans-Regular"),
      url(https://fonts.gstatic.com/s/josefinsans/v14/Qw3aZQNVED7rKGKxtqIqX5EUAnx4RHw.woff2)
        format("woff2");
    unicode-range: U+0102-0103, U+0110-0111, U+1EA0-1EF9, U+20AB;
  }
  @font-face {
    font-family: "Josefin Sans";
    font-style: normal;
    font-weight: 400;
    src: local("Josefin Sans Regular"), local("JosefinSans-Regular"),
      url(https://fonts.gstatic.com/s/josefinsans/v14/Qw3aZQNVED7rKGKxtqIqX5EUA3x4RHw.woff2)
        format("woff2");
    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB,
      U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
  }
  @font-face {
    font-family: "Josefin Sans";
    font-style: normal;
    font-weight: 400;
    src: local("Josefin Sans Regular"), local("JosefinSans-Regular"),
      url(https://fonts.gstatic.com/s/josefinsans/v14/Qw3aZQNVED7rKGKxtqIqX5EUDXx4.woff2)
        format("woff2");
    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA,
      U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215,
      U+FEFF, U+FFFD;
  }
</style>


<section class="ftco-about d-md-flex">
    	<div class="one-half img" style="background-image: url(about.jpg);"></div>
    	<div class="one-half ftco-animate fadeInUp ftco-animated">
        <div class="heading-section ftco-animate fadeInUp ftco-animated">
          <h2 class="mb-4">Welcome to <span class="flaticon-pizza">Pizza</span> A Restaurant</h2>
        </div>
        <div>
  				<p style="color: gray">On her way she met a copy. The copy warned the Little Blind Text, that where it came from it would have been rewritten a thousand times and everything that was left from its origin would be the word "and" and the Little Blind Text should turn around and return to its own, safe country. But nothing the copy said could convince her and so it didn’t take long until a few insidious Copy Writers ambushed her, made her drunk with Longe and Parole and dragged her into their agency, where they abused her for their.</p>
  			</div>
    	</div>
</section>
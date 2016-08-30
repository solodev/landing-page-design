# landing-page-design
Landing Pages are essential to delivering unique experiences and content to your audience. In this article, [Solodev](https://www.solodev.com/) will provide a mobile responsive landing page design and instructions on how to assemble the design using HTML5.

## Tutorial

For detailed instructions, view Solodev's [Designing a Responsive Landing Page](https://www.solodev.com/blog/web-design/designing-a-responsive-landing-page.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/dzg0t8w7/).

## HTML

The landing page design has the following basic HTML markup.
```
<main class="terms-wrapper">
  <div class="container">
    <div class="landing-section">
      <div class="container">
        <div class="row">
          <div class="col-md-7 landing-section-firstContent">
            <h2 class="ct-sectionHeader--type2">
              Are you Part of the App Majority? <small>It could be time to rethink your Mobile App Strategy</small>
            </h2>
            <div id="article-main-content2">
              <div class="row">
                <div class="col-lg-6 col-lg-push-6 text-center-tablet text-center">
                  <img alt="Mobile App Graphic" src="images/mobile-app-graphic.png">
                </div>
                <div class="col-lg-6 col-lg-pull-6">
                  <p class="ct-u-paddingBottom20">
                    According to digital tracking agency comScore, a key milestone called the <b>App Majority</b> was recently reached so where the majority of digital media time spent now occurs on mobile apps. With nearly 200 million Americans expected to own smartphones by 2016, it’s clear that having a mobile strategy is no longer an option.
                  </p>
                  <p class="ct-u-paddingBottom20">
                    Think about it - targeting new customers and engaging existing ones on smart phones has become more important than ever. With <b>apps now driving 7 out of every 8 minutes of mobile media consumption</b>, having a mobile strategy is imperative to reaching your key audiences.
                  </p>
                  <p class="ct-u-paddingBottom30">
                    Download WebCorpCo's targeted whitepaper and take <b>5 minutes</b> to learn the latest in Mobile strategy and technology.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <aside class="col-md-5 mobile-app-column">
            <div class="mobile-app" id="formContainer2">
              <h3 class="form-title">
                <center>DOWNLOAD OUR WHITEPAPER</center>
              </h3>
              <form name="contentForm" enctype="multipart/form-data" method="post" action="">
                <div class="formAside">
                  <div class="form-group">
                    <label for="firstName">First Name<span class="asteriks">&nbsp;*</span></label><input type="text" name="firstName" size="" id="firstName" class="form-control validate[required]" value="">
                  </div>
                  <div class="form-group">
                    <label for="lastName">Last Name<span class="asteriks">&nbsp;*</span></label> <input type="text" name="lastName" size="" id="lastName" class="form-control validate[required]" value="">
                  </div>
                  <div class="form-group">
                    <label for="emailAddress">Email<span class="asteriks">&nbsp;*</span></label> <input type="text" name="emailAddress" size="" id="emailAddress" class="form-control validate[required]" value="">
                  </div>
                  <div class="form-group">
                    <label for="title">Title<span class="asteriks">&nbsp;*</span></label> <input type="text" name="title" size="" id="title" class="form-control validate[required]" value="">
                  </div>
                  <div class="form-group">
                    <label for="companyName">Company<span class="asteriks">&nbsp;*</span></label> <input type="text" name="companyName" size="" id="companyName" class="form-control validate[required]" value="">
                  </div>
                  <div class="form-group">
                    <label for="phoneNumber">Phone</label> <input type="text" name="formfields[phoneNumber]" size="" id="phoneNumber" class="form-control" value="">
                  </div>
                  <div class="text-center ct-u-paddingTop30">
                    <button type="submit" class="btn btn-large btn-motive">Download Now</button>
                  </div>
                </div>
              </form>
            </div>
          </aside>
        </div>
      </div>
    </div>
  </div>
</main>

```
## CSS

All necessary CSS is in landing-page.css

## External Includes

This tutorial includes the following third-party resources:
```
<link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="landing-page.css">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```


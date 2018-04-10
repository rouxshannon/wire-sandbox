---
layout: post
title:  "Introducing the Creative Team"
date:   2018-04-07 21:15:05 +0000
image: /assets/images/art-creative-flying-17679.jpg
author: Doug
---
Ready for your next challenge? Add your profile to this post! Use the same process of forking the site, marking your changes, testing out your changes on your own version of the site, and then making a pull request.

We haven't added much in the way of directions here, so be sure to work together and get help!

There are some new things going on in the code of this post, including a mix of both `markdown` and <code>html</code>. We're also starting to leverage some of our [css framework](materializecss.com/), which is called `materialize`. We'll learn about all of these things as we continue working together - so it is ok if some of this code doesn't quite make sense yet. We'll keep exploring as we go!

You can copy and edit the following html code example:


<!-- this is a comment, we use comments to write notes that only appear in code -->
<!-- we also use comment to mark off sections of code to make things easier to read and scan -->
<!-- for example, in the code below, there is a start statement and an end statement to help us scan and read through the code. -->

<!-- Start Doug's profile -->
 <div class="col s12 offset-m2 l6 offset-l3">
        <div class="card-panel grey lighten-5 z-depth-1">
          <div class="row valign-wrapper">
            <div class="col s3">
              <img src="{{site.baseurl}}/assets/images/doug.jpg" alt="Doug's profile picture" class="circle responsive-img"> <!-- notice the "circle" class -->
            </div>
            <div class="col s9">
              <span class="black-text">
                Doug is passionately interested in how learners work together to build knowledge.
              </span>
            </div>
          </div>
        </div>
      </div>
<!-- End Doug's profile -->

<!-- Start Shannon's profile -->
 <div class="col s12 offset-m2 l6 offset-l3">
        <div class="card-panel grey lighten-5 z-depth-1">
          <div class="row valign-wrapper">
            <div class="col s3">
              <img src="{{site.baseurl}}/assets/images/Shannon.jpg" alt="Shannon's profile picture" class="circle responsive-img"> <!-- notice the "circle" class -->
            </div>
            <div class="col s9">
              <span class="black-text">
                Shannon has worked as part of the creative team since the winter of 2017,  heading projects such as the Research Paper Planner and Integrating Citations modules. She will be working full time at WI+RE for the Spring 2018 Quarter before moving to Chicago to serve as a Elementary Special Education Teacher! Shannon is excited about creating materials that can facilitate meaningful learning across the diverse range of learners we serve!
              </span>
            </div>
          </div>
        </div>
      </div>
<!-- End Shannon's profile -->

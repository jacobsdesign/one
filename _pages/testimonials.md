---
layout: page
title: HORIZON
permalink: /testimonials/
desctiption: "HORIZON"
---

<div id="team" class="testimonials">
  <div class="testimonial-container">
    <div class="row">
      <div class="col-md-12">
      <h1>"2017"</h1>
      </div>
    </div>
    <div class="row">
      {% for item in site.data.testimonials %}
      <div class="col-4">
        <div class="row" style="center">
          <div>
          <a href="{{item.link}}">
            <img width="250" height="250" class="team-image rounded-circle" src="{{item.image | relative_url}}"
              alt="{{item.name}}">
            <h4 class="name font-weight-bold mb-2" style="center">{{item.name}}</h4>
            <p class="position"><small>{{item.designation}}</small></p>
            </a>
          </div>
        </div>
      </div>
      {% endfor %}
    </div>
  </div>
</div>

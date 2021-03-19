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
      <h1>test</h1>
      </div>
    </div>
    <div class="row">
      {% for item in site.data.testimonials %}
      <div class="col-12 review border rounded mb-4">
        <div class="row">
          <div class="col-12 col-md-4 text-center">
          <a href="{{item.link}}">
            <img width="250" height="250" class="team-image rounded-circle" src="{{item.image | relative_url}}"
              alt="{{item.name}}">
            <h4 class="name font-weight-bold mb-2">{{item.name}}</h4>
            <p class="position"><small>{{item.designation}}</small></p>
            </a>
          </div>
          <div class="col-12 col-md-8 font-italic my-auto lead">
            {{item.comment}}
          </div>
        </div>
      </div>
      {% endfor %}
        <h3 class="name font-weight-bold mb-2">{{item.name}}</h3>
          <div class="row">
      <div class="col-md-12">
      </div>
    </div>
    </div>
  </div>
</div>

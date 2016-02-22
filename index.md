---
layout: page
title: "Tap N Book"
homepage: true
description: "Book Meeting Room. Instantly!"
---

{% for post in paginator.posts %}
<div class="post-preview">
    <a href="{{ post.url | prepend: site.baseurl }}">
        <h2 class="post-title">            {{ post.title }}
        </h2>
        {% if post.subtitle %}
        <h3 class="post-subtitle">
            {{ post.subtitle }}
        </h3>
        {% endif %}
    </a>
    <p class="post-meta">Posted by {% if post.author %}{{ post.author }}{% else %}{{ site.title }}{% endif %} on {{ post.date | date: "%B %-d, %Y" }}</p>
</div>
<hr>
{% endfor %}

<!-- Pager -->
{% if paginator.total_pages > 1 %}
<ul class="pager">
    {% if paginator.previous_page %}
    <li class="previous">
        <a href="{{ paginator.previous_page_path | prepend: site.baseurl | replace: '//', '/' }}">&larr; Newer Posts</a>
    </li>
    {% endif %}
    {% if paginator.next_page %}
    <li class="next">
        <a href="{{ paginator.next_page_path | prepend: site.baseurl | replace: '//', '/' }}">Older Posts &rarr;</a>
    </li>
    {% endif %}
</ul>
{% endif %}

<div class="heading-section col-md-12 text-center">
    <h2>Our Project Features</h2>
    <p>This Project has been started upon our self interest to know new topics in the field of IOT.</p>
</div>

<div class="row">
    <div class="col-md-4 col-sm-6">
      <div class="service-item" id="service-1">
          <div class="service-icon">
              <i class="fa fa-hand-pointer-o"></i>
          </div> <!-- /.service-icon -->
          <div class="service-content">
              <div class="inner-service">
                 <h3>Microsoft Outlook</h3>
                 <p class="service-content-p">An intuitive way to book your Outlook Meeting Rooms using Smartphone</p>
              </div>
          </div> <!-- /.service-content -->
      </div> <!-- /#service-1 -->
    </div> <!-- /.col-md-3 -->
    <div class="col-md-4 col-sm-6">
      <div class="service-item" id="service-2">
          <div class="service-icon">
              <i class="fa fa-hand-peace-o"></i>
          </div> <!-- /.service-icon -->
          <div class="service-content">
              <div class="inner-service">
                 <h3>NFC Tag</h3>
                 <p class="service-content-p">Using NFC smartphone, Microsoft Outlook meetings are booked instantly with just push of button</p>
              </div>
          </div> <!-- /.service-content -->
      </div> <!-- /#service-2 -->
    </div> <!-- /.col-md-3 -->
    <div class="col-md-4 col-sm-6">
      <div class="service-item" id="service-3">
          <div class="service-icon">
              <i class="fa fa-bullseye"></i>
          </div> <!-- /.service-icon -->
          <div class="service-content">
              <div class="inner-service">
                 <h3>Google Calendar</h3>
                 <p class="service-content-p">Enhance your overall meeting experience by activating your personal Google Calendar account</p>
              </div>
          </div> <!-- /.service-content -->
      </div> <!-- /#service-3 -->
    </div> <!-- /.col-md-3 -->
</div>
<div class="row">
    <div class="col-md-4 col-sm-6">
      <div class="service-item" id="service-3">
          <div class="service-icon">
              <i class="fa fa-hand-spock-o"></i>
          </div> <!-- /.service-icon -->
          <div class="service-content">
              <div class="inner-service">
                 <h3>Neopixel LED</h3>
                 <p class="service-content-p">Neopixel stick can show live Meeting room availability status using RGB LED's with appropriate colors</p>
              </div>
          </div> <!-- /.service-content -->
      </div> <!-- /#service-3 -->
    </div> <!-- /.col-md-3 -->
    <div class="col-md-4 col-sm-6">
      <div class="service-item" id="service-4">
          <div class="service-icon">
              <i class="fa fa-hand-paper-o"></i>
          </div> <!-- /.service-icon -->
          <div class="service-content">
              <div class="inner-service">
                 <h3>IoT</h3>
                 <p class="service-content-p">A smartphone, Raspberry Pi, Arduino, Internet & Neopixel Connected</p>
              </div>
          </div> <!-- /.service-content -->
      </div> <!-- /#service-4 -->
    </div> <!-- /.col-md-3 -->
    <div class="col-md-4 col-sm-6">
      <div class="service-item" id="service-2">
          <div class="service-icon">
              <i class="fa fa-thumbs-up"></i>
          </div> <!-- /.service-icon -->
          <div class="service-content">
              <div class="inner-service">
                 <h3>Contribute</h3>
                 <p class="service-content-p">To make it globally available!!!</p>
              </div>
          </div> <!-- /.service-content -->
      </div> <!-- /#service-2 -->
    </div> <!-- /.col-md-3 -->
</div>


It is best known as the efficient booking service by <em>A Tap & Go Style</em>, You don't need a computer but a NFC enabled smart phone. [Read more about us...]({{site.baseurl}}/about/)

---
layout: default
name: Kaitlyn Miller
title: Wedding Day Assistant
image: /uploads/a1-02269.jpg
email: events@southerncoutureweddings.com
weight: 5
bio: '"Coming Soon..."'
---
<section class="py-5">
    <div class="container">
        <div class="row justify-content-center">
            <!-- content -->
            {% if page.image %}
            <div class="col-md-4">
              <img src="{{page.image}}" class="img-fluid" alt="{{page.name}} - {{page.title}} | Southern Couture Weddings "/>
            </div>
            {% endif %}
            <div class="col-lg-8">
                <h2>{{page.name}}</h2>
                <div class="pb-5">
                  {{page.bio}}
                </div>
            </div>
        </div>
    </div>
</section>

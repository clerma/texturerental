---
layout: default
name: Kaylynn Eberhardt
title: Wedding Day Director and Social Events Planner
image: /uploads/a1-02302.jpg
email: events@southerncoutureweddings.com
weight: 2
bio: >-
  "I have been a fan of weddings for as long as I can remember. The constant
  change, the small details, the sweet families are the best part of my job. I
  get to spend time with couples on their most special day. I recently became a
  mom and loving every minute of loving on my sweet baby!

  Favorite Things: My puppy, Sunglasses, Event Days, Traveling, Mint Chocolate
  Chip Ice Cream and Heels

  Favorite Design Element: Candles, Greenery and unique details that represent
  the couple and their love story

  Favorite Wedding Tradition: Handwritten vows, the first look and the couples
  exchange of handwritten letters before the wedding

  Kaylynn graduated from the University of Louisiana at Lafayette with a degree
  in Hospitality Management. She has experience working with Lafayette
  Convention and Visitor Commission, Event Rental Lafayette and Sales Manager
  for Hilton Garden Inn."
---
<section class="py-5">
    <div class="container">
        <div class="row">
            <!-- content -->
            {% if page.image %}
            <div class="col-md-4">
              <img src="{{page.image}}" class="img-fluid" alt="{{page.name}} - {{page.title}} | Texture Event Rental Weddings "/>
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

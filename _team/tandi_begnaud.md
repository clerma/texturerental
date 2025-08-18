---
layout: default
name: Tandi Begnaud
title: Wedding Day Director
image: /uploads/a1-02247.jpg
email: events@southerncoutureweddings.com
weight: 3
bio: >-
  "Event planning is perfect for my direct, yet fun-loving personality. With
  over fifteen years of experience planning private and corporate events, I am
  passionate about creating a beautiful and unique experience with you in mind.
  With a background in creative arts, I believe every event should be unique and
  specific to your personality. No matter the size, I approach each event with
  precise attention to detail, action-oriented coordination and creativity. I
  believe these qualities are the magic behind a successful event.

  I’m married to my best friend, Rudy, and we have three children, who love life
  and believe every day is a party! In our house we are real, we create, we make
  mistakes, we have fun, we say I'm sorry, we are really loud, we love deeply,
  and we make memories!

  I am grateful that I get to create and execute incredible experiences that
  will become special memories.

  Favorite things: my family, the beach, my church, sports, sweet iced tea, a
  good book, flower beds, and red velvet cake.

  Favorite Design Element: I love beautiful flowers and the perfect color
  combination, but my favorite design element is the one that makes yours unique
  and specific to your special day.

  Favorite Wedding Tradition: Giving of the Bride; the honor of giving the Bride
  to her Groom is meaningful and always a special moment in the ceremony."
---
<section class="py-5">
    <div class="container">
        <div class="row">
            <!-- content -->
            {% if page.image %}
            <div class="col-lg-4">
              <img src="{{page.image}}" class="img-fluid bio-pic" alt="{{page.name}} - {{page.title}} | Southern Couture Weddings "/>
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

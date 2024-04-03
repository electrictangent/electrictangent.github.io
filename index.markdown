---
layout: home
title: index
contacttitle: Contact us
contactdescription: Want a quote? Contact us via the form below and we will email you as soon as possible.
submitaction: /hello.php

hero:
  description: >-
    # Creative Woodwork Crafted for Your Special Space
    
    
    Good to see you here.  At WoodConcepts, we carefully craft bespoke woodwork creations from reclaimed New Zealand native timer and other timber from elsewhere.  With innovative craftsmanship, we create beautiful woodwork tailored to suit your unique style and space.


    Our customers include businesses for e.g. Boho Café in Palmerston North, Cute Little Bagels in Whanganui and Hopper House in Wellington. 

  imageurl: /assets/img/hero.jpg
  button: Contact us
  buttonurl: /#contact-form

galleryitems:
  - title: Indoor Living
    description: Wooden furniture tailored for your indoor living space; armoire, coffee tables, barn doors, shelves, headboards. workbench, chopping boards, cheese boards, pizza boards and more&hellip;
    imageurl: /assets/img/indoorliving.jpg
    imagealt: Indoor Living
  - title: Kitchen Benchtops
    description: Convert your kitchen with our beautifully crafted New Zealand native timber kitchen bench top or stand-alone island.
    imageurl: /assets/img/kitchenbenchtop.jpg
    imagealt: Kitchen Benchtops
  - title: Outdoor living
    description: Upgrade your outdoor living space with our bespoke woodwork creations; outdoor tables, benches and seatings.
    imageurl: /assets/img/outdoorliving.jpg
    imagealt: Outdoor living
  - title: Signs and slabs
    description: Let your signs attract attention with our reclaimed timber signboards custom-made with rustic appeal. Slabs are also available for your projects.
    imageurl: /assets/img/signslab.jpg
    imagealt: Signs and slabs


customerfeedback: >-
  # Business and Home Customer Feedback

  “Excellent trade thanks.  Easy communication. Table is excellent and looks great.”


  “Happy with the item, thanks.”


  “Great trade – we are really happy with the drawers.”


  “Just amazing, so beautiful, matches our Matai floors, thanks so much :-)”


  “I would recommend Murray to all traders.  His work is well made and carefully finished.”


  “As per description. Extremely well built. Recommended trader.”


  “…First class this morning was a massive success and yeah the shelf looks so good.  Can’t wait to get the other one and might have more commissions in the future.” Harry (Business Owner)


  “Hi Murray just letting you know I have paid the final instalment of $xxx Thank you so much for your time, effort and expertise.  It’s been a good ride!”


  “Thank you so much for the bench, I just love it.  Hopefully the word will spread and more work will come from it.”


  “Yes the barstools are working a treat. We love them and use them a lot.”


  “firstly, we LOVE your seats. How wonderful they look. everyone loves them, and I feel supported by your prices being so reasonable - and caring. every time i sit on them I will feel loved and supported (not just holding me up..)” Susie (Owner of HOPPER HOUSE, Wellington)


---
{% include uielements/hero.html header="true" imageurl=page.hero.imageurl description=page.hero.description button=page.hero.button buttonurl=page.hero.buttonurl %}

{% include uielements/gallery.html %}

{% include uielements/home-textbox.html text=page.customerfeedback %}


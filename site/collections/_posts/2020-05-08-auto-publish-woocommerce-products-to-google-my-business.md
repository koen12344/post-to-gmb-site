---
title: Auto-publish WooCommerce products to Google My Business
categories:
  - tutorials
author_staff_member: /staff_members/koen-reus
date: 2020-05-08 00:00:00
content_blocks:
SEO_options:
  title:
  description:
  image: /uploads/post-image-1.png
  prevent_indexing: false
---
Google has removed the ability to create Product posts through the Google My Business API. This means you can no longer create “real” Product posts using the Post to Google My Business plugin.

Personally I think Google will be removing the product post type altogether in the near future, in favor of the new **Product Collections** feature. But it’s also **not yet possible** to populate that section using the API (I will definitely add that feature to the plugin once that becomes possible\!).

## The solution

If you want to bring your latest products and services to the attention of &nbsp;your (potential) customers, you can simply publish them as **What’s new** or **Offer** posts\!

After all, the people that search for your business on Google won’t really be aware of the difference between the various Google My Business post types.

All they see is a picture of your shiny new product, with a “Shop now” button beneath it. **It will be just as effective\!**

## How to set up the plugin

(Auto-)publishing your latest WooCommerce products to Google My Business is easy\!

1. Make sure the [Post to Google My Business plugin](https://tycoonmedia.net) is installed and activated on your WordPress website. The ability to create Product posts is available in the [Pro version and up](https://tycoonmedia.net/#pricing).
2. Enable the **Products** post type in the plugin settings and save the changes.<br>![](/uploads/59v30lur3p.png){: width="741" height="394"}
3. The Post to Google My Business panel & Auto Publish checkbox will now be available when you create or update a WooCommerce product

## But how do I get the product details into my GMB post text?

Visually, the only thing that sets a Product post apart from a regular GMB post is the “Price” field. You can still display the price of the product by including it in your post description.

The plugin can automatically fetch the product price and other details from your WooCommerce product and place them in your GMB post text. You can use the following variables in your post text & auto-post templates:

* %wc\_product\_price%
* %wc\_product\_name%
* %wc\_product\_description%
* %wc\_product\_short\_description%
* %wc\_product\_sku% %wc\_product\_virtual%
* %wc\_product\_regular\_price%
* %wc\_product\_sale\_price%

These variables will be automatically replaced by their corresponding value in your final GMB post:

![](/uploads/plugin-to-gmb.png){: width="900" height="428"}

[Here’s](https://tycoonmedia.net/blog/using-the-quick-publish-feature/) a list of all variables you can use in your post

## Auto-publish your products to GMB

The plugin can be configured to automatically publish your Products to Google My Business when you create (or update) them within WordPress.

1. In your WordPress Dashboard, navigate to Post to GMB &gt; Settings &gt; Auto-post settings
2. Adjust the template so it fits your needs. For example:

   > New product\! %wc\_product\_name% %wc\_product\_short\_description% Price: $%wc\_product\_price%
3. When creating a new Product, tick the “Auto-post to GMB” checkbox before publishing it.<br>![](/uploads/9jgmxd0knp.png){: width="294" height="227"}
4. Hit Publish and your product will be automatically posted to GMB\!

You can also tweak the auto-post template right before publishing, if you need to make product-specific changes. This will only change the auto-post template for that specific product, the global template will be unaffected.<br>![](/uploads/zzmjhwy7ky.png){: width="352" height="157"}

Additionally, you can enable **Post to GMB by default** in the auto-post settings, so the Auto-post checkbox is checked by default. Note that it will only be checked by default if the product hasn’t been auto-posted to GMB before (to prevent accidentally posting multiple times).

## Wrapping up

You should now be all set to create beautiful GMB posts from your WooCommerce products, and even be able to automate the whole process\! Do you use the auto-post feature in a clever way? I’d love to hear from you in the comments\!

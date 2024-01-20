---
layout: post
title: Welcome to Your Awesome Blog!
---

Hey there! 👋 You've officially kicked off your blog – congrats! 🚀 Now, let's add a special treat for your readers.

### Exclusive Offer 🎁

Ready to grab a discount? Click the button below:

<button onclick="revealCoupon()">Get 10% Off</button>

<!-- Hidden Coupon -->
<div id="coupon" style="display: none;">
    Your Coupon Code: `BLOG10`
</div>

### Customize Your Site

Feel free to update your site name, avatar, and other cool options. It's a breeze! Just dive into the _config.yml file at the heart of your repository. Need a visual guide? Check out the snippet below:

![Configuration File]({{ site.baseurl }}/images/config.png)

### Making Your Mark

Ready to dive into your first post? Fantastic! Head over to the /_posts/ directory and give the Hello World markdown file a makeover. Don't worry; it's as easy as editing this very post.

For more detailed instructions and tips, swing by the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub. There's a treasure trove of insights waiting for you!

Happy blogging! 🎉

<!-- JavaScript to reveal coupon and open affiliate link -->
<script>
    function revealCoupon() {
        // Reveal the hidden coupon div
        document.getElementById("coupon").style.display = "block";

        // Open affiliate link in a new tab
        window.open("https://your-affiliate-link.com", "_blank");
    }
</script>

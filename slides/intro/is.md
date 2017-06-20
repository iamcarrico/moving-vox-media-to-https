## What is this?

* Why HTTPS is important, and equally hard  <!-- .element: class="fragment" -->
* Identifying insecure content  <!-- .element: class="fragment" -->
* Certificates  <!-- .element: class="fragment" -->
* 3rd parties suck  <!-- .element: class="fragment" -->
<li class="fragment"><code>Content-Security-Policy</code></li>
<li class="fragment"><code>strict-transport-security</code></li>
* All the things you can now do because of HTTPS  <!-- .element: class="fragment" -->


Note:

First off, for a better description of what SSL/TLS is, what some common HTTPS problems are— go watch this video— it is a fantastic overview of the problem. https://www.youtube.com/watch?v=2pu3Gh38Ng4


HTTPS is important. It is important for user's privacy and security— it is important for SEO— and it is important for web performance. Even so, it can be difficult to move to HTTPS for many sites for a variety of factors. Third party content, advertising, legacy systems, the cost of certificates all come into play when making the move.

Which is why it took over a year from start to finish for Vox Media to go from no HTTPS, to defaulting to HTTPS.

This talk goes into the nitty gritty of what it took for this move to be made. Starting with identifying all of the services that needed to be updated— and how different limitations required altering how they are used. We will dive into Let's Encrypt— and how we used them to get certificates for our staging environments. What the benefits of `Content-Security-Policy` headers are, and how they can be used to debug HTTPS on a site. Why are `strict-transport-security` headers necessary for real security. Finally— we are going to talk about all the new web technologies that HTTPS opens up.

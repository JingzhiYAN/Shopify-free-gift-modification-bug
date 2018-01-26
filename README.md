# Shopify-free-gift-modification-bug
<p>Recently I found a bug on shopify store.</p>
<h2>Customers always get more free gift than sellers want on shopify store.</h2>
<h3>Reason:</h3>
<p>The cart of shopify basicly stored on customer's browser, which means it could be modified. Normally, it doesn't really matter a lot. Because if you add more products to your cart, you pay more. But what if there is a free gift? What if this store is pretty big and they are using a ERP system to do the delivery? Customers will get free gift because of that. </p>
<p>In the past I thought this won't be possible, who could be so boring to do something like this? Cheat for free gift? Well, recently I met plenty of them... I guess most of them are just doing this for fun. A challenge to the seller, and see what they are going to do.</p>
<h3>This one is showing what really happened inside, is also testing if the app author is telling something right.</h3>
<p>OK, test has been done successfully</p>

These two files are What I've got from the website, the cart part. Modified one was tested, and I've got an order with 60 free gift boxes and 60 free cards. Which nearly give an heart attack to my senior...

<p>So free gift with 0 price in shopify cannot work automatically unless shopify could give more code access to sellers' developpers.</p>
<p>I've reported similar problem to shopify officers directly about three months ago. They promised to solve this "as soon as possible". The problem I reported is the cart disappear problem. Customers' cart is not stored on accounts. They are deleted every 7 days. This is not that good...I might delete this repository after they change this to the right one...</p>
<p> </p>
<p>Now I have to work on the automatic add free gift problem alone...SAD..</p>

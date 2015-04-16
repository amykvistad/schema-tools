# schema-tools
Resources for adding schema to your website

http://www.microdatagenerator.com/local-business-generators/
Generates local business schema. Add your business type, fill out address and other basic information and then click generate. Add the schema code to your html file.

https://developers.google.com/structured-data/testing-tool/
Test your schema code -- see how Google sees it.

https://www.google.com/webmasters/markup-helper/u/0/
Google's structured data markup helper - select your data type and add the URL to tag your html.

Example:
<div itemscope itemtype="http://schema.org/HousePainter">
   <span itemprop="name">Best Painting Company</span>
   <div itemprop="address" itemscope itemtype="http://schema.org/PostalAddress">
     <span itemprop="streetAddress">10 Street Address</span>
     <span itemprop="addressLocality">town</span>,
     <span itemprop="addressRegion">state</span>
     <span itemprop="postalCode">zipcode</span>
   </div>
   Phone: <span itemprop="telephone">000-000-0000</span>
   <a href="map url" itemprop="maps">URL of Map</a>
</div> 

Also, don't forget these:
<span itemprop="url" for your company website
<span itemprop="logo" for your company logo

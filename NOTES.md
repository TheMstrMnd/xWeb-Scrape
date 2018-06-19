#### WEB SCRAPING USING NODEJS

* 1. Let's look at cheerio. 
* 2. https://medium.com/@adinugroho/webscraping-with-nodejs-and-cheerio-c3971611736a
        - npm install cheerio
        - npm install axios
* 3. Upgrading node package is the solution here. Adding altenative steps to upgrade node package as there is no need to download, install and manage node versions yourself. You can use a module called n to upgrade you node package in Mac/Ubuntu

* sudo npm install -g n
* sudo n stable

* As Jaye Speaks points out:

* MOST websites modify the DOM using JavaScript. Unfortunately Cheerio doesn’t resolve parsing a modified DOM. Dynamically generated content from procedures leveraging AJAX, client-side logic, and other async procedures are not available to Cheerio.
Remember this is an introduction to basic scraping. In order to get started you’ll need to find a static website with minimal DOM manipulation.
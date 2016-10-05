Todo
====

# HOT ISSUE
- [x] `parse-inqiery-form` is sending back to `/test` and needs to send back to previous page. 
- [x] add bio TC for 2.8 931804 to products and upload image
- [x] where the hell did the off canvas menu go! -shheez that was too easy :)
- [x] **not really ht but...** need to add the new UYF flask with cap and cap to products and images

## The big random list
- [ ] Add tox book and two appnotes to the tech.json file
- [ ] text for each roadmap tile
- [ ] redo the transfer cap form in angular will need json file and what not
- [ ] set `$_GET` in ~~Full Width template for product pages~~ test template to set biology or chemistry and have angular know it
- [x] add phone number to inquiry module forms
- [x] need another layout shorcode for smaller centered block for quotes or smaller image.
- [x] need module for related products (use prefooter? to much to the bottom of page?) this needs to be expanded on to further engage the user
- [x] update readme with new shortcodes and add pdf with cheet sheet to file
- [x] create block for more info like FAQ's videos...
- [x] info bar or module with tech library info and such for product pages
- [x] create shortcodes for the common layouts for pages i.e. text only, image with text, two images or data graphs...
- [x] if no info for tech result item then do not display item. (pseudo element with content in `css` hm....)
- [x] send to tech library and have it set to a product
- [x] move posts to pages as we can not use angular :( and also you have to have a category
- [x] tech results `app.js` on links to pages should just redirect to the page with `window.location`
- [x] figure out what to do with `$_GET` need to get into `angular`? or something.  Once page knows the query how does it show differing text apnotes ect.
- [x] product page `hero` with `<select>` responsive height is ganky
- [x] add PN's to FV pages
- [x] double check all links in robot lisa
- [x] new favicon
- [x] fix well plates search
- [x] add click to see more info on parts referance
- [x] redo `JSON` for well plates selection page
- [x] create test template for setting up complex pages faster
- [x] found old favicons replace
- [x] change all product pages to have shorter urls ie no more `optimum-growth/optimum-growth-transfer-cap/inversion-transfer-cap/`  insdead have `og/tc/inversion` so much cleaner
- [x] then update the `products.json` file
- [x] ~~move all custom `js` into `assests/javascript/custom` and remove any `enque_script` madness~~ <= this was maddness and did not work! JSON moved to it's own folder though:)
- [x] new images for the roadmap tiles
- [x] Photos of a few products for roadmap images
- [x] update `shortcodes` with `home_url()` and `content_url()` with paths
- [x] tweak roadmap tiles and set up equal columns as well
- [x] redesign roadmap tiles

##Overlay
- [x] overlay testing
- [x] ~~overlay should be able to be set on any page~~ created overlay directive for easy drop in to pages
- [x] overlay should be able to ~~be set with class and data attribute~~ grab variables from angular
- [x] overlay should be able to work with angular
- [x] overlay should be able to be sent a template from click page through data attribute
- [x] add click to close button so we can have forms or selectable text, that and people may not know to click anywhere

##Product pages
- [x] another `JSON` file with appnotes  ~~and text? I think text should be hard coded but what about the whole bio chem deal ug!~~
- [ ] appnotes on the page after cell line selection or working field entered
- [x] get a quote and get me samples? how to auto place into forms...overlay?
- [x] ~~pass `variables` to overlay form~~ use `sessionStorage` for product inquiry forms
- [x] need to have system for dropdown or something for appnotes, or get from query? duh no yet!

##Pages to start adding text
- [ ] FV main page would be first few pages from appnote booklets
- [x] UYF page.
- [x] need hero div possibly with markup inside but has to have full width height background.  This needs to be css background so `shortcode` for page content and `css` `class` to set as full size background.  Then can set image with maybe a shortcode with attribute `[background src='image.jpg']` would inject into a `<div>` like this `<div class='full-background' [background src='bgImage.jpg']>` and have it render `<div class='full-background' style='background-image:url(../../bgImage.jpg;'>`

##gist cheatsheet to make
- [x] **functions to get to:**
- [x] uploads folder
- [x] theme directory
- [x] base url
- [x] shortcode template
- [x] enque script code
- [x] function for removing added `<p>` and crap
- [x] custom field  usage
- ...... oh i'm sure there's more
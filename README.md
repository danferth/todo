Todo
====

# OTHER PEOPLES PROBLEMS
- [ ] text for sales to look over

## The big random list
- [ ] create link to general information fliers on product pge for download and in tech library change links to general info to the product page
- [ ] remove any empty links (mostly addwords landing pages) from tech library
- [ ] clamp charts need to be on product page for flasks not in tech library
- [ ] link to accessories on product page in text somewehere
- [ ] documentation needs to be redone. *ie. json keys, shortcoeds...*
- [ ] module by module style review (parts list and tech notes hover and click on mobile, form boxes, twitter...all of them) *look at desktop => tablet => mobile*
- [ ] page by page look at style *look at desktop => tablet => mobile*
- [ ] shortcode page layout style review from desktop down to mobile
- [ ] forms need second look at validation *also* **what gives on the other forms need answers**
- [ ] nail down forms text, responce, output and email receiving issues
- [ ] double check all product images and downloads. *(download the folders from c9 output on screen file names from json and match up in file explorer with details view)*
- [ ] God i know there's more....
- [ ] the related products needs an overhaul. it's a bit big when only two are present. Also the styling when on smaller screens is horrible
- [ ] Product parts linsings have a checkbox for common items like 'sterile, accessories available...'
- [ ] glassware organization needed
- [ ] glassware needs search
- [ ] each product needs the basic questions answered up front. *i.e. fill volumnes, comes in multiple sizes... and not in the form of bullets maybe a module of some sort so people konw to look in a sertain place. 
- [ ] use [plax](https://github.com/danferth/plax) to add another layer to roadmap tiles
- [ ] change over to gulp - will have to work off of gulp starter
- [x] redo overlay to have overlay module a sibling to mask not child. This way `js` can handle a click to close the whole bannana. *maybe have both in parent div*
- [x] New font needs to be looked into
- [x] off canvas menu text needs to be white
- [x] product listings need a hover click reveal of more info just basic specs and an image
- [x] well plate overlay needs to be redone
- [x] Add plate covers to plate search *(get interaction between the two)*
- [x] need way to clear well shape select
- [x] double check the well plate well shapes the 24 well square well round bottoms are not triggering
- [x] on well search try to have only 10mL for volume select
- [x] Oppertunities *(sp)* on main nav and footer link
- [x] First seal has a weird `,` prepended to description
- [x] start looking at cell culture and FV about page layouts
- [x] start design of search for tech library
- [x] redo distributors page
- [x] on main roadmap pages copy top `<p>` in a `<div>` wrapper
- [x] `parse-inqiery-form` is sending back to `/test` and needs to send back to previous page. 
- [x] add bio TC for 2.8 931804 to products and upload image
- [x] where the hell did the off canvas menu go! -shheez that was too easy :)
- [x] **not really ht but...** need to add the new UYF flask with cap and cap to products and images
- [x] MOve well plate search to well plates page no reason to have them separate
- [x] set up or check variables for changing nav bar styles easily
- [x] **fix the FLOUC on the rail nav**
- [x] introduce the twitter module or 'prefooter' instead of just being a chunk of the page
- [x] need to have a new and noteworthy news section for say new appnotes or trade shows we will attend. maybe like a twitter feed?
- [x] on large screens a module that floated mid screen on the left that housed linked in twitter and tech library link
- [x] update distributors list
- [x] order by date in the tech note results [codepen](https://codepen.io/danferth/pen/8eb2fb19f2dd022b9330337076dab685?#)
- [x] rework shortcodes to all have an added class attribute and have a push pull sttribute for text_image shortcode
- [x] `<input type="hidden" value="getStorage('science')" />` in all the quiry forms
- [x] template for pages that do not require angular ie the carrers page (so they load faster)
- [x] industry in the techlibrary.json needs to be an `[]` not a `string`
- [x] in tech library two selects for product (line and series) default will be all and once line is selected the series limits to just available.
- [x] ability to select product before entering the tech library
- [x] links or module to get to other main sections of tech library from each one. *i.e. in videos and link to appnotes keeping the product selected*
- [x] need to have a careers page like just a link in footer and simple page only one or two positions open at a time
- [x] text for each roadmap tile
- [x] redo the transfer cap form in angular will need json file and what not
- [x] set `$_GET` in ~~Full Width template for product pages~~ test template to set biology or chemistry and have angular know it
- [x] Add tox book and two appnotes to the tech.json file as well as poster to published works
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
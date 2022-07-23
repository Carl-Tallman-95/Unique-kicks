# My Website

**Bold Text**

paragraph text

https://codeinstitute.net

[Code Institute](https://codeinstitute.net)

## h2

### h3

- dot

- another dot


paragraph

# UNIQUE-KICKS

This is the website for ”Unique-kicks”. It is a website that offers customizesing services for footwear.
With simple steps and a simple design you will have a easy time navigating through our pages and hopefully get inspired aswell.
Unique-kicks will be useful for anyone who wants their shoes to have a makeover and look as good as new.
The site is designed to be compatible with sevral different screen sizes and is easy to navigate for anyone.

![This is an image](assets/images/readme_images/amiresponsive_site_result.png)

## Features
- Navigation
    - On all three pages there is a responsive navigation bar that includes links to the Home page, Gallery and Contact page.
    - The navigation bar is identical in each page to allow for easy navigation.
    - At any page you can click on the Logo that is linked to get to the Home page.
    - The navigation is easy to understand and tells the user where each section goes.

![This is an image](assets/images/readme_images/nav.png)


- The Header Image And Text Box
    - The heading has a image as a background with a text floating on it’s left side to contrast the navigation bar.
    - The image is darkened down to help the text stand out.
    -  Under the text there is a clickable button linked to the contact page.
    - The section is clear about what the service is and who it is for.

![This is an image](assets/images/readme_images/text_box.png)

- How Does it Work Section
    - The section helps the user to understand the steps to take for a customized pair of shoes to be ordered.
    - The steps gives a clear guide to the user in order to understand the ease of use for the site.
    - The steps are easily readable with a plesant design.

![This is an image](assets/images/readme_images/how_does_it_work.png)

- Check Out Our Gallery Section
    - This section will allow the user to get a get a glimpse into what the product is or could be.
    - The "HERE"button is linked to the full gallery page which is also accessible by the navigation bar.
    - The images featured are relevant and clearly show the user what kind of product they can expect from the service.

![This is an image](assets/images/readme_images/check_out_our_gallery.png)

- About Us Section
    - The About us section shows knowligable information about the service.
    - The section states in more detail what the site is and who is behind it.
    - The section gives motivation to what the service aims to achieve.
    - The section details that it makes a personalized product to make the potential customer feel special.

![This is an image](assets/images/readme_images/about_us.png)

- The Footer
    - The footer includes links to the relevant social media sites for facebook, twitter, youtube and instagram. When clicked, the links will open in a new tab for easy navigation for the user.
    - The footer encourages users of the site to stay connected with the site via social media.

![This is an image](assets/images/readme_images/footer.png)

- The Gallery Page
    - The gallery will provide the user with a larger collection of images to see what the customized footwear could potentially look like.
    - The gallery page icludes relevant pictures of customized and style footwear that the user can be assured the site can provide.
    - The gallery page features a zoom in effect when you hover over images to give the user a more interactive experience.
    - This gallery page is valuable to the user as they will be able to easily identify the types of styles the site is capable of making.


![This is an image](assets/images/readme_images/full_gallery_page.png)


- The Contact Us Page
    - The contact page features a form where the user can enter their information for a style request to be sent.
    - The contact page encourages the users to detail out the style they want for the service to work properly.
    - The contact page is valuable to the user as it gives them flexability over what they want the service to provide.

![This is an image](assets/images/readme_images/contact_page.png)

**Features Left to Implement**
- I would have liked to add uppload button to the contact page. So the user can upload their references more easily. It would also be usefull if the user has a unique design that they've made.

## Testing

- I have tested this project site on different web browsers. Google Chrome, Microsoft Edge and Mozilla Firefox have all been tested and are working.
- Tests while using the site on a Samsung smartphone is also working.
- I have confirmed that the site is looking good and is responsive on different screen sizes by using the devtools device toolbar.
- I have confirmed that the form requires writen entries in every field and is working as intended. The email field will only accept an email and the submit button will send the data to the [formdump](https://formdump.codeinstitute.net/) site.

## Bugs
**Solved bugs**
 1. - I used a div with a linear-gradient to overlay my background image, but the overlay would block the nav-bar from being clickable.
    - I solved the issue by removing the div and used the linear-gradient inside background-image property
 ```
 background-image: linear-gradient(rgba(4,9,30,0.3), rgba(4,9,30,0.3)),
 ```
 2. - The images in the "check out our gallery" wasn't responsive when the screen size shrunk when I used the column-count property.
    - It was solved by using the grid-template-columns property.
 ```
grid-template-columns: repeat(auto-fit, minmax(px, fr));
 ```

**Unfixed bugs**
- On contact page, the description is responsive but not when you start to expand the text field area. I used a media query to change the size of the description but that stopped working when the text area was alterd. 
```
@media screen and (max-width: 900px){
.your-description textarea {
    width: 90%;}
}
```

## Validator Testing

- HTML
    - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcarl-tallman-95.github.io%2FUnique-kicks%2F)
- CSS
    - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fcarl-tallman-95.github.io%2FUnique-kicks%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)

    ## h2
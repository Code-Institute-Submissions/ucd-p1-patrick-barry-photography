# Patrick Barry Photography

Patrick Barry Photography is an established photography business in Munster. Their main business is wedding photography but in the off season they also photograph on location and interiors B2B. They also enjoy landscape and food photography.

Patrick Barry Photography require a “less is more” online presence.

The goal of which is to -

##### 1 - Generate business leads -
* They would prefer to gather contact details from their website rather than potential customers phoning them, because they are often unable to answer the phone.

##### 2 - Display their best work -
* They would like a neat easy to use area of their site to display a small amount of their best work to wow potential customers.
* This should be user friendly and responsive because sometimes they direct potential clients to their mobile devices when they meet them on location.

##### 3 - Generate a positive emotional response -
* They would like users/visitors of their site to feel good about PBP as a potential choice of photographer.
* They want to make use of their client testimonials (real people, real results) to assure other potential clients of their past successes and their likability factor.
* The photo content should be WOW as opposed to overkill (too much).
* The experience should be easily navigable with minimal effort/clicks to contact.

https://github.com/barra1212/ucd-p1-patrick-barry-photography/blob/master/documentation/client-considerations.pdf

<hr/>


## UX

The project needs to be clean and minimal in design to reflect the style of photography favoured by the client and most sought after by his clients in turn.

#### User Stories

* As someone looking for a wedding photographer,<br>
Ann Walsh from Bandon wants to find a photographer that<br>
stands out from the crowd among the hundreds that she sees online.

* As a amateur photographer,<br>
John Allen wants to quickly see what a photographer deems their<br>
best work up front and centre on a photography website homepage.

* As someone looking for a photographer, and not very trusting by nature,<br>
Mary from Waterford wants to see genuine client testimonials<br>
which reassure her before committing.

* As someone who hates all the pinks/purples of most sites that target the wedding industry,<br>
Kate is always more inclined to stay on a site that is<br>
beautifully minimal and well designed than one that is “pretty in pink”<br>
and full of endless services/offers.

https://github.com/barra1212/ucd-p1-patrick-barry-photography/blob/master/documentation/user-stories.pdf

<hr/>

#### Design Considerations

Some thoughts as a designer beginning this project.

https://github.com/barra1212/ucd-p1-patrick-barry-photography/blob/master/documentation/design-considerations.pdf

<hr/>

#### Site Navigation

Considering the minimalistic requirement of the client, very few pages are used and the navigation is clean.

https://github.com/barra1212/ucd-p1-patrick-barry-photography/blob/master/documentation/site-navigation.pdf

<hr/>

#### Wireframe Mockups

See document linked in below showing mobile first approach how the site should appear firstly on smaller mobiles, through to tablet, then desktop.
Some divs will utilise Bootstrap hidden class to disappear on mobile so page content is not too large (tall).

https://github.com/barra1212/ucd-p1-patrick-barry-photography/blob/master/documentation/wireframe-mockups.pdf

<hr/>


## Features

In keeping with the clients desires, this website is not heavy on features, but works perfectly thus creating a positive emotional response for the user.
 
- Logo - New unique logo created for the client.
- Menu - Neat small menu, collapsing to a centred hamburger style menu on mobiles.
- Grow on Hover - Small animation on hovered images.
- Testimonials - Prominent on homepage.
- Call to Action - Wanna Book is a constant throughout the site, and becomes sticky (to bottom) on mobile devices.
- Contact Page form is neat and easy to use.

<hr/>


## Technologies Used

This site is constructed in HTML using a simple bootstrap framework boilerplate template.

Bootstrap CSS is used throughout and further styled with the file - /assets/css/style.css

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to enable hamburger dropdown menu on smaller mobile devices.


## Testing

##### User Stories addressed

* As someone looking for a wedding photographer, Ann Walsh from Bandon wants to find a photographer that
stands out from the crowd among the hundreds that she sees online.<br>
<b>Achieved by striking colour scheme and large logo in header</b>

* As a amateur photographer, John Allen wants to quickly see what a photographer deems their
best work up front and centre on a photography website homepage.<br>
<b>Achieved by photography categories being identified by an image</b>

* As someone looking for a photographer, and not very trusting by nature,
Mary from Waterford wants to see genuine client testimonials which reassure her before committing.<br>
<b>Achieved by client testimonials appearing below relevant photography category</b>

* As someone who hates all the pinks/purples of most sites that target the wedding industry,
Kate is always more inclined to stay on a site that is beautifully minimal and well designed than one that is “pretty in pink”
and full of endless services/offers.<br>
<b>Achieved by neutral colour scheme appealing to both men and women, and by less frills overall</b>

<hr/>

##### Initial-Scale Beware!

The main issue encountered was when media queries would not work. The site did not behave responsively.
The logo did not scale down properly and ```divs``` did flow as desired.
My mentor and student support were stumped also and unable to find the solution.

After much online research of the issue I found a forum thread on www.stackoverflow.com which provided the solution.

###### My code below (1.0) broke my media queries -

```
meta name="viewport" content="width=device-width, initial-scale=1.0"
```

###### Changing "1.0" to "1" fixed the issue -

```
meta name="viewport" content="width=device-width, initial-scale=1"
```
Lesson learned!

<hr/>

##### Responsive Testing
Responsive behaviour of website tested on a random selection of phones, tablets and desktop browsers using https://www.browserstack.com/
extension in Firefox.

<hr/>

##### HTML Code Validation
HTML code tested using open source tool at https://validator.w3.org/

*RESULT - Document checking completed. No errors or warnings to show.*

<hr/>

##### CSS Code Validation
CSS code tested using open source tool at https://jigsaw.w3.org/css-validator/

*RESULT - Congratulations! No Error Found.*

<hr/>

##### Contact Form HTML Code Validation

Fields tested, form will not send unless fields contain data. ```required```

Email field tested, form will not send unless email field contains @. ```input type="email"```

<hr/>

## Deployment

Website is constructed in Cloud9 and linked to a Github repository.

```git commits``` performed randomly throughout web construction.

Github pages activated on repository for live viewing -

https://barra1212.github.io/ucd-p1-patrick-barry-photography/

<hr/>

## Credits

#### Content
The website text is written (made up) by the developer, rather than using Lorem Ispum

#### Media
The photos used in this site were obtained from ...
- Developers own photographs
- Developers acquaintance's photographs with their permission
- www.images.google.com

#### Acknowledgements

Colour Psychology credit to https://neilpatel.com/blog/psychology-of-color-and-conversions/

Hover Grow functionality credit to http://ianlunn.github.io/Hover/#effects

Contact Form credit to Code Institute tutorial "Rosie Odenkirk CV project".
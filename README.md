# Wire-apps-test

# Template one - Cohen Homes Leased Story 

It is a hand constructed **Mave compatible HTML template** of the social media text post titled Cohen Homes Leased Story. It complies with the drawings, and structural specifications given in the assignment.

## Project Structure

index.html - Main template file

## Assumptions

1. ** There is no direct access to Mave Platform : **

The work on the template was not performed with the Mave editor or template environment and it was created manually with the help of HTML and CSS boilerplate.

2. ** Fonts **
The `Austin News`, `Benton Sans` fonts connect through the free CDN available in GitHub.
It is assumed that they look the same as fonts described in the original Figma design.

3. ** Background Image **
An example picture is the one taken on demo basis provided by [Unsplash](https://unsplash.com). Dynamically it will be injected in production using:
```html
data-field="home_property_image"
```

4. Static testing text :
Fixed stencilled text is used, such as `"Leased"` and `"30 WELLINGTON STREET W #1204"` to be accurate in layout and design. Mave makes these fields dynamic.

5. ** Logo Placement **
The logo `Cohen Homes` is supposed to be locally placed in `assets/` folder as `3.png`. Here You provided logo text is black. But in the reference logo text is white . So here Black one is used . 



# Template two - Jodie Jakobczak Open House & Just Listed Post 

## Assumptions

1. Font Replacement :  
The initial font has the font named as `"Kepler 3 VF Regular"`, which is an Adobe font and a paid-licensed one. I download font family from the other site and host in the GitHub.

2. Mave System: 
The design of the templates was done manually using the correct Mave-compatible data-field attributes, in the conventional form of a boiler plate in the proprietary system of Mave, which was inaccessible.

3. Responsiveness:
 The templates were made to be fixed dimensions to the reference (e.g. 1080x1350px Template 2) and thus lack responsiveness out of the box.

4. Open House Date/Time: 
This is an optional field, when the post type is Open House.


# Template three -  FHL Open House Post 

## Assumptions

1. Inaccessible Mave System
The template has not been constructed with the help of Mave editor or the live template preview tools. The data-field attributes were used to define all editable elements in manner compatible with Mave.

2. Font Substitutions
Fonts referred to were Adobe Fonts (The seasons and Absolute Beauty). Being not accessible, So I Download the font family file from the other site for the `"The Season"` host it used Gitgub .  The `"Absolute Beauty"` font  were replaced by:

The cursive version of Great Vibes is used in place of Absolute Beauty

Google fonts allowed to download the font named "Montserrat" and it was provided as is.

3. Dynamic Fields
Property address field can be edited through data-field and contenteditable, with the following calculations like square foot, open house time and listing photo that would be injected in place dynamically in production by Mave.

4. Established dimensions of the layout
The work requires the laying of 700X700px canvas, as indicated in the assignment reference. The responsiveness is also not mentioned because the format of a post is predetermined in the social networks.

5. Logo Asset
The asset/ folder contains the Forest hill legacy logo and it is uneditable. Based on the instructions of the assignment, it is assumed to be steady.
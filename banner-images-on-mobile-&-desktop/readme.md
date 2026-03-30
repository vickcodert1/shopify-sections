[![Show Different Banner Images on Mobile & Desktop in [HORIZON Theme Shopify]](https://i.ytimg.com/vi/SINWu9dHG3s/maxresdefault.jpg)](https://youtu.be/SINWu9dHG3s?list=PLvT_6E7D1NZIlHa09cgswsjD9QunUpHKy)

### How To Show Different Banner Images On Mobile & Desktop In Shopify?

## For Horizon Themes

Display On Desktop Only With Following Code:

```@media screen and (max-width: 750px) {
  .hero,
  slideshow-component {
    display: none;
  }
}
```
## Display On Mobile Only With Following Code:


```@media screen and (min-width: 750px) {
  .hero,
  slideshow-component {
    display: none;
  }
}
```
## For Dawn Theme 15.4.0

[![](https://i.ytimg.com/vi/COPugLSWb8g/maxresdefault.jpg)](https://youtu.be/COPugLSWb8g)

Use following code to display different banner images on Mobile and Desktop

Display On Desktop Only With Following Code:


```@media screen and (max-width: 750px) {
  .banner, slideshow-component {
    display: none;
  }
}
```
Display On Mobile Only With Following Code:


```@media screen and (min-width: 750px) {
  .banner, slideshow-component {
    display: none;
  }
}
```
## For Dawn Theme 12.0.0 and below

[![](https://i.ytimg.com/vi/zUnVUOEKFSA/maxresdefault.jpg)](https://youtu.be/zUnVUOEKFSA)

In this tutorial, we’ll guide you through the process of Different banners for both the desktop and mobile versions of your Shopify store.

## Step 1: Overview of the Problem
Let’s start with an overview of the issue. You want a unique banner for the desktop version and another for the mobile version of your Shopify store. This can significantly improve the user experience and make your store more visually appealing across different devices.

## Step 2: Demonstration
In the accompanying video, we provide a step-by-step demonstration. The narrator takes you through their own Shopify store, showing the desktop version with one banner and the mobile version with a completely different image. The goal is to help you achieve this customization seamlessly.

## Step 3: Publishing and Previewing
The tutorial includes a walk-through of the backend of a Shopify store, demonstrating how to publish and preview theme changes. The narrator updates the desktop banner, adjusts its settings, and then adds a separate banner for the mobile version.

## Step 4: Adding Custom CSS Code
This code ensures that the desktop banner appears only on desktops and the mobile banner only on mobile devices. The tutorial emphasizes updating the section IDs in the code to match your specific banners.


```/* Code for Desktop Banner */

@media screen and (max-width: 480px){
  #Banner-template--16309149270190__image_banner {
    display: none;
    /* Code contrubution by websensepro.com */
}}

/* Code for Mobile Banner */
@media screen and (max-width: 480px) {
#Banner-template--16309149270190__abae02e2-150e-4941-9c89-b7fb8f854e46 {
    display: block !important;
  /* Code contrubution by websensepro.com */
}}

#Banner-template--16309149270190__abae02e2-150e-4941-9c89-b7fb8f854e46 {
    display: none;
}
```
## Step 5: Finding Section IDs
The video illustrates how to find the section IDs for your banners using the browser’s inspect element feature. This step is crucial for tailoring the CSS code to your store’s unique structure.

## Step 6: Implementing CSS Code
With the section IDs in hand, the tutorial demonstrates how to edit the base.css file by adding the provided CSS code. It’s a straightforward process that even those new to coding can follow.

# Responsive Portfolio
The purpose of this project was to create a responsive porfolio page using CSS Bootstrap. The aim was to ensure that the layout and styling was consistent across all pages regardless of the viewport/screen size.

## First steps: Navbar and Footer
**Navbar**: I initially started with adding a navbar for each site. I opted for putting the navbar within the header tag as I had difficulties with expanding the width within the body of the page. Later on during the project, a toggler was embedded added with links to the other pages.

**Footer**: I attempted to use a similar navbar to make the footer but there were issues sticking the footer to below the page and centering the text within the footer. During my research, I discovered the navbar was designed to have text aligned to the right. Therefore I opted to use CSS to create the footer but then I run into an issue with a space appearing above and below the footer. I used the '.position' and '.min-height' class to remove the space. 

## Second steps: Body and content 
The [My Porfolio](index.html): The 'img-thumbnail' class was used to give the image more depth and a 'float' was used to keep the image in-line with the text.

The [Contact Page](contact.html): Built with form element using Boostrap all contained within one column

The [Portfolio](portfolio.html): Built with a series of 3 rows and 2 columns to hold images. The size of images was determined based on the size of the container to avoid images exceeding the container when screensize was reduced. Unfortunately I was not able to reduce the spacing within the 2 columns on a desktop screen but this spacing was eliminated as screen size was minimised. 

**Screenshot**

## Final Steps & Conclusion:
Tidying up formatting, including semantic tags and improving the overall styling of page. 

## Built with
[Boostrap v5.0](https://getbootstrap.com/)

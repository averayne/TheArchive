The custom CSS includes a centered title that overlays the carousel. It includes padding without interfering with the nav bar on mobile devices. When using the Bootstrap framework I couldn't get the title to overlay the carousel and was going for a very specific design. I also added the content boxes and image overlay boxes for readabilty. They also needed an opacity to show the background image and keep the theme. The CSS has been greatly reduced to only include neccessary elements. 

The carousel was the most challenging because I had to implement the title overlay while keeping the title static. Without the overlay it sits right below or on top of the image and disapears when the carousel changes. 

The Scrollspy component was the easiest to implement because I just had to link it to the navbar and add the scroll element which is included in Bootstrap. It also works when using keyboard only with the tab index. 

The Boostrap framework has changed the way I view components and the architecture of a project. Instead of treating each section as a block of custom code, I've started to view the site as a collection of reusable pieces. Bootstraps pre-built components have made my code more organzied and intentional. 

Bootstrap's limited styling flexibility wasn't something I particularly enjoyed, since customizing beyond defaults felt restrictive. However, not having to write up every piece of logic with JavaScript saved me a significant amount of time and frustration. 
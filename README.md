# CSS Challenge - SelectCode

## Description
### General Layout
For the General Layout of the Dashboard and the sidebar I used CSS Grid, which makes it easy to adjust the width of the Dashboard when the sidebar collapses.
### Dashboard Layout
For the Layout of the Content on the Dashboard I used Flexbox. By using Flexbox the individual Items on the dashboard automatically center themselves and wrap into a new row when there is no more space left.

## Difficulties
### Dashboard content
When designing the Dashboard itself I ran into some problems with making the dashboard scrollable while the header and sidebar stay in place. Ultimately I settled on using ``` overflow-y: scroll; ``` for the content on the dashboard and hiding the scrollbar. 

### Responsive Design for different screen sizes
When it came to make the Design respond well to different screen sizes, I initially struggled with making the layout I made for wide screen devices work on mobile. Especially the small Logo in the upper Left corner of the mobile site was a problem at first, which I managed to beat by including a new Image in my HTML that only becomes visible on smaller screens. 

### Collapsing the Sidebar
Since I do not have much experience with using JavaScript I had some problems to make the sidebar collapse in the beginning. But after some research I was quickly able to solve that problem as well. I also tried to add some animations to the collapsing of the sidebar by using ``` @keyframes ``` , but I ended up abandoning that idea, because I could not get the names of the different sidebar items to smoothly appear when opening the sidebar.


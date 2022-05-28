# Cloutsmith Portfolio

Cloutsmith Portfolio is a website created for those who are looking to hire a web and mobile software  developer for their business. Users of this site will be able to see various services rendered, know more about the company, contact Coutsmith.

The live website can be found here [Cloutsmith Portfolio](https://gbemisola23.github.io/Cloutsmith/index.html).

![responsive](/images/Screenshot 2022-05-28 at 00.26.06.png)



## Features

* **Navigation**
  - Fixed navigation bar includes links to Home, About and Contact sections to allow easy navigation through the page. 
   
  
![navigation](https://user-images.githubusercontent.com/80278757/157774697-d9a78bc0-c8ea-4f33-9146-2790d12b46f7.png)



* **The Header**
  - The top left corner shows the name of the website 
  - The right hand corner shows the Home, About and Contact section. 
  
![intro](https://user-images.githubusercontent.com/80278757/157774716-ebc1b4b8-5ef6-4a84-91fd-7a1a9bdedee5.png)


* **Home Section**
  - A brief description of the services the company renders.
  - The mid-page contains the background image.
  - The footer contains the company's contact detail and copyright.
  
  
![projects](https://user-images.githubusercontent.com/80278757/157774772-1af914cc-979f-4c3b-9460-a8ac84333c9f.png)




* **About Section**
  - In this section, the user will know more about Cloutsmith.
  - The footer contains Cloutsmith's Contact details and copyright.
![about](https://user-images.githubusercontent.com/80278757/155027291-86677484-2db4-4d77-b331-e7f397e63e75.png)


* **Contact Section**
  - A simple form that collects  Name, Email and Message for users that wants to get in touch with me.
  - The footer contains Cloutsmith's Contact details  and copyright.
    
![contact](https://user-images.githubusercontent.com/80278757/155027300-62d70c6d-1949-474f-af2c-808cfcbe34dd.png)


* **The Footer**
  - The footer section includes Cloutsmith Contact info and copyright.

  
![footer](https://user-images.githubusercontent.com/80278757/155013571-a4a81c91-8f39-4689-8d46-5a8e2b891d63.png)


*


## Testing

* I've tested that this page works in Chrome and Firefox (mobile and desktop versions).
* I've confirmed that this project is responsive on all screen sizes using dev tools.
* I confirmed by testing with users that the text of all sections is readable and easy to understand.
* I've confirmed that the form works, requires entries in every field and the submit button works.

### Validator Testing

  * **HTML** 
    - No errors were found when passing through official W3C Validator.

  * **CSS**
    - No errors were returned when passing through the Jigsaw.
  
  * **Accessibility**
    - I confirmed that the colours have enough contrast and fonts chosen are easy to read, and all links, icons and images have descriptive text for screen readers running it through Lighthouse in Chrome DevTools.

    - **Desktop**

       ![lighthouse-desktop](https://user-images.githubusercontent.com/80278757/155611377-5fc53857-4da7-474d-887e-9ff30803ec9e.png)

    - **Mobile**

       ![lighthouse-mobile](https://user-images.githubusercontent.com/80278757/155611357-38f4ae37-b919-4fff-825d-3aa920aaa42f.png)


### User Experience 
  * Users got confused when the link to the live site in the Portfolio project opened the same webpage in another tab. To fix this, I removed the button of this project that gives them access only to the code on GitHub. I also change the colour of the Live Site button to provide more emphasis to the code of each project.
  * Mobile users found it difficult to read justified text. To solve, I aligned the text to the left.
  * I fixed the navigation bar on top of the desktop version and on the bottom for mobile to guarantee that the navigations links are easier to access by small hands. 

     
### Bugs and Errors

  * **Solved**
    - Because this site was built just using HTML and CSS and I used the action="mailto:email" attribute the form show a security error. I solved this issue by deploying in Netlify and using their built-in form handling.
    - When I first passed through the W3C Validator all anchors elements were inside the buttons tags resulting in errors. So I removed and the errors are gone. 
    - All colours were changed to be more accessible for those who have a visual deficiency.
    - The images in the Portfolio section was background images using two divs and positioning, resulting in a broken style on medium and smaller screens and impossible to detect by screen readers. I've solved using Adobe Photoshop to create the image and add them to the HTML using img element and alt attribute.
    - After implementing an arrow up button to help users goes to the top of the page I realize that the buttons don't work because I've added the id attribute in the fixed navigation. I changed the location of the id to the body element to fix the issue.

  * **Unfixed**    
    - No unfixed bugs.
 

 
     
## Deployment

The site was deployed to Netlify pages. The steps to deploy are as follows:
   - In the Netlify overview click on **Add new site**
   - Choose **Import an existing project** on the dropdown menu
   - Click on the GitHub button to connect to the Git provider
   - Chose the repository of the project that you want to deploy
   - Click on **Deploy site** and after a few seconds, you will have access to the URL of the deployed site.
   - Go to **Domain settings** > **Options** > **Edit site name** to change the site name and personalize the URL.
 
 The live website can be found here [Cinthia Fontoura Portfolio](https://cinthia-fontoura-portfolio.netlify.app/).
  
 
## Credits


* Homepage banner from [https://www.pexels.com].
* About and contact banner from [www.freepik.com<]
* Icons from [Font Awesome](https://fontawesome.com/)
* Fonts from [https://fonts.google.com/]

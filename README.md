![Banner](https://github.com/moniquejb/cristina-conrique-psychology/assets/54107967/5b0f75b1-c6d0-4337-87f0-fc4b800622af)

# Cristina Conrique Psychology Website

https://psicologaconrique.com/

This website, built in 2021, was made to promote the online services of Mexican psychologist, Cristina Conrique. As she operates solely in Spanish, the website content was created in Spanish only (feel free to use that translator :wink:). The website is hosted on [Netlify](https://www.netlify.com/) but the custom domain and email are registered through [Hostinger](https://www.hostinger.com/).

## Technologies
* JavaScript
* React.js
* CSS (SCSS)
* HTML

## Features
* **Email.js & Google reCAPTCHA:** As this project was created entirely on the frontend, I made use of Email.js to send the messages from the contact form directly to the client's professional email address. The Google reCAPTCHA checkbox appears when a user completes the required fields, and a form cannot be submitted without this step being successful. The token received is then verified on the Back End by Email.js once the form is submitted.
* **GeoJS API:** As the client works online, she treats patients from all over the world and works in multiple currencies. I used the [GeoJS API](https://geojs.io/) to fetch the user's country location and apply the correct currency and rates to the _'Tarifas (Prices)'_ page. The user's country is also automatically entered into the contact form using this API, but can be edited by the user if necessary.    

## Development Process
### Design
As a trained Information Designer, I was able to use my graphic design skills to create a designs of each section of the website using Adobe Illustrator & Photoshop (screenshot below). I mostly based my code on these layouts, but made multiple changes when something didn't translate well from static images to a functioning website. I also designed the logo, created or modified all of the images used and shot the photo of Cristina Conrique for the _'Sobre Mí (About Me)'_ section. 

[![Layout](https://i.postimg.cc/Y9bN82rh/image.png)](https://postimg.cc/r0Rtwktk)

### Testing
I used [Responsively](https://responsively.app/) and Chrome Devtools to guide me in creating media queries and for testing them. I also frequently served localhost onto a mobile and tablet for testing media queries or general functionality. I mainly used Lighthouse to test performance and am working on finding ways to speed up the website, particularly for mobile devices.

[![LinkedIn badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mjblignaut) [![Instagram badge](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/monique.jaimee/) [![Gmail badge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:moniblig@gmail.com) 

To setup & start:
- 
1. Run npm install or yarn
2. Run npm start

Instructions:
-
<strong>You may spend between 2-4 hours for this challenge.  You will be paid $5 per hour (so $20 for 4 hours).
<br/>Your chances of being hired will be better if you spend more hours doing this challenge.
<br/>Please read ALL instructions before starting
</strong>
1. Clone the repo
2. Create a new BRANCH called 'challenge'
3. Choose a CSS framework of your choice and install it + include it in the app in /client/app/app.js
4. Include normalize.css in the app (it is already installed in package.json so you just need to include it in the app in /client/app/app.js)
5. Integrate autoprefixer into webpack via postcss-loader (it is already installed in package.json and postcss.config.js)
6. Make sure the app is running your CSS framework, normalize, and autoprefixer
7. You will be working with two break points.  One for 360px and one for desktop.  They are in the folder /psd. Choose the one you would like to start with
8. Using best practices and with responsive design and cross-browser compatibility in mind, you will be implementing the PSD files to:
<br/>HTML: /client/app/components/home/home.html
<br/>CSS: /client/app/components/home/home.scss
<br/>JS: /client/app/components/home/home.controller.js
9. We encourage you to use any tool you would like, including Photoshop
10. For font, set "Avenir Next" as the primary default and "Open Sans" as the secondary default
11. The table should be generated dynamically using data from the controller
12. In the PSD file, you will see a red "click" button.  You will program the controller to open a SweetAlert2 modal when the button is clicked.  Do not design the modal, just leave it as the default.  SweetAlert2 is already installed and included in the app, but there is one more step you need to do before you can use it in the controller.
<br/>SweetAlert2 Docs: https://sweetalert2.github.io/
13. When you are finished, submit a PULL REQUEST to the master branch.  In your pull request, list all of the tools / websites you used to help you finish step 8/9
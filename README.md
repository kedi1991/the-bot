**<h1>The bot</h1>**
![mockup for desktop home page](./assets/images/project_design/mockup.png)

The bot is a simple CLI program that can create a customized convresation with a person based on their responses. It has a limited topics to discuss because all discussions are created from local files.

Visit our [website](https://the-bot.herokuapp.com/) and play!!!!
<h2>1. Purpose of the project</h2>

The purpose of this project is to demonstarte logic and decision making capability based on a simple pool of information. The program has been trained and tweaked to correct errors and make it more "human" and demonstrate how AI can be used to automate some common repetitive tasks and releave humans of some duties.

<h2>2. User stories</h2>

- The program is small and uses minimal resources
- The program runs on all all browsers
- The program has uses a selection of questions in random order from a pool. 
- The nature of conversation from one user should be different from the other
- The user is allowed to freely write responses in their own way. The program should look out for specific patterns in user replies to make decisions
- The program handles erroneous input gracefully


<h2>3. Features</h2>

- CLI interface deployed on web
- Chat bot

<h2>4. Future features</h2>

- Incorporating AI libraries to improve data processing and accuracy of results


<h2>6. Wireframes</h2>

Wireframes were designed using Ms paint on windows 10 as shown below

**Desktop/ tablet/ mobile page**

a) Home page

![wireframe for desktop home page](./assets/images/project_design/wireframe_desktop_mobile.png)
![wireframe for desktop home page](./assets/images/project_design/wireframe_desktop.png)

b) failure/ pass message
![wireframe for desktop home page](./assets/images/project_design/wireframe_desktop_mobile_message.png)


**MOBILE PAGES**

a) game play with controls

![wireframe for mobile home page](./assets/images/project_design/wireframe_mobile.png)

<h2>7. Technology</h2>

- The site is built on HTML, CSS, JS, and Python.

<h2>8. Testing</h2>

All html elements where tested for intended functionality, all links where tested and the screen responsiveness was verified on mobile, tablet, and desktp screen resolutions.

<h3>8.1 code validation</h3>

The overall quality of the html, css, and JS code was checked using the [html validator](https://validator.w3.org/), [jigsaw](https://jigsaw.w3.org/css-validator/validator/), and [PiliApp](https://www.piliapp.com/javascript-validator/) online tools respectively.

<h3> 8.2 fixed bugs</h3>

No errors found on html and JS code

![html warnings on validator](./assets/images/tests/test_flight.png)

<h3>8.3 supported screens and browsers</h3>
 
The site was tested on the browsers listed below

| S/N | Browser         | Version        | Platform       | Screen sizes (mobile, tablet, desktop) |
|-----|-----------------|----------------|----------------|----------------------------------------|
| 1   | Mozilla firefox | 105.0.1        | Windows 10 x64 | Passed all                             |
| 2   | Google Chrome   | 105.0.5195.127 | Windows 10 x64 | Passed all                             |
| 3   | Google Chrome   | 105.0.5195.136 | Android 10     | Passed mobile view                     |

<br>


<h2>9. Forking and Deployment</h2>

<h3>9.1 Forking the project</h3>
This will make a copy of the project on your github repository.

1. Log into GitHub and locate your repository.
2. On the top left corner, search for "kedi1991/project-flight-sim" and select it from the results.
3. On the right hand side of the page select  **fork** to create and copy of the original under your repository

<h3>9.2 Via gitpod</h3>

To deploy the project using gitpod, run the command `add .` followed by `git commit -m "descripton of code changes to push"` 
Finally, run `git push` to push the changes to yout github repository.

<h3>9.3 Via github pages</h3>

1. While on the project root folder, go to **settings** .
2. Navigate to the **pages** tab on the left navigation panel.
3. Go to **Build and deployment** > **Branch**. Select **main** then click **save**.
4. At the top just below the **GitHub Pages** heading, you will be notified of successful deployment as shown in the image. This may take about 60 seconds to reflect. Incase It takes longer, try refreshing the page.

<h2>10. Known bugs</h2>
1. Control using the long press on the mobile device controls does not produce the desired effect as that on the keyboard on desktop. This makes the reaction time of the craft so slow.

<h2>11. credits</h2>

http://www.learnex.in/useful-english-greetings-and-responses/
https://oneminuteenglish.org/en/greetings-in-english/
https://www.jumpspeak.com/blog/english-swear-words
https://www.lihaoyi.com/post/BuildyourownCommandLinewithANSIescapecodes.html

**Thanks to:**
- CI personal mentor - Harry Dhillon for professional guidance
- The CI jul-2022-5p class and tutors




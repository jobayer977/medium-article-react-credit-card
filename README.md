
# Getting started with React Credit Card

Photo by rupixen.com on Unsplash

In this tutorial, we’ll learn about an interesting React npm package called [react-credit-card](https://github.com/Jobayerdev/react-credit-card).

• [Demo](https://econ47.netlify.com)

First, we create a React app with the npm command line. Open your terminal, and run npx create-react-app myapp after you create your React app. Then type the command npm start. Before you start your app, you need to go to the project directory with cd myapp, and then you run your app.

OK, now let’s move onto our react-credit-card project.

## Install

    npm install --save react-credit-cards

After you install, you need to start your app again with npm start.

## SetUp

Now we create a components folder in your src directory. In this folder, we create a file and name it MyCards.js. Now our folder structure looks like this:

![Home Directory](https://cdn-images-1.medium.com/max/2000/1*-pUwmKF1t94cfwS6epViFA.png)*Home Directory*

Open your MyCards.js file, and create a simple functional React component. Now our MyCards.js file looks like this:

![](https://cdn-images-1.medium.com/max/2000/1*i_T3m4O1iuWfJli1_1SudQ.png)

OK, now we’ll import some things from our react-credit-cards package. We import two things from react-credit-cards and place our Mycards.js file at the top.

* Cards: import Cards from "react-credit-cards"

* Style sheet: import "react-credit-cards/es/styles-compiled.css"

So far, our MyCards.js file looks this:

![MyCards.js](https://cdn-images-1.medium.com/max/2320/1*TmGUS1JtQvlOuhk9_j8Afg.png)*MyCards.js*

After we successfully import the cards and the style sheet, we move onto actually coding.

* Create a state, and define the default value as an object

* Create a form, and also create a change handler

So now our MyCards.js look like this:

![MyCards.js](https://cdn-images-1.medium.com/max/2316/1*0DwgPJm-HajjdQV3HDY4ng.png)*MyCards.js*

After you successfully do this step, it’s time to implement our Cards component which provided our react-credit-cards package.

![](https://cdn-images-1.medium.com/max/2000/1*t0P99v1VWbrZqWbe1mmHUw.png)

The card component accepts four arguments as props: CVC, expire, name, and number. This pass our value from input box to this component’s props using the state.

So far, our MyCards.js file has all of this code:

<iframe src="https://medium.com/media/b84dd4dc503ecab748351a032c6e82ba" frameborder=0></iframe>

OK, now our work is done in the App.js file. We import the MyCards.js file and render. So open your App.js file in the src directory, and paste this code. This code just imports our MyCards.js components.

<iframe src="https://medium.com/media/39a5cc2c2230ce6abe15af6201f65790" frameborder=0></iframe>

## Styling

In App.css, just grab this code, and paste it. It’s made fun.

<iframe src="https://medium.com/media/820cb8309f33cb95e708c86fcf559fdd" frameborder=0></iframe>

We completed our app now. Open terminal, and run npm start. I hope you can see your output like this:

![](https://cdn-images-1.medium.com/max/2000/1*pXNHuGdjixnIEa0uk5mhtQ.png)

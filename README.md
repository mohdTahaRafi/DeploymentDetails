# Deployment Details
Here's are my learnings from deployments in Level 0, Level 1 and Level 2 for Super Deployment

## Level 0
I was deploying a web project for the first time, still i did not find any difficulties in deploying the project on Vercel and Netlify.

## Level 1
In this level I was deploying my own project which was in a static folder. In deployment we had to place the base directory as the folder in which our index.html is placed and I was messing that up.

## Level 2
In this level, there were issues in the ``` package.json ``` file which was causing the project to crash. The version of web-vitals dependency was not correct, it should have been 2.1.4 instead of the version 1.1.1. "react" dependency was missing because of which react was not recognised in the project. "react-dom" dependency was missing because of which react could not be able to use on the web. index.html file was also missing in which we had to mount and inject the react files (jsx) . "react-scripts" was also missing because of which the react code was not getting mounted and injected into the index.html file. Another small issue was that the name of the components file were not starting with UpperCase which is mandatory in react apps. I also changed the var used in the components file to const and let for good practise.

# Deploying my first app with StateMesh

**StateMesh** is the first decentralized cloud architecture in the world, replacing conventional data centers with a worldwide network of crowdsourced node operators while preserving AWS/GCP/Azure-like functionality, security, and resilience. Compared to current decentralized computing implementations, its permissionless nature, fair participation mechanism, and decentralized architecture provide notable improvements.

## 1. Project idea
I decided to deploy a single-page web app built using HTML, CSS, and JavaScript. The application renders a heart-shaped particle animation on an HTML5 canvas, creating a visual effect where particles flow to form and maintain the shape of a heart. The purpose of the project was primarily to explore front-end animation techniques and to practice deploying a web application.

## 2. Prerequisites
In order to deploy my app on **StateMesh**, I registered on the platform and followed a tutorial in order to understand how the `StateMesh console` works. After deploying a template-based app, I installed the `StateMesh CLI`, a terminal-based interface for managing deployments. It allows developers to initialize projects, configure settings, and deploy applications directly from the command line.

## 3. Deployment on StateMesh
To make the application publicly accessible, I deployed it using **StateMesh**. The deployment process involved preparing the project files (`index.html`, `heart.js`, `heart.css`) and adjusting the server so that it displayed my `index.html` file. I relied heavily on the `StateMesh CLI`, which made it straightforward to package and publish my application. I was able to push my project files to `StateMesh`, where they were automatically built and hosted. The CLI then provided me with a public endpoint that I could use to access the deployed application in the browser. Throughout the process, I mainly interacted with the platform through terminal commands, which offered a fast and efficient way to manage deployment without needing a separate dashboard.

## 4. Conclusion
Working with `StateMesh` gave me a practical understanding of how simple it can be to deploy a static web application. By using the `StateMesh CLI`, I was able to upload my project files, configure the deployment, and obtain a public endpoint with minimal effort. The platform handled the server setup in the background, which allowed me to focus entirely on the application itself rather than infrastructure details.

Overall, the process helped me expose my project with a public endpoint without needing to manually configure servers or networking, highlighting how `StateMesh` simplifies deployment. 

## [StateMesh Documentation](https://docs.statemesh.net/)
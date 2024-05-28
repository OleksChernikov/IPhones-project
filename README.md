# React Phone catalog

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Marquee Example</title>
<style>
.marquee {
    width: 100%;
    white-space: nowrap;
    overflow: hidden;
    animation: marquee 5s linear infinite;
}

@keyframes marquee {
    0%   { transform: translateX(100%); }
    100% { transform: translateX(-100%); }
}
</style>
</head>
<body>

<div class="marquee">
  <span>WELCOME</span>
</div>

</body>
</html>

Developed to reinforce skills, for self-improvement, and without a commercial purpose.
During the project development, HTML, SCSS, and React/TypeScript were used.

Additionally, external libraries were utilized, such as [classnames](https://www.npmjs.com/package/classnames) for easy class management and [react-spinners](https://www.davidhu.io/react-spinners/) for displaying loading indicators.

The project is built on functional components.
[Context](https://legacy.reactjs.org/docs/context.html) is used for managing the application state and passing data between multiple components without the need to pass props through all intermediate components. 

[BEM](https://en.bem.info/) (Block Element Modifier) methodology was used in the website development, allowing the creation of independent website blocks that could be reused.

## React Phone catalog available at the link
[Project](https://olekschernikov.github.io/IPhones-project/#/)

### To work with the project locally, use the following commands
```git clone``` + *URL* will allow you to download the project to your device
```npm i``` loading project dependencies
```npm start``` will launch the project and display it in the web browser at *http://localhost:3000/*

APP UTILITY :

TextUtils is a Basic React app that helps the user modify their text,
some functionalities of it are converting the text to uppercase, lowercase, copying the text etc..
It also has a darkMode feature that changes the state of the app which changes the background color and text,


Features Used :

The reactRouter helps navigate to different pages(without loading the page)
The app uses react function based components which are present in /src/components/
I've broken it down into 4 components
1. NavBar
2. Alert
3. Textform
4. About

About The Components :

--> The navbar componet includes two "pages" that are on the website and the darkmode button
--> The Alert component is placed right after the navbar which is rendered when the state of "alert" variable 
    is changed { app.js 17/ "" const [alert, setAlert] = useState(null); ""}
--> The textform component has a textform and buttons below it which transform the text into said       functionality
--> The about component is basically just a page to see how the reactRouter setup works there are some deprecated tags like <Switch> which are replaced by <Routes>.


Help :

Note : The "node_modules" folder is included in the .gitignore file 
So Don't forget to reinitialise the "node_modules" folder if you intend on forking the project and taking a look at it yourself..

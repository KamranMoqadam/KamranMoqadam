<style>
/* Add Font */
@font-face {
    font-family: poppins;
    font-style: normal;
    font-weight: 400;
    src: local('Poppins'), url('./assets/font/Poppins-Regular.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: italic;
    font-weight: 400;
    src: local('Poppins'), url('./assets/font/Poppins-Italic.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: normal;
    font-weight: 250;
    src: local('Poppins'), url('./assets/font/Poppins-Thin.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: italic;
    font-weight: 250;
    src: local('Poppins'), url('./assets/font/Poppins-ThinItalic.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: normal;
    font-weight: 275;
    src: local('Poppins'), url('./assets/font/Poppins-ExtraLight.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: italic;
    font-weight: 275;
    src: local('Poppins'), url('./assets/font/Poppins-ExtraLightItalic.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: normal;
    font-weight: 300;
    src: local('Poppins'), url('./assets/font/Poppins-Light.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: italic;
    font-weight: 300;
    src: local('Poppins'), url('./assets/font/Poppins-LightItalic.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: normal;
    font-weight: 500;
    src: local('Poppins'), url('./assets/font/Poppins-Medium.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: italic;
    font-weight: 500;
    src: local('Poppins'), url('./assets/font/Poppins-MediumItalic.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: normal;
    font-weight: 600;
    src: local('Poppins'), url('./assets/font/Poppins-SemiBold.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: italic;
    font-weight: 600;
    src: local('Poppins'), url('./assets/font/Poppins-SemiBoldItalic.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: normal;
    font-weight: 700;
    src: local('Poppins'), url('./assets/font/Poppins-Bold.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: italic;
    font-weight: 700;
    src: local('Poppins'), url('./assets/font/Poppins-BoldItalic.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: normal;
    font-weight: 800;
    src: local('Poppins'), url('./assets/font/Poppins-ExtraBold.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: italic;
    font-weight: 800;
    src: local('Poppins'), url('./assets/font/Poppins-ExtraBoldItalic.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: normal;
    font-weight: 900;
    src: local('Poppins'), url('./assets/font/Poppins-Black.woff') format('woff')
}

@font-face {
    font-family: poppins;
    font-style: italic;
    font-weight: 900;
    src: local('Poppins'), url('./assets/font/Poppins-BlackItalic.woff') format('woff')
}
/* Wave Hand */
.wave {
  animation-name: wave-animation;    /* Name of @keyframes element below */
	animation-duration: .75s;          /* Wave speed */
	animation-iteration-count: infinite;
	animation-timing-function: linear;
	animation-play-state: paused ;
    transform-origin: 70% 70%;	/* Pivot around the bottom-left palm */
	display: inline-block;
	font-size: 36px;
    text-shadow: 0 0 0;
    cursor: wait;
}

.wave:hover {
	animation-play-state: running; /* Play animation on mouse hover */
}

@keyframes wave-animation {
  0% { transform: rotate( 0deg ) }
  25% { transform: rotate( -10deg ) }
	75% { transform: rotate( 12deg ) }
  100% { transform: rotate( 0deg ) }
}
/* Style Header */
header {
    display: block;
    margin-left: 0;
    margin-right: 0;
    text-align: center;
    width: 100%;
}
/* Style Body */
body {
    background: #13171F;
    box-sizing: border-box;
    margin: 0 auto;
}

/* Style Main */
main {
    padding: 45px;
}
/* Style H1 */
h1 {
    color: #008aff;
    font-family: poppins, sans-serif;
    font-style: normal;
    font-weight: 700;
    font-size: 32px;
    text-align: center;
    
}
h1:hover {
    cursor: text;
    text-shadow: 3px 3px 20px #0030ff,
    -2px 1px 30px #0030ff;

}
/* Style img */
img {
    display: inline-block;
    width: 100%;
    height: 100%;
    margin: 0 auto;
    filter: grayscale(100%);
    -webkit-filter: grayscale(100%);
    -webkit-transition: all 1s ease;
}
img:hover{
    filter: grayscale(0%);
    filter: gray;
    -webkit-filter: grayscale(0%);
    filter: none;
    transition: 1s ease;
}
hr{
    border: 0;
    height: 1px;
    background-image: linear-gradient(to right, rgba(19, 23, 31,0), rgba(255, 255, 255,0.75), rgba(19, 23, 31,0));
}
</style>


<body>
<header>
    <img src="./assets/image/CoverGithub.gif" alt="This is the cover readme for github">
    <h1>Hi there , I'm Kamran Moqadam<span class="wave"> 👋 </span></h1>

</header>

<main>
        <hr>


</main>
</body>
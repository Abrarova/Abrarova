<div id="header" align="center">
	<h1>Hi there, I'm Victoria!</h1>
	<h3>Frontend Developer</h3>
</div>
<div id="socials" align="center">
	<a href="linkedin-url">
		<img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
	</a>
	<a href="https://vk.com/vika.aurum">
		<img src="https://img.shields.io/badge/VK-blue?style=for-the-badge&logo=VK&logoColor=white" alt="VK"/>
	</a>
	<a href="https://t.me/Gaunt_W">
		<img src="https://img.shields.io/badge/Telegram-blue?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/>
	</a>
</div>

### About me
- 🔬 I’m currently learning **Web3, GameDev**
- 🎨 Know about my experiences and creative projects [0_0](cv-link)
- 💬 Reach me by [Telegram](https://t.me/Gaunt_W), [email](mailto:vika.argent@gmail.com)
- 🎙️ I speak Russian and English

### Languages and tools
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" title="js" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" title="html" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" title="css" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" title="react" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain.svg" title="git" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg"  title="mysql" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" title="angular" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" title="node" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" title="figma" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/wordpress/wordpress-original.svg" title="wordpress" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/blender/blender-original.svg" title="blender" width="40" height="40"/>&nbsp;
                   
   
### My stat
<div id="stat" align="center">
	<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Abrarova&theme=omni"/>
	<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Abrarova&theme=omni"/>
	<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Abrarova&theme=omni"/>
</div>

---
<h1>Pure CSS Tower of Hanoi</h1>
    <div class="discs">
        <input id="one" type="text" tabindex="-1" readonly>
        <input name="one" type="radio" tabindex="-1" checked>
        <input name="one" type="radio" tabindex="-1">
        <input name="one" type="radio" tabindex="-1">
        <label for="one"></label>
        <div class="disc one"></div>

        <input id="two" type="text" tabindex="-1" readonly>
        <input name="two" type="radio" tabindex="-1" checked>
        <input name="two" type="radio" tabindex="-1">
        <input name="two" type="radio" tabindex="-1">
        <label for="two"></label>
        <div class="disc two"></div>

        <input id="three" type="text" tabindex="-1" readonly>
        <input name="three" type="radio" tabindex="-1" checked>
        <input name="three" type="radio" tabindex="-1">
        <input name="three" type="radio" tabindex="-1">
        <label for="three"></label>
        <div class="disc three"></div>

        <input id="four" type="text" tabindex="-1" readonly>
        <input name="four" type="radio" tabindex="-1" checked>
        <input name="four" type="radio" tabindex="-1">
        <input name="four" type="radio" tabindex="-1">
        <label for="four"></label>
        <div class="disc four"></div>

        <input id="five" type="text" tabindex="-1" readonly>
        <input name="five" type="radio" tabindex="-1" checked>
        <input name="five" type="radio" tabindex="-1">
        <input name="five" type="radio" tabindex="-1">
        <label for="five"></label>
        <div class="disc five"></div>

        <input id="six" type="text" tabindex="-1" readonly>
        <input name="six" type="radio" tabindex="-1" checked>
        <input name="six" type="radio" tabindex="-1">
        <input name="six" type="radio" tabindex="-1">
        <label for="six"></label>
        <div class="disc six"></div>

        <input id="zero" type="text" tabindex="-1" readonly>

        <div class="spacer a"></div>
        <div class="separator ab"></div>
        <div class="spacer b"></div>
        <div class="separator bc"></div>
        <div class="spacer c"></div>

        <div class="tower a"></div>
        <div class="tower b"></div>
        <div class="tower c"></div>

        <div class="win">You win! :)</div>
    </div>
    <div class="bottom"></div>
    <button type="reset">New Game</button>
    label,
input {
    position: absolute;
    top: -10vmin;
    margin: 0;
    border: 0;
    padding: 0;
    width: 30vmin;
    height: 52.5vmin;
    cursor: pointer;
    opacity: 0;
    pointer-events: none;
    -webkit-tap-highlight-color: transparent;
}
input:nth-child(6n + 2),
input:checked + input + input + label {
    left: 0;
}
input:nth-child(6n + 3),
input:checked + input + label {
    left: 30vmin;
}
input:nth-child(6n + 4),
input:checked + label {
    left: 60vmin;
}

label,
input:hover,
input[readonly]:focus + input,
input[readonly]:focus + input + input,
input[readonly]:focus + input + input + input {
    pointer-events: initial;
}
input[readonly],
input:nth-child(6n + 2):checked ~ input:nth-child(6n + 2),
input:nth-child(6n + 3):checked ~ input:nth-child(6n + 3),
input:nth-child(6n + 4):checked ~ input:nth-child(6n + 4) {
    pointer-events: none;
}

#one ~ input,
#one ~ label {
    z-index: 6;
}
#two ~ input,
#two ~ label {
    z-index: 5;
}
#three ~ input,
#three ~ label {
    z-index: 4;
}
#four ~ input,
#four ~ label {
    z-index: 3;
}
#five ~ input,
#five ~ label {
    z-index: 2;
}
#six ~ input,
#six ~ label {
    z-index: 1;
}

input#zero {
    z-index: 7;
}
input#zero:focus {
    pointer-events: none;
}
input[readonly]:focus + input:checked ~ #zero {
    left: 0;
    pointer-events: initial;
}
input[readonly]:focus + input + input:checked ~ #zero {
    left: 30vmin;
    pointer-events: initial;
}
input[readonly]:focus + input + input + input:checked ~ #zero {
    left: 60vmin;
    pointer-events: initial;
}

/* Discs */
.discs {
    position: relative;
    display: flex;
    flex-flow: column wrap;
    justify-content: flex-end;
    margin: 10vmin auto 0;
    width: 90vmin;
    height: 35vmin;
}

.disc {
    z-index: 1;
    border-radius: 1vmin;
    height: 4vmin;
    pointer-events: none;
    transition: order 0.3s step-end;
}
input:checked + input + input + label + .disc {
    order: 3;
}
input:checked + input + label + .disc {
    order: 6;
}
input:checked + label + .disc {
    order: 9;
}

input:focus + input:checked + input + input + label + .disc {
    order: 1;
    transition: order 0s;
    animation: float 3s ease-in-out infinite alternate;
}
input:focus + input + input:checked + input + label + .disc {
    order: 4;
    transition: order 0s;
    animation: float 3s ease-in-out infinite alternate;
}
input:focus + input + input + input:checked + label + .disc {
    order: 7;
    transition: order 0s;
    animation: float 3s ease-in-out infinite alternate;
}
@keyframes float {
    50% {
        transform: translateY(-1vmin);
    }
}

input:focus + input:hover + input + input + label + .disc,
input + input:active + input + input + label + .disc {
    order: 1;
}
input:focus + input + input:hover + input + label + .disc,
input + input + input:active + input + label + .disc {
    order: 4;
}
input:focus + input + input + input:hover + label + .disc,
input + input + input + input:active + label + .disc {
    order: 7;
}

.one {
    margin: 0 10vmin;
    width: 10vmin;
    background: linear-gradient(to right, #eea668, #ed7e1d, #e67e22);
}
.two {
    margin: 0 8vmin;
    width: 14vmin;
    background: linear-gradient(to right, #8ac4ea, #0f9fff, #3498db);
}
.three {
    margin: 0 6vmin;
    width: 18vmin;
    background: linear-gradient(to right, #f0d775, #fc0, #e6bd19);
}
.four {
    margin: 0 4vmin;
    width: 22vmin;
    background: linear-gradient(to right, #666, #000, #333);
}
.five {
    margin: 0 2vmin;
    width: 26vmin;
    background: linear-gradient(to right, #7ee2a8, #09f16a, #2ecc71);
}
.six {
    width: 30vmin;
    background: linear-gradient(to right, #f2a097, #ff3a24, #e74c3c);
}

/* Spacers/Separators */
.spacer {
    width: 30vmin;
    height: 1px;
    flex-grow: 0;
    pointer-events: none;
    transition: flex 0.3s;
}
.separator {
    width: 0;
    height: 100%;
}
.a {
    order: 2;
}
.ab {
    order: 3;
}
.b {
    order: 5;
}
.bc {
    order: 6;
}
.c {
    order: 8;
}

input[readonly]:focus + input:hover ~ .a,
input[readonly]:focus + input + input:hover ~ .b,
input[readonly]:focus + input + input + input:hover ~ .c {
    transition: flex 0s;
    flex-grow: 1;
}
input[readonly]:focus + input:checked ~ .a,
input[readonly]:focus + input + input:checked ~ .b,
input[readonly]:focus + input + input + input:checked ~ .c {
    flex-grow: 1;
}

/* Winning */
.win {
    z-index: 7;
    position: absolute;
    left: 0;
    right: 0;
    top: -10vmin;
    bottom: -7.5vmin;
    color: #966f33;
    font-family: Arial, sans-serif;
    font-size: 6vmin;
    line-height: 17.5vmin;
    opacity: 0;
    pointer-events: none;
    transition: opacity 0.3s;
}
input:nth-child(6n + 4):checked ~ input:nth-child(6n + 4):checked ~ input:nth-child(6n + 4):checked ~ input:nth-child(6n + 4):checked ~ input:nth-child(6n + 4):checked ~ input:nth-child(6n + 4):checked ~ .win {
    opacity: 1;
    pointer-events: initial;
}

/* Everything Else */
body {
    margin: 0;
    background-color: #f8f8f8;
}

h1 {
    margin: 0;
    padding: 5vmin;
    color: rgba(0, 0, 0, 0.5);
    font-family: Arial, sans-serif;
    font-size: 7.5vmin;
    font-weight: lighter;
    text-align: center;
    background: linear-gradient(to right, rgba(150, 111, 51, 0.4), rgba(150, 111, 51, 0.2)),
    repeating-linear-gradient(to right, #eec487, #eec487 3vmin, #f3cf9a 3vmin, #f3cf9a 6vmin, #f8d8a2 6vmin, #f8d8a2 9vmin, #f1ca88 9vmin, #f1ca88 12vmin, #f4d09e 12vmin, #f4d09e 15vmin, #faddb0 15vmin, #faddb0 18vmin, #eec88a 18vmin, #eec88a 21vmin);
}

form {
    text-align: center;
}

.tower {
    position: absolute;
    top: 7.5vmin;
    border-radius: 1vmin;
    width: 5vmin;
    height: 30vmin;
    background: linear-gradient(to right, #d7b889, #b27315, #966f33);
}
.a {
    left: 12.5vmin;
}
.b {
    left: 42.5vmin;
}
.c {
    left: 72.5vmin;
}

.bottom {
    position: relative;
    display: block;
    margin: 0 auto;
    border-radius: 1vmin;
    width: 95vmin;
    height: 7.5vmin;
    background: linear-gradient(to right, rgba(255, 255, 255, 0.3), transparent),
    linear-gradient(#b27315, #966f33 13%, #faddb0 14.5%, #faddb0 27.5%, #966f33 29%, #966f33 42%, #faddb0 43.5%, #d7b889 56.5%, #966f33 58%, #966f33 71%, #d7b889 72.5%, #d7b889 85.5%, #966f33 87%, #b27315);
}

button {
    margin: 7.5vmin auto;
    border: none;
    border-radius: 1vmin;
    width: 35vmin;
    height: 10vmin;
    font-size: 4vmin;
    color: rgba(0, 0, 0, 0.5);
    background: linear-gradient(to right, #c39550, #966f33);
    outline: none;
    cursor: pointer;
    transition: background 0.3s;
}
button:hover {
    background: linear-gradient(to right, #caa163, #a77b39);
}
button:active {
    background: linear-gradient(to right, #cf9844, #9e6f29);
}
</form>

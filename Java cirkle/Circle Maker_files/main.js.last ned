const inputNum = document.querySelector("#inputNum");
const circleContainer = document.querySelector("#circleContainer");

/*Used the codes from the lesson, 
but changed the styles and added some hovereffect on button.
Also changed the random colour picker to a pastel coloured one */

const makeCircles = () => {
        while (circleContainer.firstChild) { 
            circleContainer.removeChild(circleContainer.firstChild);
        }
    if (inputNum.value && inputNum.value < 1000) {
        for (let i = 0; i < inputNum.value; i++) {
            const circle = document.createElement("div");
            circle.classList.add("circle");
            circle.style.backgroundColor = //got help with this pastel colour palette from Stackoverflow.
                "hsl(" + 360 * Math.random() + ',' +
                (25 + 70 * Math.random()) + '%,' + 
                (85 + 10 * Math.random()) + '%)';
            circle.textContent = i + 1;
            circleContainer.appendChild(circle);
        }
    
    } else {
        window.alert("Please input a number between 1 and 1000");
    }
}
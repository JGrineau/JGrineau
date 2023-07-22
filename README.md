# About Me

Hello, I'm JP Grineau! 👋

Welcome to my GitHub page! I'm a passionate developer who loves to create exciting web projects.

## Personal Portfolio

- [Portfolio](https://jpgrineau.com/)

### 🧰 Languages and Tools

<img align="left" alt="Java" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg"/>
<img align="left" alt="Spring" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" />
<img align="left" alt="TypeScript" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-plain.svg" />
<img align="left" alt="Angular" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-plain.svg" />
<img align="left" alt="Git" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
<img align="left" alt="HTML" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain.svg" />
<img align="left" alt="CSS" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain.svg" />
<img align="left" alt="JavaScript" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" />
<img align="left" alt="React" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
<img align="left" alt="GitHub" width="30px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />
<br />

## Projects

- [Project 1](link-to-your-project-1) - Short description of Project 1.
- [Project 2](link-to-your-project-2) - Short description of Project 2.
<!-- Add more projects here -->

## Rock, Paper, Scissors Game

<div style="display: flex; justify-content: center;">
  <div id="game-container" style="text-align: center;">
    <button onclick="play('rock')">Rock</button>
    <button onclick="play('paper')">Paper</button>
    <button onclick="play('scissors')">Scissors</button>
    <p id="result"></p>
  </div>
</div>

<script>
  function play(playerChoice) {
    const choices = ["rock", "paper", "scissors"];
    const computerChoice = choices[Math.floor(Math.random() * 3)];
    const result = getResult(playerChoice, computerChoice);

    document.getElementById("result").innerText = `You chose ${playerChoice}, computer chose ${computerChoice}. ${result}`;
  }

  function getResult(player, computer) {
    if (player === computer) return "It's a tie!";
    if ((player === "rock" && computer === "scissors") || 
        (player === "paper" && computer === "rock") || 
        (player === "scissors" && computer === "paper")) {
      return "You win!";
    } else {
      return "You lose!";
    }
  }
</script>

## Contact

You can reach me at:

- Email: jgrineau95@gmail.com
- Twitter: [@jp_grineau](https://twitter.com/jp_grineau)
- LinkedIn: [JP Grineau](https://www.linkedin.com/in/jpgrineau/)

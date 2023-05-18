<kbd>**Hello World!**</kbd>

<style>
@keyframes neonBlink {
  0% {
    color: #ffffff;
    text-shadow: none;
  }
  50% {
    color: #00ff00;
    text-shadow: 0 0 5px #00ff00, 0 0 20px #00ff00, 0 0 30px #00ff00, 0 0 40px #00ff00, 0 0 55px #00ff00, 0 0 75px #00ff00, 0 0 90px #00ff00;
  }
  100% {
    color: #ffffff;
    text-shadow: none;
  }
}

@keyframes glowingBorder {
  0% {
    border: 2px solid #ffffff;
    box-shadow: none;
  }
  50% {
    border: 2px solid #00ff00;
    box-shadow: 0 0 5px #00ff00, 0 0 20px #00ff00, 0 0 30px #00ff00, 0 0 40px #00ff00, 0 0 55px #00ff00, 0 0 75px #00ff00, 0 0 90px #00ff00;
  }
  100% {
    border: 2px solid #ffffff;
    box-shadow: none;
  }
}

kbd {
  animation: neonBlink 2s infinite;
  display: inline-block;
  padding: 0.1em 0.3em;
  border: 2px solid #ffffff;
  border-radius: 4px;
  text-align: center;
  font-weight: bold;
  text-transform: uppercase;
  font-size: 18px;
  background-color: #000000;
  color: #ffffff;
  text-shadow: none;
  transition: all 0.3s ease-in-out;
}

kbd:hover {
  animation: glowingBorder 2s infinite;
  color: #00ff00;
}
</style>

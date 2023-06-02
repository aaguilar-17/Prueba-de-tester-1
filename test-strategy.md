Plan de ataque test-strategy

- Línea 45: let randomNumber = Math.random() * 10, corrección let randomNumber = (Math.floor() * 100) + 1; 

- Línea 47: const ATTEMPS = 5, correción const ATTEMPS = 10

- Línea 50: const lowOrHi = document.querySelector ('lowOrHi'); correción const lowOrHi = document.querySelector('.lowOrHi');

- Línea 59; let userGuess = guessField.value; corrección let userGuess = Number(guessField.value);

- Línea 66: lastResult.textContent = '!!! Pérdisteis!!!'; corrección lastResult.textContent  = ' Felicitaciones! adivinaste el número!';

- Línea 67: lastResult.style.backgroundColor = 'black'; corrección lastResult.style.backgroundColor = '#00FF00';

- Línea 71: lastResult.textContent = ' Felicitaciones! adivinaste el número!'; corrección lastResult.textContent  = '!!! Pérdisteis!!!';

- Línea 76: lastResult.style.backgroundColor = 'green'; corrección lastResult.style.backgroundColor = '#000000';

- Línea 88: guessSubmit.addeventListener('click', checkGuess); corrección guessSubmit.addEventListener('click, checkGuess');

- Línea 96: resetButton.addeventListener('click',resetGame); corrección resetButton.addEventListener('click', resetGame);



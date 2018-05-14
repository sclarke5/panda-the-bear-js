var image = document.querySelector('.profile-image');
image.src = 'https://placebear.com/200/300';

var cloud = document.querySelector('#left-image img');
cloud.src = 'https://placebear.com/200/300';

var heading = document.querySelector('h1');
heading.innerText = "Sean's Page";

var employment = document.querySelector('#employment h3');
employment.innerText = "Work History";

var background = document.querySelector('body');
background.style.backroundColor = 'blue';

var highlightElements = document.querySelectorAll('.highlight');
highlightElements.forEach(function(item){
  item.style.backroundColor = "yellow";
  })

var headerFont = document.querySelector('h1');
headerFont.style.fontFamily = 'monospace';

var buttons = document.querySelectorAll('action-icon-bg');
buttons.forEach(function(button){
    button.style.backroundColor = "yellow";
})

var nameChange = document.querySelector('#name');
nameChange.placeholder = "Identify yourself";

var messageChange = document.querySelector('#message');
messageChange.placeholder = "State your business";

var nameValue = document.querySelector('#name');
nameValue.value = "Your nemesis";

var emailValue = document.querySelector('#email');
emailValue.value = "koalathebear@gmail.com";

var submitValue = document.querySelector('#submit');
submitValue.value = "En garde!";

var submitDisable = document.querySelector('#submit');
submitDisable.disabled = true;

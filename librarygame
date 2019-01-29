const taskData = [
  {
    name: 'F AUT',
    position: 0,
    required_position: 0
  },
  {
    name: 'F BAC',
    position: 1,
    required_position: 1
  },
  {
    name: 'F BES',
    position: 2,
    required_position: 2
  },
  {
    name: 'F CAN',
    position: 3,
    required_position: 3
  },
  {
    name: 'F ZET',
    position: 4,
    required_position: 4
  }
  
];

var arrayLength = taskData.length;
var temp;




for (i = 0; i < arrayLength; i++) {

  temp = document.createElement('div');
  temp.className = 'uk-card uk-card-default uk-margin uk-card-body';
   temp.innerHTML = "<h5 id=" + taskData[i].position + ">" + taskData[i].name + "</h5>";
  document.getElementById("test").appendChild(temp);

}

var correctAnswer = [0, 1, 2, 3, 4];
var answer;


var cA = correctAnswer.toString();


    // Create an empty array to store the ids and use map

document.getElementById("button").addEventListener('click',function ()
    {
		answer = $('h5').map(function () {
	return this.id;
}).get();

var A = answer.toString();

if(A===cA){modal.style.display = "block";}



})

// Get the modal
var modal = document.getElementById('myModal');

// Get the button that opens the modal
var btn = document.getElementById("myBtn");

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on the button, open the modal 
btn.onclick = function() {
  modal.style.display = "block";
}

// When the user clicks on <span> (x), close the modal
span.onclick = function() {
  modal.style.display = "none";
}

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}








		
		

	





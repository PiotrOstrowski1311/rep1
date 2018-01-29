# rep1

closure in JS

function makeTime (doneMessage, n) {

  setTimeout(function() {
    alert(doneMessage);
  }, n);
}

makeTime("Ready", 1000);

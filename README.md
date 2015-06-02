# swipe
swipe  jQuery plugin

usage

var options = {bounce : {
     flag : true , axis : 20 , time : 100, target : $("body") 
  }
};

//flag : bounce effect on/off , axis : bounce effect distance , time : bounce time , target : target jQuery Object

$(document).Swipe(function(e){
  console.log(e.currentTarget.component.direction);
  //+1 left swipe -1 right swipe
  }
} , options);

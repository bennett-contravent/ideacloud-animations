//IDEACLOUD ANIMATIONS
var dot1heading = null;
var dot1copy = null;
var dot1dot = null;
var dot1image = null;
var dot2heading = null;
var dot2copy = null;
var dot2dot = null;
var dot2image = null;
var dot3heading = null;
var dot3copy = null;
var dot3dot = null;
var dot3image = null;
var dot4heading = null;
var dot4copy = null;
var dot4dot = null;
var dot4image = null;
function hideAll() {
    dot1heading.style.display = 'none';
    dot1copy.style.display = 'none';
    dot1image.style.display = 'none';
    dot2heading.style.display = 'none';
    dot2copy.style.display = 'none';
    dot2image.style.display = 'none';
    dot3heading.style.display = 'none';
    dot3copy.style.display = 'none';
    dot3image.style.display = 'none';
    dot4heading.style.display = 'none';
    dot4copy.style.display = 'none';
    dot4image.style.display = 'none';
}
var animate_stop = false;
var time1 = null;
var time2 = null;
var time3 = null;
var time4 = null;
var current_animate = null;
var current_visible = null;
function hideT1(continue_next){
    if (continue_next){
    $('#pinktimer').css('width', '0px');
    $('#tdot1').css('transition','background-color .4s')
                            .css('background-color','transparent');
                
    $('#tdot1').children('.trigger-dot-text').css('transition','color .4s')
                    .css('color','#E11E8E');
    
    $('#imgPhone1').fadeOut(400, () => {
        $('#imgPhone1').css('left', '-4%');
    });
    $('#dot1heading, #dot1copy, #dot1image').fadeOut(400, () => {});
  }
}
function showT1(continue_next=true){
    console.log('showt1');
    $('#tdot1').css('transition','background-color .4s')
                    .css('background-color','#E11E8E');
            
    $('#tdot1').children('.trigger-dot-text').css('transition','color .4s')
                    .css('color','#FFFFFF');
        
    $('#imgPhone1').fadeIn(500).animate({
                            'left': '0%'
                            }, {duration: 500, queue: false, start: function() {
        setTimeout(()=>{
            console.log('showing image1');
            $('#dot1heading, #dot1copy, #dot1image').fadeIn(500);
        }, 200)
    }});
        
    //current_animate = $('#cvrSave');
    timerWidth = $('#pinktimer').parent().width()
        $('#pinktimer').animate({
        width: timerWidth + "px"
        }, 5000, () =>{
                     hideT1(continue_next);
        } );
    current_visible = hideT1;
    if (continue_next){
        time1 = setTimeout(runT2, 5500);
    }
}
function hideT2(continue_next){
  if (continue_next){
        $('#pinktimer').css('width', '0px');
    $('#tdot2').css('transition','background-color .4s')
      .css('background-color','transparent');
    $('#tdot2').children('.trigger-dot-text').css('transition','color .4s')
      .css('color','#E11E8E');
    $('#imgPhone2').fadeOut(400, () => {
        $('#imgPhone2').css('left', '-4%');
    });
    $('#dot2heading, #dot2copy, #dot2image').fadeOut(400);
  }
}
function showT2(continue_next=true){
        console.log('showt2');
    $('#tdot2').css('transition','background-color .4s')
                    .css('background-color','#E11E8E');
            
    $('#tdot2').children('.trigger-dot-text').css('transition','color .4s')
                    .css('color','#FFFFFF');
        
    $('#imgPhone2').fadeIn(500).animate({
                        'left': '0%'
                        }, {duration: 500, queue: false, start: function() {
        setTimeout(()=>{
            $('#dot2heading, #dot2copy, #dot2image').fadeIn(500);
        }, 200)
    }});
        
    //current_animate = $('#cvrSave');
    timerWidth = $('#pinktimer').parent().width()
        $('#pinktimer').animate({
        width: timerWidth + "px"
        }, 5000, () =>{
                     hideT2(continue_next);
        } );
    current_visible = hideT2;
    if (continue_next){
        time2 = setTimeout(runT3, 5500);
    }
}
function hideT3(continue_next){
  if (continue_next){
    $('#pinktimer').css('width', '0px');
    $('#tdot3').css('transition','background-color .4s')
      .css('background-color','transparent');
    $('#tdot3').children('.trigger-dot-text').css('transition','color .4s')
      .css('color','#E11E8E');
    $('#imgPhone3').fadeOut(400, () => {
        $('#imgPhone3').css('left', '-4%');
    });
    $('#dot3heading, #dot3copy, #dot3image').fadeOut(400);
  }
}
function showT3(continue_next=true){
        console.log('showt3');
    $('#tdot3').css('transition','background-color .4s')
                    .css('background-color','#E11E8E');
            
    $('#tdot3').children('.trigger-dot-text').css('transition','color .4s')
                    .css('color','#FFFFFF');
        
    $('#imgPhone3').fadeIn(500).animate({
                        'left': '0%'
                        }, {duration: 500, queue: false, start: function() {
        setTimeout(()=>{
            $('#dot3heading, #dot3copy, #dot3image').fadeIn(500);
        }, 200)
    }});
    //current_animate = $('#cvrSave');
    timerWidth = $('#pinktimer').parent().width()
        $('#pinktimer').animate({
        width: timerWidth + "px"
        }, 5000, () =>{
                     hideT3(continue_next);
        } );
    current_visible = hideT3;
    if (continue_next){
        time3 = setTimeout(runT4, 5500);
    }
}
function hideT4(continue_next){
  if (continue_next){
    $('#pinktimer').css('width', '0px');
    $('#tdot4').css('transition','background-color .4s')
      .css('background-color','transparent');
    $('#tdot4').children('.trigger-dot-text').css('transition','color .4s')
      .css('color','#E11E8E');
    $('#imgPhone4').fadeOut(400, () => {
        $('#imgPhone4').css('left', '-4%');
    });
    $('#dot4heading, #dot4copy, #dot4image').fadeOut(400);
  }
}
function showT4(continue_next=true){
        console.log('showt4');
    $('#tdot4').css('transition','background-color .4s')
                    .css('background-color','#E11E8E');
            
    $('#tdot4').children('.trigger-dot-text').css('transition','color .4s')
                    .css('color','#FFFFFF');
        
    $('#imgPhone4').fadeIn(500).animate({
                        'left': '0%'
                        }, {duration: 500, queue: false, start: function() {
        setTimeout(()=>{
            $('#dot4heading, #dot4copy, #dot4image').fadeIn(500);
        }, 200)
    }});
    //current_animate = $('#cvrSave');
    timerWidth = $('#pinktimer').parent().width()
        $('#pinktimer').animate({
        width: timerWidth + "px"
        }, 5000, () =>{
                     hideT4(continue_next);
        } );
    current_visible = hideT4;
    if (continue_next){
        time4 = setTimeout(runT1, 5500);
    }
}
function stop_timeouts(){
    if (time1) clearTimeout(time1);
    if (time2) clearTimeout(time2);
    if (time3) clearTimeout(time3);
    if (time4) clearTimeout(time4);
    $('#pinktimer').stop(false, true);
    //if (current_animate) current_animate.stop(false, true);
    if (current_visible) current_visible(true);
}
function runT1(continue_next=true){
    showT1(continue_next);
}
function runT2(continue_next=true){
    showT2(continue_next);
}
function runT3(continue_next=true){
    showT3(continue_next);
}
function runT4(continue_next=true){
    showT4(continue_next);
}
function runAnimations() {
    runT1(true);
}
window.addEventListener('load', (event) => {
    dot1heading = document.getElementById('dot1heading');
    dot1copy = document.getElementById('dot1copy');
    dot1image = document.getElementById('dot1image');
    dot1dot = document.getElementById('tdot1');
    dot2heading = document.getElementById('dot2heading');
    dot2copy = document.getElementById('dot2copy');
    dot2image = document.getElementById('dot2image');
    dot2dot = document.getElementById('tdot2');
    dot3heading = document.getElementById('dot3heading');
    dot3copy = document.getElementById('dot3copy');
    dot3image = document.getElementById('dot3image');
    dot3dot = document.getElementById('tdot3');
    dot4heading = document.getElementById('dot4heading');
    dot4copy = document.getElementById('dot4copy');
    dot4image = document.getElementById('dot4image');
    dot4dot = document.getElementById('tdot4');
    hideAll();
    //runAnimations();
    dot1dot.addEventListener('click', (event) => {
        stop_timeouts();
        //clearInterval(the_interval);
        //let other tab go away before showing this one on click
        setTimeout(()=>{runT1(false);}, 500);
    });
    dot2dot.addEventListener('click', (event) => {
        stop_timeouts();
        //clearInterval(the_interval);
        //let other tab go away before showing this one on click
        setTimeout(()=>{runT2(false);}, 500);
    });
    dot3dot.addEventListener('click', (event) => {
        stop_timeouts();
        //clearInterval(the_interval);
        //let other tab go away before showing this one on click
        setTimeout(()=>{runT3(false);}, 500);
    });
    dot4dot.addEventListener('click', (event) => {
        stop_timeouts();
        //clearInterval(the_interval);
        //let other tab go away before showing this one on click
        setTimeout(()=>{runT4(false);}, 500);
    });
});
var animation_started = false;
window.addEventListener('scroll', function() {
    var element = document.querySelector('#trigger-story');
    var position = element.getBoundingClientRect();
    // checking whether fully visible
    if(position.top >= 0 && position.bottom <= window.innerHeight) {
        //console.log('Element is fully visible in screen');
    }
    // checking for partial visibility
    if(position.top < (window.innerHeight-400) && position.bottom >= 0) {
        console.log('Element is partially visible in screen');
        console.log('top' + position.top);
        console.log('innerheight' + window.innerHeight);
        console.log('bottom' + position.bottom);
        if (animation_started == false){
            animation_started = true;
            runAnimations();
        }
    }
  
  var testdiv = document.querySelector('#testdiv');
  var testposition = testdiv.getBoundingClientRect();
  if(testposition.top >= 0 && testposition.bottom <= window.innerHeight) {
        //console.log('Element is fully visible in screen');
    }
  
});

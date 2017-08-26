# javascript-points

setTimeout(); context will always be global so it points to window object

$('a') === document.querySelector('a')

document.querySelectorAll('a');
document.querySelectorAll('a').length;
$$('a').length

right click preserve to keep logs even after refresh

document.body.contentEditable = true;//browser page will become editable

getEventListeners($('#myInput'))

monitorEvents($("#myInput));
monitorEvents($("#myInput),'click');
monitorEvents($("#myInput),['click','keyup','blur']);
unmonitorEvents($("#myInput));

console.time('myTime');
console.timeEnd('myTime');
Useful
console.time('myLoop');
for(var i=0; i<100000000;i++){
    1+2+3;
}
console.timeEnd('myLoop');
console.groupCollapsed('My Error');
for(var i=50;i--;){
    console.error(i);
}
console.groupEnd()
console.error();

console.table(myArray)
console.trace()

function foo(){
    console.count('fooed');
}
foo()
fooed:1
fooed:2

if({}) // true
if([]) // true
# calculator

## Basic Math Functions
function add(){};
function subtract(){};
function multiply(){};
function divide(){
    if infinity
    return "Cant divide by 0, bro!"
    clear firstnumber, secondnumber, and calloperator
};

After these function complete their calculations, call number.prototype.tofixed on them. Use 10.

## Keypad
All number and operator pads wiill have their related characters assigned to their custom data attributes
When pressed, pass the value of their custom data attributes to addnumber function and call it


## Displaying numbers on the display
var firstnumber = "";
var secondnumber = "";
var isOperatorPressed = false;

function displaytext(number){
    add number to span's textContent;
}

addNumber(number){
    if(firstNumber !== "" && callOperator){
        if(secondnumber === "")
            secondnumber = number;
        else{
            var stringNumber = number.toString();
            stringNumber = stringNumber + firstnumber.toString();
            firstnumber = Number.intParse(stringNumber);
        }
        displaytext(e)
    }
    else{
        if(firstNumber === "")
            firstnumber = number;
        else{
            var stringNumber = number.toString();
            stringNumber = stringNumber + firstnumber.toString();
            firstnumber = Number.intParse(stringNumber);
        }
        displaytext(e);
    }
}

---

## Add operator
When an operator button is pressed, assign function expression to callOperator

var callOperator = null;
var isOperatorPressed = false;

element.addEventListener('click', ()=>{
    //Check to see if callOperator is not null
    if(isOperatorPressed){
        call operate()
        isOperatorPressed = false;
    }
    callOperator = add;
    displayText(" + ");
})

---
# Operate

When "equal" button is pressed, call Operate functon with the paramaters firstnumber, secondnumber and calloperator

Check if secondnumber is null.
If null, do nothing

Operate(firstnumber, secondnumber, calloperator){
    if(isOperatorPressed){
        span.textContent = calloperator(firstnumber, secondNumber);
        firstnumber gets span.textContent and secondnumber become null;
        calloperator becomes null
    }
    else
        span.textContent = calloperator(firstnumber, secondNumber);
        firstnumber and secondnumber become null;
        calloperator becomes null
}

# clear
When you press the clear button, 
- assign "" to span.textContent
- reset firstnumber, secondnumber, isOperatorPressed, and callOperator

# Backspace
If calloperator is null and secondnumber are ''
var text = spa.textContent
numberstring = firstnumber.toString()
firstnumber = parseInt(numberstring.slice(0, numberstring.length - 1))
text = firstnumber.tostring()


Else If calloperator is true and secondnumber is ''
var text = spa.textContent
text = text.slice(0, text.length - 3) 
calloperator is null
isOperatorPressed is false

Else if secondnumber is not null
var text = spa.textContent
numberstring = secondnumber.toString()
secondnumber = parseInt(numberstring.slice(0, numberstring.length - 1))
text = secondnumber.tostring() 

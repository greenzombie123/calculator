# calculator

Basic Math Functions
- Add
- Subtract
- Multiply
- Devide

These functions are called when their corresponding buttons are pressed. Their related variables (var subtract, var add, etc) will be given a boolean value of true. 

Operate Function
- Called when either the equal sign is pressed or another number is included into the calculation. 

operate()


## 
var numberDisplay;

displayNumber(number){
    if(numberDisplay === '')
        numberDisplay = number;
    else{
        var stringNumber = number.toString();
        stringNumber = stringNumber + numberDisplay.toString();
        numberDisplay = Number.intParse(stringNumber);
    }
}

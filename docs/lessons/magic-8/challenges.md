# magic 8 challenges


## Challenge 4

```blocks
basic.showString("ASK A QUESTION")
basic.showNumber(8)
input.onGesture(Gesture.Shake, () => {
    basic.clearScreen()
    let randomNumber = randint(0, 7)
    if (randomNumber == 6) {
        basic.showString("OF Course, you will pass the test")
    } else if (randomNumber == 5) {
        basic.showString("No you won't pass the test")
    } else if (randomNumber == 4) {
        basic.showString("You will faily horribly")
    } else if (randomNumber == 3) {
        basic.showString("Try again next time")
    } else if (randomNumber == 2) {
        basic.showString("Im not sure")
    } else if (randomNumber == 1) {
        basic.showString("You will get a perfect score")
    } else {
        basic.showString("There's a chance you will pass")
    }
    basic.showNumber(8)
})
```


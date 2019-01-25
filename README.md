# Chapter-11-Exercises

Exercise 1:
Review the documentation of java.awt.Rectangle. Which methods are pure? Which are modifiers?

If you review the documentation of java.lang.String, you should see that there are no modifiers, because strings are immutable.

getBounds() - is not a pure function since there are so manty options to set as the bound, the input does not only determine the return value.
intersection(Rectangle r) - is a pure function since the return value (intersection) is determined from the imput "rectangle r"
union(Rectangle r) - is also a pure function since the reuturn value (union) is determined from the input "rectangle r"

Exercise 2:
The implementation of increment in this chapter is not very efficient. Can you rewrite it so it doesn’t use any loops? Hint: Remember the modulus operator.

public void increment(int seconds) {
    second += seconds;
    normalize();
}

 

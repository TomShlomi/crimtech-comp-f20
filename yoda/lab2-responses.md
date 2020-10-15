Yoda Chat: Responses
================

B. Inspect Mode
---------------
1: chocolate
2: next_week = "Guest talk?"
3: s3.amazonaws.com


C. Welcome to Programming in Javascript
---------------------------------------
3: y.includes("hello") tells whether y contains "hello" as a substring.
y.repeat(10) returns a string with y repeated 10 times.
4: square(2.5) returns 6.25
square("hello") returns NaN
5: function square(i) {
    if (typeof(i) != "number") {
        return(-1);
    }
    return i*i;
}
6: function numberString(i) {
    ret = "";
    if (typeof(i) == "number" && i > 0) {
        for (j = 1; j <= i; j++) {
            ret = ret + j;
        }
    }
    return ret;
}
1. prices.length is printed out
2. prices[prices.length-1]*(1-discount) is printed out
3. finalPrice does print whatever the rounded value of discountedprice is
4. The array that will be returned is one where all the elements are half the originaln array as the 1 - 0.5 = 0.5 and the 100s in the numerator and denominator cancel out. Answer: [50 100 150]
5. line 11 will cause an error to be thrown because i is not defined outside of the for loop because of let
6. it will also throw an error as the variable is only defined within the for loop and not anywhere outside it
7. the finalPrice will be printed with the final value as it is decalred first outside of the for loop and it is solely updated within the loop
8. The array that will be returned is one where all the elements are half the originaln array as the 1 - 0.5 = 0.5 and the 100s in the numerator and denominator cancel out. Answer: [50 100 150]
9. This will output an error because i is defined by let, meaning that it is block scope
10. will output an error because const variables cannot be changed 
11. This will also output an erro as const will not allow it to change
12. This will be an empty array as the elements of this array are dependent on const variables and as those cannot be changed, they will not be assigned a value and not give the array elements.  Ultimately, nothing will be returned because it cannot even get to that point of the codee because of the error.
13. a) student.name b)student['Grad Year'] c)student.init() d)student['Favorite Teacher],name e) student.courseLoad[0];
14.  a) 32, 2 is converted to a string b) 1, 3 is changed into an int c)3, null is treated as 0 d)3null, they are both treated as strings e)4, true is treated as a 1 f) 0, false and null are treated as 0 g)3undefined, undefined and 3 are treated as strings h)NaN, cant do any operations as undefined does not have an int value and you cant subtract strings
15.  a) true, 2 is converted to an int b) false, they compare characters position by position and 2 comes after 1 in the lexicogrpahical ordering c)true, '2' becomes an int, not strict equality taht checks for type d) false, strict equality that checks for type and doesnt do type conversions implicitly e)false, true is given the value 1  f)true, boolean(2) is inherently 'true' as it is not 0 or null.
16.  '==' is not strict in the sense that it doesnt check the type so if we are comparing the string 2 and the int 2, it will return true.  However, '===' does check for what type and does not do an implicit type conversion so thee above example will return false
17.  Hello! gets printed as 2 is 'true' in the sense that it is not one of thee empty values.  Since this conditional block is in the form of if, else if, and else, once one condition is met, thee others wont be checked for.
19. 
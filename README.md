
# E02a-Control-Structures
main01: I expect the program to say greetings and ask its favorite color. The program operated exactly as my exprectation.
main02: The difference is that the program will repeat the color I inputed with the line of "color=input()". The program operated exactly as my exprectation.
main03: The difference is that this time the program has a correct answer and will give out different responses, but no whole game loop. The new response feature are the lines 9-12, line 10 and 12 are indented because they fall under the if loop. The program doesn't see "red" as correct. This tells me that "color" must be exact to be considered correct.
main04: The difference is that now "red" is also correct. This is an attempt to achieve the correct answer ignoring the capitalization issues. Yet other types of capitalization are still not recognized.
main05: I expect line 9 to fix the capitalization issue completely, but when I add spaces, it fails to recognize once again.
main06: Now line 9 added .strip() to fix the space issues. Thus the problem is completely fixed, no other types of "red" would trigger the wrong answer.
main07: I expect this time the program is trying to give players some hints. And line 12 is the hint.
main08: Line 9 sets a while loop so now players can guess until the correct answer is present. Lines 10-17 are indented because they are a part of the while loop. If line 9 and 10 flipped, then if red, no further operations are possible, if not, the program would repeat the result by itself nonstop.
main09: Line 13 is counting the number of tries that the player attempted, the count is the feature of attempts. There is no line 22~
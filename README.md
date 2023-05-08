Download Link: https://assignmentchef.com/product/solved-solvedlab-06
<br>
Objective:The objective of this lab is to get you some experience in processing strings character by character and in implementing stacks and queues in a class package.

The programming assignment:

In your lab05, replace instructor’s Tokenizer class and MyStackQueue package with your own.

Requirements:1. You must use a linked list to implement your queue.2. You must use an array to implement your stack.3. You must use the following frame work to implement your tokenizer.class Tokenizer {private char [] Buf;private int cur;Tokenizer(String infixExpression) {Buf = infixExpression.toCharArray();cur = 0;}boolean moreTokens() {Skip blanks.return cur&lt;Buf.length;}Token nextToken() {1. Skip blanks.2. if (cur=Buf.length) return null;3. If the next character is a digit, keep reading until a non-digit is read.Convert the string of digits into an integer.String Digits = new String(Buf, start, len);int num = Integer.valueOf(Digits).intValue();Use num to create and return an operand.4. Otherwise, use the next character to create and return an operator.}
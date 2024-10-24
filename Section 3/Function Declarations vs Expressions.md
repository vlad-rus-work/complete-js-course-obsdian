function functionDeclaration(param1, param2) {
	block of code;
	return;
}

const functionExpression = (param1, param2) {
	block of code;
	return;
}

The key difference is that we can call a declared function <mark style="background: #650BB3;">BEFORE</mark> it is defined in the code.
This happens because of hoisting.
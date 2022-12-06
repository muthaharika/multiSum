function multiSum(num,ten=10) {
	let sum = 0;
	for (let i = 1; i <= ten; i++) {
		sum = sum + (num*i);
	}
	return sum;
}
console.log(multiSum(6));

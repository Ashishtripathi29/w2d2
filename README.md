// 1. Print all even numbers in first 50 natural numbers
	// HINT: google how to determine if a number is even or not

	for(var i=0;i<=50;i++){
		if(i%2===0){
			console.log(i);
		}
	}
	// 2. print all odd numbers in natural numbers from 20 to 50
		// HINT: google how to determine if a number is odd or not
	console.log("odd number");
	for (let i = 20; i < 50; i++) {
	if(i%2!==0){
		console.log(i);
	}    
	}
	
	// 3. print all numbers that are divisible by 5
	// 	[12, 45, 67, 89, 90, 34, 35, 55]
		// HINT: google how to check divisibility by a number
	console.log("problem 3  ")
	var arr=[12, 45, 67, 89, 90, 34, 35, 55]
	for (let i = 0; i < arr.length; i++) {
		if(arr[i]%5==0){
			console.log(arr[i]);
		}
	}
	
	// 4. Print all numbers of this array
	// 	 [[1,2], [3,4], [5,6], [7,8]]
		// HINT: use nested loops
	
	console.log("problem 4");
	var arr2=[[1,2], [3,4], [5,6], [7,8]]
	for (var i = 0; i < arr2.length; i++) {
		for (var j = 0; j < arr2[i].length; j++) {
			console.log(arr2[i][j])
		}
	}
		
	// 5. Print all prime numbers occurring in 1st 50 natural numbers
		// HINT1: google how to check if a number is prime or not
		// HINT2: use nested loops
	console.log("problem 5")
	for (let i = 1; i < 50; i++) {
		var k=true
		for (let j = 2; j <= i/2;j++){
			if(i%j==0){
				k=false;
			}
		}
		if(k){
			console.log(i);
		}
	}

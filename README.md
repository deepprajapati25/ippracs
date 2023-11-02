## Promises
let promise = new Promise(function (resolve, reject) { <br/>
	const x = "geeksforgeeks";<br/>
	const y = "geeksforgeeks"<br/>
	if (x === y) {<br/>
		resolve();<br/>
	} else {<br/>
		reject();<br/>
	}<br/>
});<br/>

promise.<br/>
	then(function () {<br/>
		console.log('Success, You are a GEEK');<br/>
	}).<br/>
	catch(function () {<br/>
		console.log('Some error has occurred');<br/>
	});<br/>

- š Hi, Iām @gassansa
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
gassansa/gassansa is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
/*
1) Open https://popcat.click
2) Open console (F12)
3) Insert code & run
*/


var event = new KeyboardEvent('keydown', {
	key: 'g',
	ctrlKey: true
});

setInterval(function(){
	for (i = 0; i < 100; i++) {
		document.dispatchEvent(event);
	}
}, 0);

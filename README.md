bala.DualSelectList
============

bala.DualSelectList is a jQuery plugin to provid multiple-select function through 2 List-Boxes.

How to use:

1. Create DualSelectList with candidate items

var dsl = $('#dualSelectExample').DualSelectList({
	'candidiateItems' : ['Item 01', 'Item 02', 'Item 03', 'Item 04', 'Item 05']
});

2. Set candidate items after DualSelectList created

var dsl = $('#dualSelectExample').DualSelectList();
dsl.setCandidate(['Item 01', 'Item 02', 'Item 03', 'Item 04', 'Item 05']);

3. Get select result

var res = dsl.getSelection();


* The jQuery Plugin Registry is now in read-only mode.
https://plugins.jquery.com/
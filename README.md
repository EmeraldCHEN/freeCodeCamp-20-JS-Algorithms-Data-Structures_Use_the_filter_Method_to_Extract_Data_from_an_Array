One useful array function is Array.prototype.filter(), or simply filter(). The filter method returns a new array which is at most as long as the original array, but usually has fewer items.

Filter doesn't alter the original array, just like map. It takes a callback function that applies the logic inside the callback on each element of the array. If an element returns true based on the criteria in the callback function, then it is included in the new array.


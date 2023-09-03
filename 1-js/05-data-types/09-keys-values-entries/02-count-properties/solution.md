let count = function(obj) {
// convert the object to an array then return the obj.length 
  obj = Object.entries(obj);
  return obj.length;
}

count({
  name: 'Ahmed',
  age: 20,
}) // returns 2 

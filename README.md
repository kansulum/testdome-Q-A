# testdome-Q-A
A repository for asp.net testdome questions and answers

Question 1
Implement the removeProperty function which takes an object and property name, and does the following:

If the object obj has a property prop, the function removes the property from the object and returns true; in all other cases it returns false.

Starting code:

function removeProperty(obj, prop) {
  return null;
}
Solution 1
function removeProperty(obj, prop) {
if(prop in obj) {
  delete obj[prop];
  return true;
  } else {
  return false;
 }
}

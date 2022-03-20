Describe: ccNumberCheck()

Test: "It will take a number, and return the number doubled."
Code: numDoubler(2);
Expected Output: 4;

Test: "It will take a two digit number, and turn it into a string."
Code: numExtractor(25);
Expected Output: "25";

Test: "It will take a two digit number, and set aside in a variable the ones -- right most -- digit as a number."
Code: numExtractor(25);
Expected Output: 5;

Test: "It will take a four digit number -- ex. 1234, and set aside the target numbers replaced by x & y -- 1y3x in two separate variables."
Code: numExtractor(1234);
Expected Output: console logged --> y is 2 and x is 4.;

Test: "It will take a five digit number -- ex. 12345, and set aside the target numbers replaced by x & y -- 12y4x in two separate variables."
Code: numExtractor(12345);
Expected Output: console logged --> y is 3 and x is 5.;

Test: "It will take a six digit number -- ex. 123456, and set aside the target numbers replaced by x & y -- 123y5x in two separate variables."
Code: numExtractor(123456);
Expected Output: console logged --> y is 4 and x is 6.;

Test: "It will take a six digit number -- ex. 123456, and set aside the numbers specified in previous test as elements of an array."
Code: numExtractor(123456);
Expected Output: console logged --> numArray = [6, 4];

Test: "It will take a six digit number -- ex. 123456, and using a loop, set aside the numbers specified in previous test as elements of an array."
Code: numExtractor(123456);
Expected Output: console logged --> numArray = [6, 4];

Test: "It will take a sixteen digit number -- ex. 1234567890123456, and set aside the numbers specified in previous test as elements of an array."
Code: numExtractor(1234567890123456);
Expected Output: console logged --> numArray = [6, 4, 2, 0, 8, 6, 4, 2];

Test: "It will take a fifteen digit number -- ex. 123456789012345, and set aside the numbers specified in previous test as elements of an array."
Code: numExtractor(123456789012345);
Expected Output: console logged --> numArray = [5, 3, 1, 9, 7, 5, 3, 1];

Test: "It will take a number -- ex: 5, place it in an array, and then return it in a different array with twice its value."
Code: numExtractor(5);
Expected Output: 10;

Test: "It will take all elements of the numbers array and use array mapping to multiply the values by two and put them in a different array."
Code: numExtractor(123456789012345);
---> Goes in map [5, 3, 1, 9, 7, 5, 3, 1]
Expected Output: [10, 6, 2, 18, 14, 10, 6, 2];

Test: "It will take a number, check if it's value is 10 or greater. If yes, it will return true. If not, it will return false.
Code: numCheck(10);
Expected Output: True;

Test: "It will take a number. If value is 10 or greater, it will separate the two digits into separate numbers, and place into an array, and return it. If not, it will return the number as is."
Code: numCheck(12);
Expected Output: [1, 2];

Test: "It will take numbers in an array, check to see if the values are 10 or greater, then add the individual digits together."
Code: numCheck(array); --> [5, 12];
Expected Output: [5, 3];

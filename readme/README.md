Describe: wordCounter()

Test: "It should return 1 if a passage has just one word."
Code:
const text = "hello";
wordCounter(text);
Expected Output: 1

Test: "It should return 2 if a passage has two words."
Code:
const text = "hello there";
wordCounter(text);
Expected Output: 2

Test: "It should return 0 for an empty string."
Code: wordCounter("");
Expected Output: 0

Test: "It should not count numbers as words."
Code: wordCounter("hi there 77 19");
Expected Output: 2

Describe: numberOfOccurrencesInText()

Test: "It should return 0 occurrences of a word for an empty string."
Code:
const text = "";
const word = "red";
numberOfOccurrencesInText(word, text);
Expected Output: 0

Describe: getTopThreeWords()

Test: "Should return 0 for an empty string"
Code: 
const text = "";
getTopThreeWords(text);
Expected output: 0

Test: "Should take the text and convert it in array compare elements to text"
Code:
const text = "";
getTopThreeWord(text);
Expexted output: add 1 to word counter

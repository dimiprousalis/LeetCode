// A phrase is a palindrome if, after converting all uppercase letters into lowercase letters and removing all non-alphanumeric characters, it reads the same forward and backward. Alphanumeric characters include letters and numbers.

// Given a string s, return true if it is a palindrome, or false otherwise.



// Example 1:

// Input: s = "A man, a plan, a canal: Panama"
// Output: true
// Explanation: "amanaplanacanalpanama" is a palindrome.
// Example 2:

// Input: s = "race a car"
// Output: false
// Explanation: "raceacar" is not a palindrome.
// Example 3:

// Input: s = " "
// Output: true
// Explanation: s is an empty string "" after removing non-alphanumeric characters.
// Since an empty string reads the same forward and backward, it is a palindrome.


// Constraints:

// 1 <= s.length <= 2 * 105
// s consists only of printable ASCII characters.



//Solution
/**
 * @param {string} s
 * @return {boolean}
 */
var isPalindrome = function (s) {
    s = s.toLowerCase()
    let s1 = s.split('').filter((e, i) => s.charCodeAt(i) >= 97 && s.charCodeAt(i) <= 122 || s.charCodeAt(i) >= 48 && s.charCodeAt(i) <= 57)

    for (let i = 0; i < s1.length; i++) {
        if (s1[i] !== s1[s1.length - i - 1]) {
            return false
        }
    }
    return true
};
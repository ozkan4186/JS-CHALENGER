# JS-CHALENGER
1.// ! Write a function which calculates the average of the numbers in a given list.

! Note: Empty arrays should return 0.

image

2.//! An isogram is a word that has no repeating letters, consecutive or non-consecutive. Implement a function that determines whether a string that contains only letters is an isogram. Assume the empty string is an isogram. Ignore letter case.

image

3.//! Implement the function unique_in_order which takes as argument a sequence and returns a list of items without //! any elements with the same value next to each other and preserving the original order of elements.

image

4.// !! Deoxyribonucleic acid (DNA) is a chemical found in the nucleus of cells and carries the "instructions" for the development and functioning of living organisms.

// !!If you want to know more: http://en.wikipedia.org/wiki/DNA

//!! In DNA strings, symbols "A" and "T" are complements of each other, as "C" and "G". Your function receives one side of the DNA (string, except for Haskell); you need to return the other complementary side. DNA strand is never empty or there is no DNA at all (again, except for Haskell).

// !!More similar exercise are found here: http://rosalind.info/problems/list-view/ (source)

//!! Example: (input --> output)

//!! "ATTGC" --> "TAACG"

image

//#Find the missing letter
Write a method that takes an array of consecutive (increasing) letters as input and that returns the missing letter in the array.
function solution(number) {
    let arr = 0
    for (i = 0; i < number; i += 3) {
        arr += i
    }
    for (i = 0; i < number; i += 5) {
        arr += i;
    }
    for (i = 0; i < number; i += 15) {
        arr -= i;
        i
    }
    return arr
}
console.log(solution(27));


You will always get an valid array. And it will be always exactly one letter be missing. The length of the array will always be at least 2. The array will always contain letters in only one case.

Example:

['a','b','c','d','f'] -> 'e' ['O','Q','R','S'] -> 'P'

image

function feast(beast, dish) {

    if (a[0] == b[0] && a[a.length - 1] == b[b.length - 1]) {
        return 'true';


    } else {
        return 'false';
    }

}

console.log(feast("creat 5 herok", "carlic naak"))
# code wars 7.kata ouestions
Complete the function that accepts a string parameter, and reverses each word in the string. All spaces in the string should be retained.

Examples
"This is an example!" ==> "sihT si na !elpmaxe"
"double  spaces"      ==> "elbuod  secaps"![Ekran görüntüsü 2022-09-29 182036](https://user-images.githubusercontent.com/109352349/193072921-0a666eb7-bc63-40f1-975f-65d46777a64b.png)




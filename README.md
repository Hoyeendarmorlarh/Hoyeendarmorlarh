// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract EvenOddChecker {
    function isEven(uint256 number) public pure returns (bool) {
        // A number is even if it's divisible by 2 without a remainder.
        // The modulo operator (%) calculates the remainder of a division.
        // If the remainder is 0, the number is even.
        return number % 2 == 0;
    }
}


<!---
Hoyeendarmorlarh/Hoyeendarmorlarh is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

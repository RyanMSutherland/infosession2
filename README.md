# README

You are given a List of Integers, listInt, and another integer n. We will define closure under addition for listInt to mean that for two distinct values of i and j, (listInt[i]+listInt[j]) % n is in listInt or k * n + (listInt[i]+listInt[j]) % n (for some int k) is in listInt.

Your goal is to determine if a given List of Integers is closed under addition for some modulus n. You will implement a method, isClosed, that will return true if a List is closed under addition for a given n and false otherwise.

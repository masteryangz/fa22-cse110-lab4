1. the variable i is incremented to 3 and is printed to the console
2. the variable discountedPrice, which is the last element in prices, 300, times (1 - discount) = 150, is printed
3. in the last iteration of the for loop, discountedPrice is 150, and Math.round(150 * 100) / 100 is 15000 / 100 which is 150, so 150 is printed
4. the function returns [50, 100, 150], because each element of prices is updated by multiplying 0.5 and since line 8 does not change the elements, the discounted, which is the updated prices is returned
5. error, because i is out of scope and is not reassigned a value
6. error, because discountedPrices is out of scope and is not reassigned a value
7. print 150 because finalPrice is updated as the elements of prices * 0.5 for each iteration and 150 is the last iteration, so 150 is printed
8. the function will return [50, 100, 150] because discounted is the updated list of prices multiplying 0.5
9. error, because i is out of scope and is not reassigned a value
10. print 3, because length is assigned as the length of prices, which is 3
11. the function will return [50, 100, 150] because discounted is the updated list of prices multiplying 0.5
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. '32' 2 is converted to '2' and '3' + '2' = '32'
    B. 1 '3' is converted to 3 and 3 - 2 = 1
    C. 3 null is converted to 0 and 3 + 0 = 3
    D. '3null' null is converted to 'null' and '3' + 'null' = '3null'
    E. 4 true is converted to 1 and 1 + 3 = 4
    F. 0 false is converted to 0 and null is converted to 0 and 0 + 0 = 0
    G. '3undefined' undefined is converted to 'undefined' and '3' + 'undefined' = '3undefined'
    H. NaN both '3' and undefined can not be converted into the same type for -
14. A. true '2' is converted to 2 and 2>1 is true
    B. false '2' will compare with '1' first and '2'<'1' is false
    C. true since '2' and '2' are the same
    D. true since '2' and '2' are the same and have the same type
    E. false since true can be converted to 1 but 1 != 2
    F. true since true and Boolean(2) are both Boolean type and Boolean(2) is true
15. == only accounts for the values of two sides, while === accounts for the values and the types of two sides
16. part2-question16.js
17. [2, 4, 6] the newArr is calling doSomething each iteration with each element of array, and doSomething will multiply each element of array by 2, so the result is [2, 4, 6]
18. part2-question18.js
19. 1
    4
    3
    2
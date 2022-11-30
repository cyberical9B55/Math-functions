# Math-functions
Extra math functions for roblox (easy to learn+use)

How to use: just add the loadstring at the top of your script!
loadstring:
  loadstring(game:HttpGet("https://raw.githubusercontent.com/cyberical9B55/Math-functions/main/Functions"))()

tutorial:

IsEven/Even:
  return true/false depending on if the number you input is even or not
  example:
    print(IsEven(5)) -- this would return false
    

IsOdd/Odd:
  return true/false depending on if the number you input is odd or not
  example:
    print(IsOdd(5)) -- this would return true


IsPrime/Prime:
  return true/false depending on if the number is prime of not
  example:
    print(IsPrime(7)) -- would return true since 7 is prime
    
    
    
FormatNumber/Format:
  returns a nicely formatted number that you input
  example:
    print(FormatNumber(100000)) -- this would return "100,000)
    
ToClosest/RoundIn:
  returns a number set your input number is closest to
  example:
    local set = 100 -- can be anything im just using 100s for example
    local num = 69 -- haha funny but can be any number
    print(ToClosest(set, num)) -- would return 100 as 100 is the closest set of 100 to 69
    
    local num = 690 -- haha funny but can be any number
    print(ToClosest(set, num)) -- would return 690 as 690 is the closest 100 of 700 to 690
    
    
FindEvensFromTable/FindEvens:
  returns a table with all the even numbers from a past table
  example:
    local mytab = {1, 2, 3, 4, 5, 6, 7, 8}
    print(FindEvensFromTable(mytab)) -- would return 2,4,6,8
    
    
RemoveEvensFromTable/RemoveEvens:
  returns a table with no even numbers from a past table
  example:
    local mytab = {1, 2, 3, 4, 5, 6, 7, 8}
    print(RemoveEvensFromTable(mytab)) -- would return 1, 3, 5, 7
    
    
 
    
FindOddsFromTable/FindOdds:
  returns a table with all the Odd numbers from a past table
  example:
    local mytab = {1, 2, 3, 4, 5, 6, 7, 8}
    print(FindOddsFromTable(mytab)) -- would return 1, 3, 5, 7
    
    
RemoveOddsFromTable/RemoveOdds:
  returns a table with no Odd numbers from a past table
  example:
    local mytab = {1, 2, 3, 4, 5, 6, 7, 8}
    print(RemoveOddsFromTable(mytab)) -- would return 2, 4, 6, 8
    
    
IsClosestTo:
  returns a number which is the closest to a set of numbers in a table
  example:
    local mytab = {1, 5, 10}
    local mynum = 6
    print(IsClosestTo(mytab, mynum)) -- would print 5 since 6 is closest to 5
    

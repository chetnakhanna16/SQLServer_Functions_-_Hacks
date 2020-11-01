# SQLServer Functions and Hacks

<B>1. ASCII</B> - ASCII value of just the first character

<B>2. CHAR</B> - Character corresponding to the ASCII value

<B>3. CHARINDEX</B> - Index of the start of a substring in a string (Search start index can also be given to start searching from a specific position)

<B>4. ‘+’</B> - Concat using + adds 2 strings together (Most basic - You have to even give the space explicitly if you need space in between strings)

<B>5. CONCAT</B> - Add 2 strings together

<B>6. CONCAT_WS</B> - Add 2 strings together with a separator 

   Difference between CONCAT and CONCAT_WS: 
   ~ Can use different separators in CONCAT to get output in the way you want as separator is itself considered as a string
   ~ Can use a single separator in CONCAT_WS to get the strings separated by that separator as separator is a parameter here 
   ~ Can use more than one separator in CONCAT_WS by setting the first input string as empty
     Example: CONCAT_WS('', LastName, ', ', FirstName, ' (', MiddleName, ')' ) to return LastName, FirstName (MiddleName)
   
<B>7. PERCENTILE_DISC</B> - https://docs.microsoft.com/en-us/sql/t-sql/functions/percentile-disc-transact-sql?view=sql-server-ver15

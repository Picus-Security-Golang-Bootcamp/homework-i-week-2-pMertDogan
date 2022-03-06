## Homework | Week 2

You can query our small book liblary!

Checkut avaiable commands! You can find them on below.

Note: Commands are not case sensite! You can use seArch booKName , searcH BOOK name, LiSt..

### list command
```
go run main.go list
```

'list' command just get all of the books. No limiation or filter applied to this query. Command like 'list xxx xxx' are same as 'list'.


### search command 
  
  Example commands by line
  
```
go run main.go search <bookName>
go run main.go search Lord of the Ring: The Return of 
```
  
  You can use seArch <booKName> , searcH <BOOKname>,
  bookname should be include all letters. If you are searching for 'hobbit' you can type 'search hobbit' or 'search HoBbiT' . If you type 'search hob' its not return hobbit !
  
  
_____
  
 EXAMPLE results
  ```
  PS C:\Projeler\homework-i-week-2-pMertDogan\week-2> go run .\main.go list       
Hobbit
World War Z
Kolpaçino
Ayla
Lord of the Ring: The Return of the King
PS C:\Projeler\homework-i-week-2-pMertDogan\week-2> go run .\main.go search hoBBit
hoBBit is available
PS C:\Projeler\homework-i-week-2-pMertDogan\week-2> go run .\main.go search hoBBi 
The book 'hoBBi' is not available. You can get all book name with 'list' command
PS C:\Projeler\homework-i-week-2-pMertDogan\week-2> go run .\main.go search World war z
World war z is available
PS C:\Projeler\homework-i-week-2-pMertDogan\week-2> go run .\main.go search World w a r z
The book 'World w a r z' is not available. You can get all book name with 'list' command
PS C:\Projeler\homework-i-week-2-pMertDogan\week-2> go run .\main.go list this text are not hanled
Hobbit
World War Z
Kolpaçino
Ayla
Lord of the Ring: The Return of the King
  
  ```


# tema-2-poo-template


I create a program which receive some commands and make specific actions. I consider good to know about this program
this thinks:

  - created in ManagementPrimarie some static arguments like: users(HashMap) and all offices(generics objects),
  because I needed to access them easily from whole program
  - use static method in ManagementPrimarie like: read, print, println, because I needed to read and print files from
  whole program
  - had to create resetArguments method, because when I ran repeatedly all the tests, without deleted all output files,
  they didn't work expected
  - data structures which saved every user and office clerk are HashMap, because in each command I had to find them
  using the name. In this HashMap the key is name field and the second objects is a specific reference by main object
  like: User or OfficeClerk
  - For saved each request I used TreeSet and sorted them by specific rules. User class sorted requests with
  timeComparator class, which only looked at the date, and Office class sorted requests with priorityComparator, which
  looked first at request's priority and then request's date

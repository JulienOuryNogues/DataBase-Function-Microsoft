# DataBase-Function-Microsoft

This database contains part of the fuctions found on Microsoft's site. 

https://msdn.microsoft.com/en-us/default.aspx

there are two tabs in this DB : 

FunDLL, in which you can find the name of the function, his RVA, his Ordinal and his OS ! All these informations are extracted from the DLL

FunDoc, in which we can find all the information foudn in Microsoft's site (description, profile, retrunr and parameter's value) 

If you want to make a "join" between these two tabs, you have to match on the name. Pay attention to the demangling test, and some function could be foudn in several DLL... 


In the database "CategoriesExample", we can find some examples for our classification with all the data possible ! without TFIDF and with k=200 and k=1600 

You only have the name and the number (arbitrary) of the category. If you want more information about the functions , please use the other database. 
# pandas 
* in pandas object means string 

## pandas function 
* Series 


## Series method 
* head  -> get the data from head of the column, depending on how many data featch for example head(5) means 5 column of data are fetch 
* tail -> get the data from last of the column
* sample -> get the random data in dataSeries 
* value_counts -> which acter are how many movie || calculate the count of data  
* sort_values -> how to calculate max runs of virt kohli 
* sort_index   -> if you sort the alphabetical character than use to sort_index not used in number 
* count() -> count is function, count function is not count to Nan value but size method are count 
### mathmatical method 
* size -> size is method 
* mean 
* median
* mode 
* std 
* var 
* min
* max   
* describe  -> give the all paramer like [count, mean, std, etc....]




## pandas attribute 
* size -> how many itams found 
* dtype
* name   -> name of data 
* is_unique 
* index -> index of data 
* values -> value of data 

### series indexing 
### Editing Data 
### Series with python Functionality 
* membership operator 
* loop 
* Arthmatic operator 
* Boolean Indexing in series 
* Ploting graph on series 


### Some Important Series Method 
* astype   -> type of data for example: int64, float32 etc...
* between
* clip      -> give the range 
* drop_duplicates  -> drop the duplicate item in list 
* isnull
* dropna    -> drop the null value 
* fillna    -> fill null value 
* isin        -> ex- 49 is found the data or not 
* apply
* copy



## DataFrame 

### Method 
* head
* tail 
* sample -> get the random data 
* info  -> get the summary of the data 
* describe  -> describe the data 
* isnull     -> true means null value are found 
* duplicate -> copy of the rows 
* rename  -> rename the column of data 
* astype
* value_count



### Attribute 
* shape 
* dtype 
* index    -> fetch the row
* columns   -> fetch the column
* values     -> get the values of data in 2D
* iloc   -> fetch row 
* loc    -> index data give 
* contains



### Most Important Function 
* value_counts    -> count the values 
* sort_values      -> arrange the item in ascending/descending order 
* rank           -> arrange the order in rank wise 
* sort index      -> arrange the index ascending/descending order
* set index       -> set the index 
* rename index -> rename
* reset index     -> reset the data index 
* unique & nunique    -> nunique means no of unique item 
* isnull/notnull/hasnans 
    * hasnans ->  ye ek row me nan value batata hai boolean me
* dropna    -> drop the null value
* fillna    -> fill the null value
* drop_duplicates   -> drop the duplicates value of data 
* drop            -> drop the value using indexing
* apply     -> apply is method which is customise the function in data 
* isin      -> column are is in data or not give the True False 
* corr      ->  correlation of column in data 
* nlargest -> nsmallest  
* insert   -> insert the row | col in data 
* copy     -> copy the whole data 



### Groupy BY Objects 
* groupby  -> this method are grouped by two item 
- what is mean ? 
* average column value 

### GroupBy Attributes and Methods 
* find total number of groups -> len
* find items in each group -> size 
* first()/last() -> nth item    
* get_group -> vs filtering 
* groups 
* describe 
* sample 
* nunique


## groupby_objects
## Merging, Joining & Concatenating
* merging 
how to use merge 
![alt text](<Screenshot 2024-03-25 202242.png>)

students.merge(regs,how='inner',on='student_id')
students.merge(regs,how='left',on='student_id')
inner -> join the common side of data 
left -> join the data but left side are first priority 


## MultiINdexing Series 
what is the uses of multiIndexing b/c if your data is more then 2D this is MultiIndexing, you should convert 2D, 1D Data 
* Stack -> column ko index bana deta hai 
* unstack -> index ko column bana deta hai

## ## Long Vs WIde Data 

### Long Vs Wide Data

**Wide format** is where we have a single row for every data point with multiple columns to hold the values of various attributes.

**Long format** is where, for each data point we have as many rows as the number of attributes and each row contains the value of a particular attribute for a given data point.

* google colab link: https://colab.research.google.com/drive/17l8EddlrS2Ed35frmeS6cHAvdf5Fbw-g?usp=sharing#scrollTo=-oQZntArcOKD





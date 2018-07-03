# pupg_cloud


url on https://jtoump.github.io/pupg_cloud/testpubg/here/pubg_test.html


### rs.iris_researchers(keyword,onlyiriscodes=False)




#### Parameters:
**keyword**: _str_

    keyword to search in the iris database,e.g('housing', 'urban planning')
    
**onlyiriscodes**: _boolean_
    
    Return the list of the iris alias of the relevant authors based on the input keyword. Will default on false returning
    the abstracts
    
#### Return:

**authorlist**: _list_

    Returned if onlyriscodes=True. List of the identified authors.
    
If _onlyriscodes=False_ see __fetch_publications()__
    
    
    
#### Examples: 

```python
abstracts,dataframe = rs.iris_researchers(keyword,onlyiriscodes=False)
```

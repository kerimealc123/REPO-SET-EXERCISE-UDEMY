# REPO-SET-EXERCISE-UDEMY
//make list with string variable
List<String> name=new List<StrinG>{'kerime'};
System.debug(name);
System.debug(name.contains('kerime'));


// make set with integer variable
Set<INteger> rollNUmbers=new Set<INteger> {2222,2222,444,33322};
System.debug(rollNumbers);

// add item
rollNUmbers.add(333224);
rollNumbers.add(1234);
System.debug(rollNumbers);

// add duplicate item not allowed
rollNUmbers.add(444);
System.debug(rollNUmbers);

// check set have an item with -CONTAINS METHOD-
System.debug(rollNumbers.contains(444));

// delete an item -REMOVE METHOD- (different from list we address the value)
rollNumbers.remove(444);
System.debug(rollNUmbers);


// get set size -SIZE METHOD-
System.debug(rollNUmbers.size());

//check set is empty or not -ISEMPTY METHOD-
System.debug(rollNumbers.isempty());

//clear set -CLEAR METHOD-
rollNumbers.clear();
System.debug(rollNUmbers);
System.debug(rollNUmbers.isempty());

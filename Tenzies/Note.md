# .map() 
>>> whenever we use,
    .map() method on array, 
don't forget to add key property to get rid of error.
i.e.   key : {singleDie.id}

_____________________________________________________________________________________________________________________

# Components
>>> Never forget the usage of components, to use same comp's multiple times(along with .map() method).

_____________________________________________________________________________________________________________________
# .useEffect()

>>> keeping 2 internal pieces of states "IN-SYNC" with each other,is really a common reason to use useEffect() for...
>>> not only, when it is concerned with outside the comp-function entirely.

_____________________________________________________________________________________________________________________
# .every()

>>> 



_____________________________________________________________________________________________________________________
To align children within flex-box, set the following to the parent:

# 1- justify-content to align children along the main/primary axis i.e. vertical axis if parent has flex-direction: column and horizontal axis if parent has flex-direction: row.

# 2- align-items to align children along the cross/secondary axis i.e. horizontal axis if parent has flex-direction: column and vertical axis if parent has flex-direction: row.

In your case, try:

.container {
    display: flex;
    flex-direction: column;
    border: 1px solid red;
    justify-content: center; /* align children centered vertically */ 
    align-items: center; /* align children centered horizontally */
}
and remove margin from children that you are using to align children.


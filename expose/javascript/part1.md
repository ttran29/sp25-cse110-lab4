1. values added:  20
2. final result:  20
3. We should not use var because it can lead to naming conflcits and scoping issues.
4. values added:  20
5. Leads to a ReferenceError: result is not defined because using let is block-scoped while using var isn't. This means that result isn't accessible outside the if block
6. Leads to a TypeError: Assignment to constant variable because line 9 was never eached since using the const keyword will prevent reassignment to that variable. So in this case result has been assigned to 0 and we can not change it. 
7. Leads to a TypeError: Assignment to constant variable because line 9 was never eached since using the const keyword will prevent reassignment to that variable. So in this case result has been assigned to 0 and we can not change it. 
  
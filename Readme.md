<b>There are three ways to print out line numbers.<br>
Lets print all three in test.rb</b><br><br>
__LINE__<br>
caller()<br>
caller_locations(1,1)

caller_locations or __LINE__ will be the decision on which to implement. Lets figure out how all of that works :+1 in production.rb

## checklist
1) make sure the functionality is modular (callable from a method).
2)


These definitions must be understood: <br>
```Function Definition``` vs ```Prototype/Function Declaration``` vs ```Calling the Function```

## Dont forget the Overarching goal [#1](../../../../runtime-debug-all/runtime-debug-all/blob/master/Readme.md)
<b>it should</b> "print line number, var name, and var value"<br><br>
  ```line 10, testB, val 5 || line 11, testB, val 4 || line 10, testB, val 6 || line 11, testB, val 4```
  <br><br>```line 20, testC, val 2 || line 21, testD, val 3```
  <br><br>```line 24, testB, val 2```

  end

## About g4_4POU+FB.app


### POU_1
```
PROGRAM POU_1
VAR
    x: INT;
END_VAR
```
```
x := 1111;
```

### POU_2
*VAR defined same as POU_1*
```
x := 2222;
```


### POU_3
*VAR defined same as POU_1*
```
x := 3333;
```

### POU_4
*VAR defined same as POU_1*
```
x := 4444;
```

### FB_Counter
```
FUNCTION_BLOCK FB_Counter
VAR_INPUT
    enable: BOOL;
END_VAR
VAR
    count: INT;
END_VAR
```
```
IF enable THEN
    count := count + 1;
END_IF;
```

### FC_Add
```
FUNCTION FC_Add : INT
VAR_INPUT
	a:INT;
	b:INT;
END_VAR
VAR
END_VAR
```
```
FC_Add := a + b;
```

### SR_Main
```
PROGRAM SR_Main
VAR
    myCounter: FB_Counter;
    x: INT;
END_VAR
```
```
PROGRAM SR_Main
VAR
    myCounter: FB_Counter;
    x: INT;
END_VAR
```
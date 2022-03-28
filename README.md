# xerrors
extend special handler

## use 

```
err0 := xerrors.New("0")
err1 := xerrors.New("1")

errWrap := xerrors.Wrap(err1, err0)
fmt.Printf("%+v \n", errWrap)

flag := xerrors.Contains(errWrap, err0)
fmt.Println(flag)
```


# -
cd ./-

# \#0
just -,

cd ./-

# \#1
```cmd
/usr/bin/ld: /tmp/cc9iDlzX.o:(.data.rel.ro.local+0x0): multiple definition of `header'; /tmp/cckNaIHX.o:(.data.rel.ro.local+0x0):
first defined here
collect2: error: ld returned 1 exit status
```
OH, 'linker ' Noob 'linker'!

# \#2
```
   *****
   []-[]
  __|^|__
 |  \ /  |

///////////
just a push
```

# \#3
```python3
template = [os.path.isfile(_obj) and \
    file_list.append(_obj) or \
    os.path.isdir(_obj) and \
    dirs_list.append(_obj) for _obj in os.listdir(self.__path)]
```
`if-elif-else`: Fuck you!!

`and-or`: Wow

# \#4
```c
#define NUMARGS(...)  (sizeof((int[]){__VA_ARGS__})/sizeof(int))
```
> [C++ preprocessor __VA_ARGS__ number of arguments ...](https://stackoverflow.com/questions/2124339/c-preprocessor-va-args-number-of-arguments/2124433#:~:text=number%20of%20params%3A-,%23define%20NUMARGS(...)%20%20(sizeof((int%5B%5D)%7B__VA_ARGS__%7D)/sizeof(int)),-Full%20example%3A)

# \#5
**Freedom**

# \#6
```python3
class split:
    def __init__(self, string, jump_str=False, cut_index=-1) -> None:
        self.__S = []
        self.__match_key = ("object", "at")
        self.result = None

        if jump_str:
            ...
        else:
            self.__result = [s != "" and not s in self.__match_key and \
                self.__S.append(s) for s in re.split(r"[\W+]", string)]

        self.result = cut_index != -1 and self.__S[cut_index] or self.__S
        
        return None

print(split("<class '__main__.plugin'>", cut_index=0).result)
```

# \#7
```c
#define start_server(...) \
    Server.listen((struct ServerSettings){__VA_ARGS__})
```

**FROM** [`Server Framework`](https://github.com/ktvexe/server-framework/blob/e73a1319cfbe03d7252bc07df56e558292992cc3/protocol-server.h#L41-L42)

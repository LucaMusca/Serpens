# Serpens
python that speaks latin

## Description
Ever wondered how programming languages would look like if they were developed during the Roman Empire?  
To answer this question, I created this fork of cpython (version 3.9) that contains the latin translations of all the usual Python keywords.  
The folder `Grammar` contains the modified grammar files (compare them with `Grammar` in [cpython](https://github.com/python/cpython "The Python programming language")) that make this possible.

__Keywords__

| and | et
|:-------------:| :-----:|
| as | qualis
| assert | affirma
| break | incide
| class | classis
| continue | continua
| def | functio
| del | dele
| elif | aliterse
| else | aliter
| except | exceptio
| False | Falsus
| finally | deque
| for | per
| from | ab
| global | universalis
| if | se
| import | importa 
| in | in
| is | est
| lambda | lambda 
| None | Nihil
| nonlocal | nonlocalis
| not | non
| or | aut
| pass | transi 
| raise | leva
| return | restitue
| True | Verus
| try | conere
| while | dum
| with | cum
| yield | redde

## Installation
If you use linux, just download the file `serpens` and run it in the linux terminal with the command `./serpens`.  
If you use another OS, download [cpython](https://github.com/python/cpython "The Python programming language"), replace the `Grammar` folder with the one present in this repo and build the project following the [usual procedure](https://devguide.python.org/setup/ "Build cpython").

## Examples of usage
Just use the keywords listed above as they were the usual python keywords.
```Python
importa numpy qualis np
classis A:
    functio __init__(self, x):
          se x non est Nihil:
              self.x = x
```

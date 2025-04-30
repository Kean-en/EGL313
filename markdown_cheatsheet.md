# Headers
This is for **heading 1**
## Heading 2
This is for *heading 2*
### Heading 3
This is for ***heading 3***

# List
This is how u list items in markdown
1. Member 1
    * Project owner
2. Member 2
    * Hardware   
3. Member 3
    * Software
4. Member 4
    * Cheerleader


# Inserting an image
To insert an image, you will need to drag + hold shift + drop![alt text](cat.jpg)
[Click here to link](https://www.google.com)

[Click here to jump to test.md](/test/test.md)

# Code Block
To highlight or insert a particular section of code, you can do the following

1. In raspberry pi, if want to update you will `sudo apt update`

```
from tkinter import *
main=Tk()
main.mainloop()
```

# Quotes
A famous quote by ** Sir Issac Newton**
> For every action, there will be a reaction

# Tables
This is how you insert tables

|Header A|Header B|Header C|
|-------:|-------:|:-------|
|Row 1|Data A|Data B|
|Row 2| Data C|Data D|

```
|----:|This is to justify right
```

# Horizontal rule
This is how to insert a section line

---


# Flowchart

```mermaid
graph TD

A[Sensor 1]--GPIO 17--> B
B[Raspberry Pi]--> C[L-Acoustic K2 </br>Linear Line Array]
C --Anything--> A
A --> E
E --> C

```

# Sequence Diagram

```mermaid 
sequenceDiagram;

Alice ->> Bob: Hello, how are you
Bob -->> Alice: I am good
Alice ->> Charlie: Have you eaten?
Charlie -->> Alice: No i have not
```







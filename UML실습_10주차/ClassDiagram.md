```mermaid
classDiagram
    class BankAccount{
        +String owner$
        -Int 잔액
        +deposit(금액)* int
        +withdrawl(금액)$ int
    }
```

```{mermaid}
classDiagram
  direction TB
  class 학생 {
    -학생증: 학생증
  }
  class 학생증 {
    -id : int
    -name : string
  }
  class 자전거 {
    -id : int
    -name : string
  }
  학생 "1" --o "1" 학생증 : 가지고다닌다
  학생 "1" --o "1" 자전거 : 탄다
```

```{mermaid}
classDiagram
    classA <|-- classB
    classC *-- classD
    classE o-- classF
    classG <-- classH
```
```{mermaid}
classDiagram
    classI <.. classJ
    classK <|.. classL
    classM -- classN
    classO .. classP
```

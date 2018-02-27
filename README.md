# Software-Engineer-Interview-QA
A number of Software Engineer interview questions and answers

## <a name='topic'>Table of Contents</a>

  1. [General Questions](#general)
  1. [Architecture](#architecture)
  1. [Problem Solving](#problemsolving)

#### [[1]](#topic) <a name='general'>General Questions:</a>
    + What is polymorphism?
    + What is encapsulation?
    + What is inversion of control?

#### [[2]](#topic) <a name='architecture'>Architecture:</a>
    + Design principles:
        - Separation of concerns.
        - Single Responsibility principle.
        - Principle of Least Knowledge.
        - DRY: Don’t repeat yourself.
        - Minimize upfront design.
    + Drawbacks of not using `separation of concerns`.
    + Microservices is a variant of the service-oriented architecture (SOA).
    + What is SOLID Principles of Object Oriented and Agile Design?
        - Single responsibility principle.
        - Open/closed principle.
        - Liskov substitution principle.
        - Interface segregation principle.
        - Dependency inversion principle.
    + Design patterns. 
        - Creational: Builder, Object Pool, Factory Method, Signleton, Multiton, Prototype, Abstract Factory.
        - Structural: Adapter, Bridge, Composite, Decorator, Facade, Flyweight, Proxy.
        - Behavioral: Chain of Responsibility, Command, Interpreter, Iterator, Mediator, Memento, 
                        Observer, State, Strategy.
    + 3-tier architecture?
        - Presentation tier.
        - Application tier.
        - Data tier.
    + 3-layer architecture?
        - DAO (Repository).
        - Business (Service) layer.
        - Controller).
    + What is REST?
    + Idempotent operation EX: The PUT and DELETE methods are referred to as idempotent, 
        meaning that the operation will produce the same result no matter how many times it is repeated.
    + nullipotent operation EX: GET method is a safe method (or nullipotent), 
        meaning that calling it produces no side-effects.
#### [[3]](#topic) <a name='problemsolving'>Problem Solving:</a>
    + (medium) given a collection of numbers and a sum  , find a matching pair that is equal to the sum
        - assume the numbers is sorted
        - assume the numbers is not sorted 
        what is the best complexity you can come up with?
        can you do it in O(n^2) , O(nlog(n)) , O(n) , etc... ? where n is the length of the numbers

        example : [1 , 2 , 3 ,6]  , Sum = 10 , no matching pair
                : [1 , 2 , 4 , 4]  , Sum = 8 , matching pair = (4, 4)
                
    + (Easy) given a string  , find the first recurret charter in the string
        example : 'ABCDA' , answer = 'A'
                : 'ABCBDA' , answer = 'B'
                : 'ABC' , answer = NULL
        find the O(n) answer
# Computer Science and Engineering Roadmap and Checklist

> This is the complete syllabus of _Computer Science and Engineering UG_.

#### Computer Science is divided in 4 parts
 - [Computer Science 1](#computer-science---1) : Hardware and Engineering part.
 - [Computer Science 2](#computer-science---2) : Everything that is required to write Programs.
 - [Computer Science 3](#computer-science---3) : Daily Computer Science.
 - [Computer Science 4](#computer-science---4) : Real Life Applications of CS.

[**Discrete Mathematics**](http://home.iitk.ac.in/~arlal/book/mth202.pdf)<sup>PDF</sup> is necessary for understanding Graphs.

 - [Mathematics Syllabus can be found here](https://github.com/apeman/awesome_computer_science/blob/master/Mathematics.md)

## Table of Contents

 #### [Computer Science 1](#computer-science---1)
- [Digital Electronics](#digital-electronics)
- [Computer Organization and Architecture](#computer-organization-and-architecture)
- [Theory of Computation and Automata](#theory-of-computation-and-automata)
 #### [Computer Science 2](#computer-science---2)
- [Compiler Design](#compiler-design)
- [Programming](#programming)
- [Data Structures](#data-structures)
- [Algorithms](#algorithms)
- [Artificial Intelligence](#artificial-intelligence)
 #### [Computer Science 3](#computer-science---3)
- [Operating Systems](#operating-systems)
- [Computer Networks](#computer-networks)
- [DBMS and SQL](#dbms-and-sql)
- [Software Engineering](#software-engineering-after-learning-the-above)
 #### [Computer Science 4](#computer-science---4)
- [Cryptography](#cryptography)
- [Machine Learning](#machine-learning)
- [Computer Graphics](#computer-graphics)
- [Web Dev](#web-dev)

## Computer Science - 1

## Digital Electronics

- [ ] **[Boolean Algebra](http://www.uop.edu.pk/ocontents/ELEC-DIGE-S3%20Boolean%20Algebra%20Laws%20.pdf)**
   - Number System
   - Addition, Subtraction
   - Multiplication, Division
   - 1's, 2's compliments
   - k-maps

- [ ] **Hardware**
   - Logic Gates
   - Flip-Flops and Latches
   - Adder - Subtractor
   - Encoder - Decoder
   - Multiplexer - Demultiplexer
   - Integrated Circuits
   - [Printed Circuit Boards](https://www.youtube.com/watch?v=ljOoGyCso8s)

## Computer Organization and Architecture

- [ ] **Computer Organization**
   - Address Bus, Data Bus
   - ROM, EPROM, RAM
   - Memory Hierarchy, Cache Memory, Virtual Memory
   - Secondary Storage
   - Programmable Logic Devices and Controllers
   - Input - Output Devices

- [ ] **Computer Architecture**
   - Stack
   - Registers
   - Endianness (Big, Little)
   - Floating Point Numbers
   - Addressing Modes
   - Pipelining
   - Interrupts
   - RISC - CISC
   - aarch64, Intel_x86 / AMD64, MIPS / RISC-V (learn the differences)
   - [Assembly Language](https://stackoverflow.com/questions/1933801/x86-assembly-reference-sheet) (basic instructions)

## Theory of Computation and Automata

- [ ] **Automata and Languages**
   - NFA - DFA - NDFA
   - Regular Expressions
   - Context-Free Languages and Grammers
   - Pushdown Automata
   - Turing Machines
   - Decidability of Languages
   - Reducibility of Languages
   - Complexity Theory : P vs NP

## Computer Science - 2

## Compiler Design

- [ ] **Compiler Design**
   - Lexical analysis
   - Syntax analysis
   - Type Checking
   - Intermediate code generation
   - Machine code generation
   - Assembly and linking
   - Analysis and optimisation
   - Memory management
   - Interpreters
   - [Golang reference specifications](https://go.dev/ref/spec)<sup>If you want to red an easy specification</sup>

## Programming

- [ ] **[Learn C](https://codescracker.com/c/)**
    > The language almost every computer knows
    - [Character constants, escape sequences, string constants](https://www.cs.fsu.edu/~myers/c++/notes/basics1.html)
    - [Data types and Type conversion](https://www.cs.fsu.edu/~myers/c++/notes/basics2.html)
    - [Precedence and associativity](https://learn.microsoft.com/en-us/cpp/cpp/cpp-built-in-operators-precedence-and-associativity?source=apeman) of [Operators](https://learn.microsoft.com/en-us/cpp/cpp/cpp-built-in-operators-precedence-and-associativity?source=apeman)
    - [Functions](https://www.cs.fsu.edu/~myers/c++/notes/functions1.html)
    - [storage class](https://learn.microsoft.com/en-us/cpp/cpp/storage-classes-cpp?source=apeman) and [variable scope](https://learn.microsoft.com/en-us/cpp/cpp/scope-visual-cpp?source=apeman)
    - [if, for, while, switch_case](https://www.cs.fsu.edu/~myers/c++/notes/control1.html)
    - [break, continue, goto](https://codescracker.com/c/c-jump-statements.htm?source=apeman)
    - [Arrays](https://www.cs.fsu.edu/~myers/c++/notes/arrays.html), [Strings](https://www.cs.fsu.edu/~myers/c++/notes/strings.html), [Pointers](https://www.cs.fsu.edu/~myers/c++/notes/pointers1.html)
    - [Structs](https://www.cs.fsu.edu/~myers/c++/notes/structs1.html), [Union, enum, typedef](http://www.cs.cornell.edu/courses/cs2022/2009fa/lectures/lec06.pdf)
    - [Header files, #MACROS](https://learn.microsoft.com/en-us/cpp/cpp/header-files-cpp?source=apeman)
    - [malloc, calloc, realloc](https://www.cs.cmu.edu/~ab/15-123S09/lectures/Lecture%2008%20-%20%20Dealing%20with%20Dynamic%20Memory.pdf) | [2](https://manpages.ubuntu.com/manpages/xenial/man3/malloc.3.html), [new](https://www.cs.fsu.edu/~myers/c++/notes/dma.html), [argc argv](https://learn.microsoft.com/en-us/cpp/cpp/main-function-command-line-args?source=apeman)
    - [input/output](https://www.cs.fsu.edu/~myers/c++/notes/c_io.html), [file io](https://www.cs.fsu.edu/~myers/c++/notes/fileio.html), [streams](https://www.cs.fsu.edu/~myers/c++/notes/formatting.html)
    - [<Math.h>](https://pubs.opengroup.org/onlinepubs/009695399/basedefs/math.h.html)
    
    
- [ ] **[C++](https://www.cs.nmsu.edu/~jcook/tags/c/c++/)** (You can try **[Python](https://docs.python.org/3/tutorial/index.html)** for same topics)
    > Used in almost everything from Games to Browsers to Machine learning and beyond
    - [Everything mentioned in C](https://google.github.io/styleguide/cppguide.html)
    - [namespaces](https://learn.microsoft.com/en-us/cpp/cpp/namespaces-cpp?source=apeman)
    - [Classes](https://learn.microsoft.com/en-us/cpp/cpp/class-cpp?source=apeman) and [Objects](https://en.cppreference.com/w/cpp/language/object)
    - [Access Controls : Public, Private, Protected](https://learn.microsoft.com/en-us/cpp/cpp/member-access-control-cpp?source=apeman)
    - [Member Functions](https://learn.microsoft.com/en-us/cpp/cpp/overview-of-member-functions?source=apeman) and [Friend Functions](https://learn.microsoft.com/en-us/cpp/cpp/friend-cpp?source=apeman)
    - [Function Overloading](https://learn.microsoft.com/en-us/cpp/cpp/function-overloading?source=apeman)
    - [Constructor](https://learn.microsoft.com/en-us/cpp/cpp/constructors-cpp?source=apeman) and [Destructors](https://learn.microsoft.com/en-us/cpp/cpp/destructors-cpp?source=apeman)
    - [Inheritence](https://learn.microsoft.com/en-us/cpp/cpp/inheritance-cpp?source=apeman), [Polymorphism](https://www.cs.nmsu.edu/~jcook/posts/cpp-polymorphism/)
    - [Templates](https://learn.microsoft.com/en-us/cpp/cpp/templates-cpp?source=apeman)

## Data Structures

- **[Arrays](https://www.digitalocean.com/community/tutorials/how-to-work-with-arrays-in-ruby)**
- **[Linked Lists](https://www.cs.cmu.edu/~adamchik/15-121/lectures/Linked%20Lists/linked%20lists.html)**
- **[Skip Lists](https://www.cs.cmu.edu/~ckingsf/bioinfo-lectures/skiplists.pdf)**<sup>PDF</sup>
  - [Skip-Lists done right](http://ticki.github.io/blog/skip-lists-done-right/)<sup>Suggested Reading</sup>
- **[Hash Tables](https://www.cs.cornell.edu/courses/cs3110/2014fa/lectures/13/lec13.html), [2](https://www.eecs.umich.edu/courses/eecs380/ALG/hash_tables.html)**
- **stack** and **queue** and **set**
- [ ] **[Trees](http://math.hws.edu/eck/cs225/s03/binary_trees/)** and **Tries**
    - [ ] Self Balancing Trees
    - [ ] n-ary Trees
    - [ ] 2-3 Trees
- [ ] **[Graphs](http://www-h.eng.cam.ac.uk/help/tpl/talks/C++graphs.html)**
    - [ ] Adjacency matrix vs Adjacency list

## [Algorithms](https://xlinux.nist.gov/dads/)

- [ ] **Searching**
    - [ ] Breadth First Search
    - [ ] Depth First Search
- [ ] **[Sorting](https://en.wikipedia.org/wiki/Sorting_algorithm)**
    - [ ] Merge Sort
    - [ ] Quick Sort
    - [ ] Insertion Sort
    - [ ] Selection Sort
- [ ] **Graph Traversal**
    - [ ] Minimum Spanning Trees
    - [ ] Shortest Paths
- [ ] **space-time Complexity** 
    
## Artificial Intelligence

- [ ] **Knowledge Representation** and **Reasoning**
- [ ] **State Space**
- [ ] **Search**
    - [Hill Climbing](https://www.javatpoint.com/hill-climbing-algorithm-in-ai)<sup>Must know</sup>
    - [A*](https://www.ics.uci.edu/~kkask/Fall-2016%20CS271/slides/03-InformedHeuristicSearch.pdf)<sup>Must know</sup>
    - [MinMax](http://web.mit.edu/sp.268/www/gamesearch.pdf)<sup>Easiest Algorithm in AI</sup>
- [ ] **[Neural Networks](https://stackoverflow.com/questions/2019056/getting-a-simple-neural-network-to-work-from-scratch-in-c)**
    - Weights and Layers (Neural Networks)
    - Gradient Descent
    - Convolutional neural networks(https://towardsdatascience.com/convolutional-neural-networks-from-the-ground-up-c67bb41454e1)
- [ ] [Backpropagation](http://galaxy.agh.edu.pl/~vlsi/AI/backp_t_en/backprop.html)
- [ ] [Game Dev Basics](https://sheepolution.com/learn/book/contents)

## Computer Science - 3

## DBMS and SQL
[FCC quick commands](https://www.freecodecamp.org/news/basic-sql-commands/) | [Graphical view](https://www.guru99.com/sql-commands-dbms-query.html)
- [ ] **[SQL](https://www.javatpoint.com/sql-tutorial)**
    - [ ] **Data Definition Language**
     - [CREATE](https://www.1keydata.com/sql/sqlcreate.html)
     - [DROP](https://www.1keydata.com/sql/drop-table.html)
     - [ALTER](https://www.1keydata.com/sql/sql-alter-table.html)
     - [TRUNCATE](https://www.1keydata.com/sql/sqltruncate.html)
    - [ ] **Data Query Language**
     - [SELECT](https://www.1keydata.com/sql/sqlselect.html)
    - [ ] **Data Manipulation Language**
     - [INSERT](https://www.1keydata.com/sql/sqlinsert.html)
     - [UPDATE](https://www.1keydata.com/sql/update.html)
     - [DELETE](https://www.1keydata.com/sql/sqldelete.html)
    - [ ] **Data Control Language**
     - [GRANT](https://www.1keydata.com/sql/sql-grant.html)
     - [REVOKE](https://www.1keydata.com/sql/sql-revoke.html)
    - [ ] **Transction Control Language**
     - [COMMIT](https://www.1keydata.com/sql/sql-commit.html)
     - [ROLLBACK](https://dev.mysql.com/doc/refman/8.0/en/savepoint.html)
     - [SAVEPOINT](https://www.postgresql.org/docs/current/sql-savepoint.html)
    - [ ] **AGGREGATE FUNCTIONS**
     - [COUNT](https://www.1keydata.com/sql/sqlcount.html) | [SUM](https://www.1keydata.com/sql/sum-function.html) | [AVG](https://www.1keydata.com/sql/sql-average.html) | [MAX](https://www.1keydata.com/sql/max-function.html) | [MIN](https://www.1keydata.com/sql/min-function.html)
    - [ ] **JOINS**
     - [FULL OUTER JOIN](https://www.ibm.com/docs/en/db2-for-zos/12?topic=jdfmtot-full-outer-join)
     - [INNER JOIN](https://www.ibm.com/docs/en/db2-for-zos/12?topic=table-inner-joins)
     - [LEFT JOIN](https://stackoverflow.com/questions/5706437/) | [RIGHT JOIN](https://stackoverflow.com/questions/5706437/)
     - [NATURAL JOIN](https://docs.oracle.com/javadb/10.6.2.1/ref/rrefsqljnaturaljoin.html)
     - [LEFT OUTER JOIN](https://www.1keydata.com/sql/left-outer-join.html)
     - [RIGHT OUTER JOIN](https://docs.oracle.com/javadb/10.6.2.1/ref/rrefsqlj57522.html)

- **[DataBase Management Systems](https://www.javatpoint.com/dbms-tutorial)**
    - Entity-Relationship model.
    - [ ] **Integrity Constraints**
     - Primary Key and Foreign key
     - Composite keys
     - All other types of keys
    - [ ] Normal Forms : 1NF to 4 NF
    - [ ] File Organization.
    - [ ] Indexing (B- Trees and B+ Trees)
    - [ ] **Transactions and Concurrency Control**
    - Conflict Serializability
    - Locking
    - ACID | BASE
    - Database security
    - SQL Injection
    - Flat file / document database
    - Object / JSON based database
    
## [Operating Systems](http://pages.cs.wisc.edu/~remzi/OSTEP/)
   - The Boot Process
- [ ] **Processes and Threads**
  - Process Control Block
  - Dispatcher and Scheduler
- [ ] **Inter Process Communication**
  - Mesage Passing
  - Shared Memory 
- [ ] **Scheduling Algorithms**
  - Round Robin.
  - Shortest Remaining Time First.
  - Least Recently Used.  
- [ ] **Deadlocks**
  - MutEx and Locks
  - Semaphores
  - Banker's Algorithm
- [ ] **Memory Management**
  - Paging and Page tables
  - Segmentation
  - First Fit, Next Fit, Best Fit
  - Non-continuous Allocation
- [ ] **Virtual memory**
  - Page Faults
  - Page Replacement Algorithms
  - Belady’s Anomaly
- [ ] **File Systems**
  - File Allocation Tables.
  - Disk Scheduling Algorithms
- [ ] **OS Security**
  - Firewall
  - Malware and Antiviruses
- [ ] [Unix commands](http://www.ee.surrey.ac.uk/Teaching/Unix/)
## Computer Networks

- [ ] **Layers of TCP and OSI**
    - Application.
    - Presentation.
    - Session.
    - Transport.
    - Network.
    - Data.
    - Physical.

- [ ] **Flow Control**
    - Flow Control
    - Congestion Control
    - Error Control
    
- [ ] **Routers and Routing Algorithms**
    - DHCP and static routing
    - Round Robin and others
    - DHCP | ICMP
    
- [ ] **UDP and Sockets**

- [ ] **IPv4 | IPv6**
    
- [ ] **Application Layer Protocols**
    - HTTP | FTP
    - DNS | SMTP
    - Email MIME Types | POP | IMAP

## Software Engineering <sup>After learning the above</sup>

- [ ] **Software development models**
    - Waterfall
    - Spiral
    - Iterative
    - Agile

- [ ] **Software Cost Estimation**

- [ ] **COCOMO Model**

- [ ] **Risk Management**

- [ ] **Software Requirement**
    - Software Requirement Specifications
    - Data Flow Diagrams

- [ ] **Software Quality**
    - ISO standards 9001, 14001
    - SEICMM
    - Six Sigma

- [ ] **Software Design**
    - Software Design Principles
    - **Coupling and Cohesion**
    - Object-Oriented Design
    - User Interface Design

- [ ] **Testing**

## Computer Science - 4 
_You will need these when you make projects_

## Cryptography and Network Security

- [ ] **Encryption Algorithms**
    - DES, AES, Whirlpool, One Time Pad
- [ ] **Hashing Algorithms**
    - SHA family
- [ ] **Key Distribution**
    - RSA, Kerberos
- [ ] **Digital Signatures**
    - Message Digest    
 - [ ] **Compression**
    - [History](https://www.hanshq.net/zip.html#huffman).
 - [ ] **Firewalls**
 - [ ] **Network Security**
    - Honeypots
    - Man in the middle attacks
    - [DDOS prevention](https://www.researchgate.net/figure/DDoS-Mitigation-Module_fig3_220939734)


### Data Science and Machine Learning

- [ ] **[Bias and Variance](https://svivek.com/teaching/lectures/slides/loss-minimization/bias-variance.pdf)**

- [ ] **Supervised Learning**
   - [ ] [Classification](https://cogitoai.home.blog/2019/08/21/what-is-classification-in-machine-learning/)
   - [ ] [Regression](https://www.topcoder.com/thrive/articles/introduction-to-linear-regression)

- [ ] **Un-supervised Learning**
   - [ ] [Clustering](https://scikit-learn.org/stable/modules/clustering.html)
   - [ ] [k-Nearest Neighbours](https://web.iitd.ac.in/~bspanda/KNN%20presentation.pdf)

- [ ] **[Image Processing](https://homepages.inf.ed.ac.uk/rbf/HIPR2/wksheets.htm)**<sup>Worth learning</sup>
    - [Transformation](http://www.it.hiof.no/~borres/j3d/math/twod/p-twod.html) and [Translation](https://homepages.inf.ed.ac.uk/rbf/HIPR2/translte.htm)
    

## Web Development
> You can study Web Development from [Mozilla Developer Network Website](https://developer.mozilla.org/en-US/docs/Web/Tutorials).

- [MDN Getting Started Guide](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)
- [ ] **Front-End**
    - [HTML5](https://developer.mozilla.org/en-US/docs/Learn/HTML)
    - [CSS3](https://developer.mozilla.org/en-US/docs/Learn/CSS)
    - [JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
    - [Web Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms) 
    - [Accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility) 
    - [Tools and Testing](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing)
    - [DNS and Domain Names](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name)
    - [JSON and other formats](https://www.zionandzion.com/json-vs-xml-vs-toml-vs-cson-vs-yaml/) and [YAML](https://yaml.org/)

- [ ] **BackEnd**
    - [Golang](https://astaxie.gitbooks.io/build-web-application-with-golang/content/en/)


## [Computer Graphics](https://www.cs.uic.edu/~jbell/CourseNotes/ComputerGraphics/)

> Not mandatory, just get the overview

- [ ] **Concepts and principles**
    - [OpenGL basics : lines, planes, vertex and edges](https://learnopengl.com/)
    - [Pixels](http://math.hws.edu/graphicsbook/c2/s1.html)
    - [Rendering](https://github.com/ssloy/tinyrenderer/wiki)
    - [Shading](https://www.cs.uic.edu/~jbell/CourseNotes/ComputerGraphics/LightingAndShading.html)
    - [Texturing](https://www.cs.uic.edu/~jbell/CourseNotes/ComputerGraphics/TextureMapping.html)
    - [Ray Tracing](https://raytracing.github.io/books/RayTracingInOneWeekend.html)
    - [Raycasting](http://web.cs.wpi.edu/~matt/courses/cs563/talks/powwie/p1/ray-cast.htm)


After you are done with all this and want to make projects, check out [Projects you can make](https://github.com/apeman/awesome_computer_science/blob/master/what-should-i-code.md)

## LICENSE

[Mozilla-Public-License](./LICENSE.txt)

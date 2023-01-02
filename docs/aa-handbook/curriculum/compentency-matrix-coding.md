Based upon the [excellent guide](https://sijinjoseph.netlify.app/programmer-competency-matrix/) by Sijin Joseph.

The bulk of the original wording is unchanged, the first entries are geared towards FRC.


<table>
   <tbody>
      <tr>
      <tr><td><h3>FRC Specific
      <tr><th>   <th> Zero or little experience <th> Intermediate <th> Advanced <th> Mastery <th> Comments              
      <tr><td>Java
         <td> Fundamentals      
         <td> 
         <td>
         <td>
         <td>

      <tr><td>wpilib
         <td>Can install the wpilib, can add depedendencies
         <td>Understand how to utilize the many different aspects of the library
         <td>
         <td>Explores the interals, confident they could contribute to wpilib         
         <td>

      <tr><td>roborio      
         <td> Understanding of how to send programs
         <td> An understanding of how communication takes place between the driver station and the roborio 
         <td> 
         <td> An understanding of the internals of the roborio, from the operating system, to the bootloader, to the overall hardware
         <td> 

      <tr><td>Control loops/PID
         <td> Randomly plugs things into a PID 
         <td> Able to predict the behavior of their modifications to PID
         <td> Able to construct new PID from scratch
         <td> Able to construct a model driven tuner for PID
         <td>

      
      <tr><th> Area <th> Zero to no experience <th> Intermediate <th> Advanced <th> Mastery <th> Comments              
      <tr><td><h3>Computer Science
      <tr>
         <td>Data structures
         <td>Doesn’t know the difference between Array and LinkedList
         <td>Able to explain and use Arrays, LinkedLists, Dictionaries etc in practical programming tasks
         <td>Knows space and time tradeoffs of the basic data structures, Arrays vs LinkedLists, Able to explain how hashtables can be implemented and can handle collisions, Priority queues and ways to implement them etc.
         <td>Knowledge of advanced data structures like B-trees, binomial and fibonacci heaps, AVL/Red Black trees, Splay Trees, Skip Lists, tries etc.
         <td>
      
      <tr>
         <td>Algorithms
         <td>Unable to find the average of numbers in an array (It’s hard to believe but I’ve interviewed such candidates)
         <td>Basic sorting, searching and data structure traversal and retrieval algorithms
         <td>Tree, Graph, simple greedy and divide and conquer algorithms, is able to understand the relevance of the levels of this matrix. (was in big O notation before modified)
         <td>Able to recognize and code dynamic programming solutions, good knowledge of graph algorithms, good knowledge of numerical computation algorithms, able to identify NP problems etc.
         <td>
      
      <tr>
         <td>Systems Programming
         <td>Doesn’t know what a compiler, linker or interpreter is
         <td>Basic understanding of compilers, linker and interpreters. Understands what assembly code is and how things work at the hardware level. Some knowledge of virtual memory and paging.
         <td>Understands kernel mode vs. user mode, multi-threading, synchronization primitives and how they’re implemented, able to read assembly code. Understands how networks work, understanding of network protocols and socket level programming.
         <td>Understands the entire programming stack, hardware (CPU + Memory + Cache + Interrupts + microcode), binary code, assembly, static and dynamic linking, compilation, interpretation, JIT compilation, garbage collection, heap, stack, memory addressing…
         <td>
      
      <tr><td><h3>Software Engineering       
      
      <tr><th> Area <th> Zero to no experience <th> Intermediate <th> Advanced <th> Mastery <th> Comments        
      
      <tr>
         <td>Source Code Management/Version Control
         <td>Folder backups by date
         <td>VSS and beginning CVS/SVN user
         <td>Proficient in using CVS and SVN features. Knows how to branch and merge, use patches setup repository properties etc.
         <td>Knowledge of distributed VCS systems. Has tried out Bzr/Mercurial/Darcs/Git
         <td>
      
      <tr>
         <td>Build Automation
         <td>Only knows how to build from IDE
         <td>Knows how to build the system from the command line
         <td>Can setup a script to build the basic system
         <td>Can setup a script to build the system and also documentation, installers, generate release notes and tag the code in source control
         <td>
      
      <tr>
         <td>Automated Testing
         <td>Thinks that all testing is the job of the tester
         <td>Has written automated unit tests and comes up with good unit test cases for the code that is being written
         <td>Has written code in TDD manner
         <td>Understands and is able to setup automated functional, load/performance and UI tests
         <td>
      
      <tr><td><h3>Programming              
      <tr><th> Area <th> Zero to no experience <th> Intermediate <th> Advanced <th> Mastery <th> Comments        
      
      <tr>
         <td>Problem Decomposition
         <td>Only straight line code with copy paste for reuse
         <td>Able to break up problem into multiple functions
         <td>Able to come up with reusable functions/objects that solve the overall problem
         <td>Use of appropriate data structures and algorithms and comes up with generic/object-oriented code that encapsulate aspects of the problem that are subject to change.
         <td>
      
      <tr>
         <td>Systems Decomposition
         <td>Not able to think above the level of a single file/class
         <td>Able to break up problem space and design solution as long as it is within the same platform/technology
         <td>Able to design systems that span multiple technologies/platforms.
         <td>Able to visualize and design complex systems with multiple product lines and integrations with external systems. Also should be able to design operations support systems like monitoring, reporting, fail overs etc.
         <td>
      
      <tr>
         <td>Communication
         <td>Cannot express thoughts/ideas to peers. Poor spelling and grammar.
         <td>Peers can understand what is being said. Good spelling and grammar.
         <td>Is able to effectively communicate with peers
         <td>Able to understand and communicate thoughts/design/ideas/specs in a unambiguous manner and adjusts communication as per the context
         <td>This is an often under rated but very critical criteria for judging a programmer. With the increase in outsourcing of programming tasks to places where English is not the native tongue this issue has become more prominent. I know of several projects that failed because the programmers could not understand what the intent of the communication was.
      
      <tr>
         <td>Code Organization Within a File
         <td>no evidence of organization within a file
         <td>Methods are grouped logically or by accessibility
         <td>Code is grouped into regions and well commented with references to other source files
         <td>File has license header, summary, well commented, consistent white space usage. The file should look beautiful.
         <td>
      
      <tr>
         <td>Code Organization Across Files
         <td>No thought given to organizing code across files
         <td>Related files are grouped into a folder
         <td>Each physical file has a unique purpose, for e.g. one class definition, one feature implementation etc.
         <td>Code organization at a physical level closely matches design and looking at file names and folder distribution provides insights into design
         <td>
      
      <tr>
         <td>Source Tree Organization
         <td>Everything in one folder
         <td>Basic separation of code into logical folders.
         <td>No circular dependencies, binaries, libs, docs, builds, third-party code all organized into appropriate folders
         <td>Physical layout of source tree matches logical hierarchy and organization. The directory names and organization provide insights into the design of the system.
         <td>The difference between this and the previous item is in the scale of organization, source tree organization relates to the entire set of artifacts that define the system.
      
      <tr>
         <td>Code Readability
         <td>Mono-syllable names
         <td>Good names for files, variables classes, methods etc.
         <td>No long functions, comments explaining unusual code, bug fixes, code assumptions
         <td>Code assumptions are verified using asserts, code flows naturally – no deep nesting of conditionals or methods
         <td>
      
      <tr>
         <td>Defensive Coding
         <td>Doesn’t understand the concept
         <td>Checks all arguments and asserts critical assumptions in code
         <td>Makes sure to check return values and check for exceptions around code that can fail.
         <td>Has his own library to help with defensive coding, writes unit tests that simulate faults
         <td>
      
      <tr>
         <td>Error Handling
         <td>Only codes the happy case
         <td>Basic error handling around code that can throw exceptions/generate errors
         <td>Ensures that error/exceptions leave program in good state, resources, connections and memory is all cleaned up properly
         <td>Codes to detect possible exception before, maintain consistent exception handling strategy in all layers of code, come up with guidelines on exception handling for entire system.
         <td>
      
      <tr>
         <td>IDE
         <td>Mostly uses IDE for text editing
         <td>Knows their way around the interface, able to effectively use the IDE using menus.
         <td>Knows keyboard shortcuts for most used operations.
         <td>Has written custom macros
         <td>
      
      <tr>
         <td>API
         <td>Needs to look up the documentation frequently
         <td>Has the most frequently used APIs in memory
         <td>Vast and In-depth knowledge of the API
         <td>Has written libraries that sit on top of the API to simplify frequently used tasks and to fill in gaps in the API
         <td>E.g. of API can be Java library, .net framework or the custom API for the application
      
      <tr>
         <td>Frameworks
         <td>Has not used any framework outside of the core platform
         <td>Has heard about but not used the popular frameworks available for the platform.
         <td>Has used more than one framework in a professional capacity and is well-versed with the idioms of the frameworks.
         <td>Author of framework
         <td>
      
      <tr>
         <td>Requirements
         <td>Takes the given requirements and codes to spec
         <td>Come up with questions regarding missed cases in the spec
         <td>Understand complete picture and come up with entire areas that need to be speced
         <td>Able to suggest better alternatives and flows to given requirements based on experience
         <td>
      
      <tr>
         <td>Scripting
         <td>No knowledge of scripting tools
         <td>Batch files/shell scripts
         <td>Perl/Python/Ruby/VBScript/Powershell
         <td>Has written and published reusable code
         <td>
      
      <tr>
         <td>Database
         <td>Thinks that Excel is a database
         <td>Knows basic database concepts, normalization, ACID, transactions and can write simple selects
         <td>Able to design good and normalized database schemas keeping in mind the queries that’ll have to be run, proficient in use of views, stored procedures, triggers and user defined types. Knows difference between clustered and non-clustered indexes. Proficient in use of ORM tools.
         <td>Can do basic database administration, performance optimization, index optimization, write advanced select queries, able to replace cursor usage with relational sql, understands how data is stored internally, understands how indexes are stored internally, understands how databases can be mirrored, replicated etc. Understands how the two phase commit works.
         <td>
      
      <tr><td><h3>Experience
      <tr><th> Area <th> Zero to no experience <th> Intermediate <th> Advanced <th> Mastery <th> Comments        
      
      <tr>
         <td>Languages with Professional Experience
         <td>Imperative or Object Oriented
         <td>Imperative, Object-Oriented and declarative (SQL), added bonus if they understand static vs dynamic typing, weak vs strong typing and static inferred types
         <td>Functional, added bonus if they understand lazy evaluation, currying, continuations
         <td>Concurrent (Erlang, Oz) and Logic (Prolog)
         <td>
      
      <tr>
         <td>Platforms with Professional Experience
         <td>1
         <td>2-3
         <td>4-5
         <td>6+
         <td>
      
      <tr>
         <td>Years of Professional Experience
         <td>1
         <td>2-5
         <td>6-9
         <td>10+
         <td>
      
      <tr>
         <td>Domain Knowledge
         <td>No knowledge of the domain
         <td>Has worked on at least one product in the domain.
         <td>Has worked on multiple products in the same domain.
         <td>Domain expert. Has designed and implemented several products/solutions in the domain. Well versed with standard terms, protocols used in the domain.
         <td>
      
      <tr><td><h3>Knowledge
      <tr><th> Area <th> Zero to no experience <th> Intermediate <th> Advanced <th> Mastery <th> Comments        
      
      <tr>
         <td>Tool Knowledge
         <td>Limited to primary IDE (VS.Net, Eclipse etc.)
         <td>Knows about some alternatives to popular and standard tools.
         <td>Good knowledge of editors, debuggers, IDEs, open source alternatives etc. etc. For e.g. someone who knows most of the tools from Scott Hanselman’s power tools list. Has used ORM tools.
         <td>Has actually written tools and scripts, added bonus if they’ve been published.
         <td>
      
      <tr>
         <td>Languages Exposed To
         <td>Imperative or Object Oriented
         <td>Imperative, Object-Oriented and declarative (SQL), added bonus if they understand static vs dynamic typing, weak vs strong typing and static inferred types
         <td>Functional, added bonus if they understand lazy evaluation, currying, continuations
         <td>Concurrent (Erlang, Oz) and Logic (Prolog)
         <td>
      
      <tr>
         <td>Codebase Knowledge
         <td>Has never looked at the codebase
         <td>Basic knowledge of the code layout and how to build the system
         <td>Good working knowledge of code base, has implemented several bug fixes and maybe some small features.
         <td>Has implemented multiple big features in the codebase and can easily visualize the changes required for most features or bug fixes.
         <td>
      
      <tr>
         <td>Knowledge of Upcoming Technologies
         <td>Has not heard of the upcoming technologies
         <td>Has heard of upcoming technologies in the field
         <td>Has downloaded the alpha preview/CTP/beta and read some articles/manuals
         <td>Has played with the previews and has actually built something with it and as a bonus shared that with everyone else
         <td>
      
      <tr>
         <td>Platform Internals
         <td>Zero knowledge of platform internals
         <td>Has basic knowledge of how the platform works internally
         <td>Deep knowledge of platform internals and can visualize how the platform takes the program and converts it into executable code.
         <td>Has written tools to enhance or provide information on platform internals. For e.g. disassemblers, decompilers, debuggers etc.
         <td>
      
      <tr>
         <td>Books
         <td>Unleashed series, 21 days series, 24 hour series, dummies series…
         <td>Code Complete, Don’t Make me Think, Mastering Regular Expressions
         <td>Design Patterns, Peopleware, Programming Pearls, Algorithm Design Manual, Pragmatic Programmer, Mythical Man month
         <td>Structure and Interpretation of Computer Programs, Concepts Techniques, Models of Computer Programming, Art of Computer Programming, Database systems , by C. J Date, Thinking Forth, Little Schemer
         <td>
      
      <tr>
         <td>Blogs
         <td>Has heard of them but never got the time.
         <td>Reads tech/programming/software engineering blogs and listens to podcasts regularly.
         <td>Maintains a link blog with some collection of useful articles and tools that he/she has collected
         <td>Maintains a blog in which personal insights and thoughts on programming are shared
         <td>
      
   </tbody>
</table>

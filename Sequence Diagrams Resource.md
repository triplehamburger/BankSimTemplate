
```
Author: Alex (Raj) Rajasekaran

Please feel free to recommend any additions for your TA to add!
```
## Sequence Diagram Programs
- [sequencediagram.org](https://sequencediagram.org/) - simple sequence diagram maker
- Mermaid ([https://mermaid.js.org/](https://mermaid.js.org/)) - a little more in-depth UML diagram maker that uses markdown files (very cool). You can embed these directly into your repository
- Previous Student Recommendations
	- PlantUML ([https://plantuml.com/en/sequence-diagram](https://plantuml.com/en/sequence-diagram))
	- Drawio (https://www.drawio.com/blog/sequence-diagrams)

## How to make a sequence diagram
### Basics FOR THIS (PayStationMain) ASSIGNMENT!!
- In this assignment, each call needs a corresponding return. In theory, all 
- When a new object is called, it needs to be activated
- After a return, the returning object needs to be deactivated
- When thinking about where each call needs to come from, read through your source code and follow where each of your methods takes you
	- Each time a function is called, there should be a corresponding arrow on your diagram (with a return)
	- Is your method calling other methods within itself?
	- Which object is doing the calling and which object is being called?
### Threads
- Individual threads do not need to wait for other thread's returns or calls to make any calls or returns of their own
- Note that if a thread is calling an already activated object, the activated object needs to be activated again
### Examples and Resources
- https://ars.els-cdn.com/content/image/3-s2.0-B9780750662727500087-f05-10-9780750662727.jpg (from https://www.sciencedirect.com/topics/computer-science/sequence-diagram)
- https://developer.ibm.com/articles/the-sequence-diagram/
- https://stackoverflow.com/questions/1643733/how-to-illustrate-multiple-threads-in-sequence-diagram (threads in UML Sequence Diagrams)
_Nucleo's Low-Level Learning Plan — v1.0_
# 🧠 Low-Level Programming Mastery Map (Post-CS:APP)

This roadmap focuses on deepening practical low-level programming skills after completing *Computer Systems: A Programmer's Perspective (CS:APP)*.

---

## ✅ Checklist

- [x] Completed *Computer Systems: A Programmer's Perspective (CS:APP)*

---

## 🚀 Mastery Flowchart

```mermaid
flowchart TD
    A[Deep Memory Allocators] --> B[Data Layout & Serialization]
    B --> C[Advanced Systems Programming]
    C --> D[Advanced Concurrency ]
    D --> E[Deep Linking, Loading, ELF/Binary Formats]
    E --> F[Virtual Machines and Interpreters]
    F --> G[Operating System Projects]
```

### Resources

| Step | Broad Topic | Free Book / Resource |
|:---|:---|:---|
| 1 | **Deep Memory Allocators** | [Modern Operating Systems (Ch 2)](https://cs.brown.edu/courses/cs161/papers/tanenbaum-memory.pdf) |
| 2 | **Manual Data Layout & Serialization** | [Zig Learn (Structs and Memory)](https://ziglearn.org/) |
| 3 | **Advanced Systems Programming** | [Beej's Guide to Network Programming](https://beej.us/guide/bgnet/) |
| 4 | **Advanced Concurrency (Lock-Free)** | [OSTEP (Concurrency Advanced)](https://pages.cs.wisc.edu/~remzi/OSTEP/) |
| 5 | **Deep Linking, Loading, ELF/Binary Formats** | [Linkers and Loaders (Free Draft)](https://www.iecc.com/linker/linker.pdf) |
| 6 | **Virtual Machines and Interpreters** | [Build Your Own Lisp](http://www.buildyourownlisp.com/) |
| 7 | **Operating System Projects** | [The Little Book About OS Development](https://littleosbook.github.io/) |

---

## ✨ Real Project Ideas

| Phase | Project |
|:---|:---|
| Deep Memory | Implement a slab allocator in Zig. |
| Data Layout | Serialize/deserialize a Zig struct manually to a file. |
| Systems | Write a TCP echo server using raw syscalls (no stdlib). |
| Concurrency | Implement a lock-free ring buffer (FIFO queue) in Zig. |
| Linking/Binaries | Write a parser that reads and prints ELF section names. |
| VM | Create a bytecode interpreter for math expressions (`3 + 5 * 2`). |
| OS | Write a bootloader that prints text, then a kernel that changes colors. |


# 📊 Backend Development (Flowchart)

```mermaid
flowchart TD
  A(Server and Application Logic) --> A1(gRPC APIs)
  A --> A2(WebSocket APIs)
  A --> A3(GraphQL APIs)
  A --> A4(Business Logic)
  
  B(Database Management) --> B1(Database Design and Modeling)
  B --> B2(Advanced SQL)

  C(Security) --> C1(Data Protection - Encryption)
  C --> C2(Input Validation and Sanitization)
  C --> C3(Access Control - RBAC)
  C --> C4(Compliance - GDPR, HIPAA)

  D(Performance Optimization) --> D1(Caching Strategies)
  D --> D2(Load Balancing Concepts)
  D --> D3(Database Indexing & Query Optimization)
  D --> D4(Code and API Optimization)

  E(Communication with Other Services) --> E1(Microservices Architecture)
  E --> E2(Message Queues - RabbitMQ, Kafka)
  E --> E3(Third-party Integrations - APIs)
```

---

# Backend Development

## 📚 Resources (Mostly Free)

| Topic | Free Resources |
|:---|:---|
| **gRPC APIs** | - [gRPC Basics - Google Codelabs](https://grpc.io/docs/what-is-grpc/introduction/) <br> - [Practical gRPC (Book Free Online)](https://www.oreilly.com/library/view/practical-grpc/9781492058328/) |
| **WebSocket APIs** | - [WebSockets - MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API) <br> - [WebSocket Tutorial - FreeCodeCamp](https://www.freecodecamp.org/news/websockets-tutorial/) |
| **GraphQL APIs** | - [How to GraphQL - Free Fullstack Tutorial](https://www.howtographql.com/) |
| **Business Logic & Domain-driven design** | - [Domain-Driven Design Quickly (Free Book PDF)](https://www.infoq.com/minibooks/domain-driven-design-quickly/) |
| **Database Design & Modeling** | - [Database Design - Stanford Online Course](https://lagunita.stanford.edu/courses/DB/2014/SelfPaced/about) |
| **Advanced SQL** | - [Mode Analytics SQL Tutorial](https://mode.com/sql-tutorial/) <br> - [LeetCode SQL Problems (Free practice)](https://leetcode.com/problemset/database/) |
| **Security** | - [OWASP Top 10 (must-read free)](https://owasp.org/www-project-top-ten/) |
| **Caching & Performance** | - [Designing Data-Intensive Applications (Chapter 11 - Caching is free)](https://dataintensive.net/) |
| **Microservices, Message Queues** | - [Microservices Fundamentals - Microsoft Free Book](https://learn.microsoft.com/en-us/dotnet/architecture/microservices/) |
| **RabbitMQ/Kafka Basics** | - [RabbitMQ Tutorials - Official](https://www.rabbitmq.com/getstarted.html) <br> - [Kafka 101 - Confluent Free Course](https://developer.confluent.io/learn/kafka-fundamentals/) |

---

## 🛠️ Small Projects To Solidify Each

| Topic | Mini-Project |
|:---|:---|
| **gRPC APIs** | Build a *simple chat service* using gRPC (text messages between users) |
| **WebSocket APIs** | Create a *live collaborative text editor* (like Google Docs basic) |
| **GraphQL APIs** | Build a *blog app* with GraphQL queries/mutations |
| **Business Logic** | Make a *shopping cart system* with discount rules |
| **Database Design** | Design a *library system* (Books, Authors, Users, Loans) |
| **Advanced SQL** | Build a *report generation system* (e.g., Monthly active users, Total orders) |
| **Security** | Make a *login system* with encrypted passwords and role-based access |
| **Performance Optimization** | Add *Redis caching* to an API and measure before/after response times |
| **Microservices** | Create two microservices: *User Service* and *Order Service* communicating via events |
| **Message Queues** | Simulate *order processing* with RabbitMQ (order queued and processed asynchronously) |
| **Third-party Integrations** | Integrate *Stripe payment API* in a mock store |

---

## 🚀 Suggested Learning Path (Optional)

1. **Database Design and Advanced SQL**  
   \- Learn design first → then SQL queries → then transactions.

2. **Server and Application Logic (gRPC, WS, GraphQL)**  
   \- Build APIs after mastering database.

3. **Security Basics**  
   \- Learn input validation, encryption, and access control.

4. **Performance Optimization**  
   \- Add caching, optimize queries, learn how load balancing works.

5. **Communication with Other Services**  
   \- Learn microservices, queues, and integrate third-party services.

✅ This sequence helps you "stack" knowledge practically like in real-world backend projects!

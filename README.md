# CS340-portfolio

## How do you write programs that are maintainable, readable, and adaptable? Consider your work on the CRUD Python module from Project One.

I focus on writing clean, modular code with clear separation of concerns. The CRUD Python module I developed encapsulates all database interactions into a class, making it easy to update or extend without affecting the rest of the application. By using consistent naming conventions, in-line comments, and exception handling, the module is both readable and resilient. The advantage of this approach is that the dashboard widgets can call the same CRUD methods regardless of the underlying database structure. In the future, this module could be reused for other projects that require basic database operations, or it could be expanded to include additional collections or more complex queries without rewriting the core logic.

## How do you approach a problem as a computer scientist?

I approach problems by first understanding the client's needs and then breaking the project into manageable components. For Grazioso Salvare, I started with the database and authentication, then built the CRUD module, and finally developed the dashboard interface. In the future, I would apply the same modular, iterative strategy: gather requirements and gradually add functionality while constantly testing each component.

## What do computer scientists do, and why does it matter?

Computer scientists design and build systems that solve real-world problems efficiently and reliably. This project, for example, allows Grazioso Salvare to quickly filter and visualize animal shelter data, helping them identify dogs suitable for search-and-rescue training. By creating a clean, reusable CRUD module and an intuitive dashboard, I enabled non-technical users to interact with complex data without needing to write queries themselves. This type of work matters because it translates raw data into actionable insights, helping organizations make better decisions and ultimately save lives.

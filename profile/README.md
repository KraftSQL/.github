# **Kraft**SQL

![logo](../logo/logo.line.png)

"Craft your SQL transformations with the power of Kotlin™."

## Why **Kraft**SQL?

Modern data warehouse systems usually include a powerful SQL engine.
Using this for your data transformations saves you extra infrastructure, but doing it all with plain SQL can become a mess.

**Kraft**SQL lets you craft high quality SQL code with the power of Kotlin - for high quality data.

### Features

*Modular Structure* - Break your business logic into manageable and reusable chunks.

*Scalability* - **Kraft**SQL grows with your needs, from the first `SELECT`-statement to complex data transformations.

*Coding Support* - Leverage IDE support and detect bugs at compile time, thanks to Kotlin and its strong type system.

*Testing* - Unit-test your data transformations before running them in your data warehouse.

*Extensibility* - Use existing connectors or even write your own to connect to any SQL engine and its dialect.

*Lean Scope* - **Kraft**SQL focuses on its core task to generate SQL code, thereby fitting into any data processing workflow.

## State of this project

**Kraft**SQL is still in its Proof of Concept and Proof of Value phase.
In this phase features to implement are mainly prioritized by high risk or by importance to demonstrate the value of **Kraft**SQL to potential users.
Hence, the breadth of the covered SQL features is rather small and you will find reandomly chosen specialties to be implemented while a lot of the basics aren't.
Furthermore the conepts and core interfaces still evolve.
This is also reflected by its 0.0.x versions.

Once this PoC and PoV is successful, **Kraft**SQL will focus on covering more and more SQL features.
In this phase versions will change to 0.x.y, where an increase in x indicates new features while an increase in y indicates fixes.

With at least the most common SQL features implemented, **Kraft**SQL is planned to be released as 1.0.0 and switch to semantic versioning.

## Learn more

Have a look at the [Documentation](https://github.com/KraftSQL/documentation/wiki) to learn more about **Kraft**SQL and how to use it.

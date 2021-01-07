# Direct study in Database Applications (CS3068)

**Book:** Database Systems: The Complete Book 2nd Edition
by Hector Garcia-Molina, Jeffrey Ullman, Jennifer
Widom

**Homework:** We will use Gradiance for the exercises. After 10 minutes
od delay, the exercise set can be tried again, any number of times.
Please visit `https://www.newgradiance.com` and join the class `A365923A`. You will see the first exercise set then.

## Schedule

### Weeks 1 and 2

**Topic:** ER Diagrans and relations

**book:** Chapter 4,4.1-4.6 (p.119-165)

**Exercise:** 1 on Gradiance

### Weeks 3 and 4

**Topic:** Relational algebra

**book:** Chapter 2,2.1,2.2,2.4,2.5 (p.15-28,38-62)

**Exercise:**
  + 2 on Gradiance
  + Questions 2.4.1 and 2.4.3 in the book, please use
    `https://dbis-uibk.github.io/relax/calc/local/uibk/local/0` to check
your solution and send me by email the result. I will check it using this
website.

**Slides:** classes 5 and 6

### Weeks 5, 6 and 7

**Topic:** SQL

**Book:** Chapter 6, 6.1, 6.2, 6.3, 6.4, 10.2 (p. 243-289,437-444)

**Exercises:**
  + 3 on Gradiance
  + The 4 labs on Gradiance

**Slides:** classes 9-15

### Weeks 8 and 9

**Topic:** Database programming, indexes and triggers

**Book:** 2.3, 6.5, 7, 7.1, 7.2, 7.3, 7.4, 7.5, 8, 8.1, 8.2, 8.3, 8.5,
9.3, 9.4 (p. 29-36,291-295,311-338,341-352,378-403)

**PostgreSQL:**
  * [PL/pgSQL Guide](https://www.postgresql.org/docs/12/plpgsql.html)
  * [ElephantSQL](https://www.elephantsql.com/plans.html)
    + Create an account and a new free Tiny DB
    + Use the Elephant Browser

**Exercise:**
  + [Exercise 4](Exercises/ex4/ex4.pdf)
  + [createTables.sql](Exercises/ex4/createTables.sql)

**Slides:** class 8, classes 16-18

### Weeks 10, 11 and 12

**Topic:** Database design

**Book:** 3,3.1-3.5 (p. 67-105)

**Exercise:** 5 on Gradiance

**Slides:** class 18-24

## Final project

The final project should describe precisely a data based problem. It can
either involve a new problem or a detailed description of an existing
one (like Twitter). Most importantly, it should be based on real
requirements.

There are three required deliverables:

* **Project proposal:** should consist of 1-2 pages describing the problem you plan to solve, outlining how you plan to solve it, and describing what you will "deliver" for the final project.

* **Database design and implementation:** should contain
  1. Complete ER diagram
  2. Description of the functionalities users should be able to execute
     over the data, including invariants and constraints.
  3. A complete translation of the ER diagrams to relations
  4. An optimized version of the relations based on the last part of the
     course.
  5. Scripts for creating the database schema in PostgreSQL
  6. Triggers, indexes and procedures implementations

* **Final Report:** You should summarize step 2 in a detailed final
   report discussing the above six steps, choices made and problems
encountered. The report should describe the second step and be faithful
to the first step. Nevertheless, the report should be a standalone
artefact which can be used for tackling the original problem.

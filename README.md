# SQL-Server-Notes
Hello world, this is Saumya Kushwaha. This is my SQL notes and practice repo.
Topic :- ER Diagrams

An ER Diagram (Entity-Relationship Diagram) is a type of structural flowchart used in database design. It visually models how different "entities (things)" (like people, objects, or concepts) relate to one another within a system.

Entity - anything which has a phyical existence- represented in a rectangular shape

Relationship -  represented in a barfi shape

Attribute - specific characteristic, property, or piece of data that describes an entity. Attribute is represented in an oval shape 

Example- In a database for a school

Entity - Student
Attributes        StudentID (e.g., 10482)
                   FirstName (e.g., "Alex")
                   LastName (e.g., "Smith")
                   Address
                   Mobile no.
1. Key Attribute
What it is: Uniquely identifies a specific record (Primary Key).
Visual: Underlined text inside the oval.
Student Example: StudentID (e.g., STU10482)

2. Composite Attribute
What it is: Can be broken down into smaller, independent sub-fields.
Visual: Main oval branched into smaller sub-ovals.
Student Example: Name ➔ splits into FirstName and LastName.

3. Multi-Valued Attribute
What it is: Can hold more than one value for a single record at the same time.
Visual: Double-lined oval.
Student Example: PhoneNumbers (A student can have both a personal mobile and a home number).

4. Derived Attribute
What it is: Not stored directly; calculated dynamically from other data.
Visual: Dashed-line oval.
Student Example: Age (Calculated automatically from DateOfBirth).

Student Attribute Data Sheet

StudentID ➔ Key Attribute (e.g., 2026048)

Name ➔ Composite Attribute (e.g., FirstName: Alex, LastName: Smith)

Gender ➔ Simple / Single-Valued Attribute (e.g., Female)

PhoneNumbers ➔ Multi-Valued Attribute (e.g., ['555-0192', '555-0143'])

Age ➔ Derived Attribute (e.g., 20 — calculated from DateOfBirth)

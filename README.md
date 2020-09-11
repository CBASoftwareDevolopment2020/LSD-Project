# LSD-Project

[Case 1](https://datsoftlyngby.github.io/soft2020fall/resources/e12f05a6-case-1.pdf)

- [Assignment 1 - Logical Data Model](https://datsoftlyngby.github.io/soft2020fall/resources/535325c7-01-logical-data-model.pdf)
- [Assignment 2 - Use Case Model](https://datsoftlyngby.github.io/soft2020fall/resources/a9edbcd7-02-use-case-model.pdf)
- [Assignment 3 - System Operations Contract](https://datsoftlyngby.github.io/soft2020fall/resources/a3cead66-03-system-operations-contract.pdf)


## LDM Decription
A **flight carrier** has 0 or more **flights** available. A flight is a trip, which is used to manage flight seats. The trip information is stored in the **Schedule**, which gets the **departure** and **arrival** informations from the **airports**.  
A **booking** is an interface for either a one-way or roundtrip, and the entity can be seen as an order, it includes the **passengers** which the **flight** is booked for.
**Flight seats** are not distributed at the time of booking, but there is an option to distribute them at a later time.  
The **travel agency** have **employees** who will the users of our system.
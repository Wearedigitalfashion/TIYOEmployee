## TIYO Employee

## Task
Below is a fictional scenario which highlights **users** and *components* of the scenario and process.
In your own time and approach, create a solution using .net and any architecture and approach you consider fit for purpose.

The aim is *NOT* to create a perfect end-to-end system, but rather architecture and approach, feel free to go into as much detail as you'd like, but the expectation is not a production-ready system.

### Business Scenario
Currently, in the garment design industry, the process is very one-sided and doesn't allow for much feedback and reviews.
For that reason, clothes are very opinionated and less input and data-driven.
With our new tool, "TIYO Employee", we aim to change the industry practices for that.

The aim is to allow input from people in various stages of the process and allow opinions of others to influence the garment design and manufacturing process.

#### Overview
A garment is typically designed by a **designer** who will come up with designs and specifications and make decisions such as material, composition, colour and cut of the garment.

The **designer** will then typically produce a *design*, which is then fitted on a mannequin, and pictures are taken.
The pictures along with the *description*, *name*, *price*, *material composition* and *colour* are then stored in a *catalogue* .

After that, the **designer** will use that catalogue item and, using TIYO Emplyee, open it up for voting and send the *draft item* out to other users.
They can be any of the **trend advisor**, **retail buyers**, other **co-designers**  and **head of design**.

This will allow all other parties to rate the item with a *comment*, a *demand score* from `0 to 10`, `0` being not desired at all, and `10` being a highly popular item.

After the designer has had enough insights, they can close the *draft item* from voting and look at all the reviews as well as the *average demand score*.

#### Solution

Use whatever approach you consider appropriate and allow for a .net - API - centric solution (feel free to implement a front-end if you'd like).
This should allow for the process mentioned above.

To simplify the solution, the only user of the system is the **designer** and all others are not system users, but the system should still allow them to vote on it.

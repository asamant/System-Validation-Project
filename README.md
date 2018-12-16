# System-Validation-Project
Project files for the course IN4387 System Validation.

- This project deals with a system in which a set of robots is used to move wafers to and from a projecting lamp which is enclosed in a vacuum chamber. The transfer of wafers in and out of this chamber takes place via airlocks, and the system ensures that at no point can the inner chamber be in direct contact with the outer part. The airlocks are present to prevent such a scenario from arising and hence their functioning in key here.

- There are two outer robots whose roles are to pick up wafers from the inputs stacks (2) and drop them in the output stacks (2) after the projection cycle is complete; this includes moving the wafers from the input stacks to the airlock outer doors and then to the output stacks. There is one inner robot whose role is to pick up fresh wafers from the airlock inner doors and place them under a projection lamp for the circuit to be etched on them. Moreover, once it's done, the inner robot is also responsible for moving the etched wafers from the lamp to the airlock inner doors.

## Components
- Code: contains all the code related to the project. This includes:
  * MCRL2 code files consisting of the core logic for the robot system.
  * mu-calculus formula files (MCF) for verifying the logic.
  * "old-vault" - consists of all the initial files used for putting the project together. To be used only for reference; archived.

- Documents: contains documents related to the project - the report, architecture diagrams, initial design diagrams, etc.

- Submission: contains zip archives of the submissions made for the project.

# Appendix A · Workspace Theory

*This appendix gives the formal backbone for Chapters 06 (Continuity) and 08 (Workspace). It is not required reading — the manual runs without it — but the operator who wants to know* why *the savepoint works, and* what *a delta is, will find the answers here.*

## A.1 · The ever-changing workspace

What I call the **Historiotopia** is the three-dimensional surface of the workspace — the tables, walls, stacks, and screens, arranged in space. Two facts govern it:

1. At any given moment, the workspace is in a current **configuration**, or **state**.
2. The state is subject to **change**. Every working day, the configuration differs from the day before.

Whenever two work-states — call them *w₁* and *w₂* — differ by a physical, discernible, appreciable change, we say *w₁* **precedes** *w₂*, written *w₁* ≺ *w₂*. Precedence has a converse: *w₂* **succeeds** *w₁*, and the state *w₂* is **accessible** from *w₁* — meaning the workspace could actually get there from here, by some sequence of real operations. (A state that cannot be reached from the current one is not a future state; it is a fantasy. The operation plans only in accessible states.)

*Note on notation: in mathematics, the relationship "x precedes y" for ordered sets is written x ≺ y. I use the symbol in exactly this sense.*

There is a precise thermodynamic analogue worth borrowing. In the Lieb–Yngvason axiomatic formulation of thermodynamics, a state *Y* is **adiabatically accessible** from a state *X*, written *X* ≺ *Y*, if the change from *X* to *Y* can be effected by interaction with some device — mechanical, electrical, auxiliary — that returns to its initial condition afterward, the only lasting trace being, say, a weight raised or lowered in a gravitational field. Strip away the physics and keep the structure: a later work-state is adiabatically accessible from an earlier one if the operation can get there *and the apparatus that got it there is ready to work again*. That last clause is the savepoint, formalized (Chapter 06): the session ends with the device — the workspace — restored to a working condition, the only lasting trace being the work produced.

## A.2 · Deltas

When the workspace moves from one state to another, the appreciable change between them is a **delta**, denoted Δ. Workspaces change *over time*, so deltas take place over time as well.

This is why Chapter 08 asks you, every morning: *what is different here today?* The operator must be hyper-sensitive to Δs, because deltas **signal**. A single delta is a fact; a sequence of deltas is a trend; and once you are tracking trends, you are no longer merely noticing differences — you are measuring *rates* of change.

Formally: regard the change from workspace *A* to workspace *A′* as a **mutation** — a function *M* taking *A* as input and producing *A′ = M(A)* as output. Then:

> *A′ − A = Δ-workspace*

If time is *t* and the **historiotopic function** *h(t)* carries the workspace from one configuration to the next, then the deltas are the changes of *h* over time — and the *rate* of those changes is the derivative of *h* with respect to time:

> If the input of a function represents time, then the derivative represents change with respect to time. If *f* takes a time as input and gives the position of a ball as output, then the derivative of *f* is how the position changes in time — that is, the velocity of the ball.

By exact analogy, the derivative of the historiotopic function is the **historiotopic velocity**: how fast the workspace's configuration is changing. A series in full production has high historiotopic velocity; a stalled operation has velocity near zero — which is the formal statement of momentum death (Chapter 06). The morning survey (Chapter 08) is, in these terms, a velocity reading: the operator samples *h(t)* daily and watches the derivative.

## A.3 · The Historiotheque as warehouse

Velocity matters because the Historiotheque is, among other things, a **manufacturing operation** — and manufacturing operations are usefully understood as warehouses. The Historiotheque is the name of the art studio *and* the office; the workspace it names is modular, and the operations conducted there are multifarious — wide in range, interdisciplinary by definition.

Consider the warehouse stripped to its function. A warehouse interrupts the flow of goods: it takes an **InFlow** (shipments from suppliers) and produces an **OutFlow** (shipments to customers). It unloads, stores, assembles, and loads. Over any period, its flow consists of *orders*, each order having *lines*, each line identifying a *stock*, a *unit of handling*, and a *quantity*.

The Historiotheque — call the operating house the **H-house**, the operation the **H-op** — differs from a standard warehouse in exactly one structural respect: where the warehouse interrupts the flow of goods from suppliers to customers, the H-house interrupts the flow of **inputs** (raw materials, art supplies, equipment — and *signals*: communications, commissions, provocations) from the outside to the inside, and the flow of **outputs** (finished works, publications, records) from the inside to the outside, toward the end-user or audience of the H-house's productions.

The functional requirements are therefore the warehouse's, translated:

- **Consume the InFlow.** Unload and store inputs — materials received, data collected In The Field (Chapter 03), signals taken in.
- **Produce the OutFlow.** Assemble and load outputs — manufactured artifacts, published works, public records — and ship them to their destinations (publication prepared in advance, Chapter 02).

The attributes of inputs and outputs relevant to design decisions are threefold — **physical** (what it is, how it stores, how it degrades), **operational** (how it moves through the procedure, what it constrains), and **managerial** (what it costs, who is responsible, how it is accounted for). Run every significant input and output through those three attributes before committing the operation to it.

This is the beginning of what I call the **logistics of the Historiotheque**: the discipline of InFlow and OutFlow managed as deliberately as the work itself. An operation that manufactures brilliantly but cannot receive, store, or ship is a warehouse with no doors. Mind the doors.

## References

- McGinnis, L.: *An object oriented and axiomatic theory of warehouse design.* In: Carrano, A., Gue, K., de Koster, R., Ogle, M., Montreuil, B., Smith, J. (eds.) 12th International Material Handling Research Colloquium — 2012. Material Handling Industries of America (2013).
- Lieb, E. H., Yngvason, J.: *The physics and mathematics of the second law of thermodynamics.* Physics Reports 310 (1999). — The source of the adiabatic-accessibility formulation used in §A.1.

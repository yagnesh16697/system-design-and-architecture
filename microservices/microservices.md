### Microservices

- small, autonomous, harmonic

Core idea: Divide and Conquer

Break a product into manageable sub-problems and tackle each
one of them separately.

Each sub-problem is solved separately and optimally.

Why **Microservices**?

- Codebase grows overtime
  - difficult to co-ordinate
  - change in one module by one team can break others
  - reduces product developement velocity
- Scaling becomes predictable
  - Each service scales independently
    Search might be on 10 instances while Auth on 20 & Payments on 3
- Autonomous & Isolation
  - Your own tech stack, networking interface, protocols
  - Pure client-server relationship
  - You change your own code, deploy when you want.
- Fault Tolearance
  - If one is down you might still have a partially operational system
- Updates are simpler
  - you can evolve your service to Better lang, Better DB, Better infra

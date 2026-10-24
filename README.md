# Embodiment

How do body mechanics and interactions with the environment produce behavior or reduce the work required of a controller? Covers passive movement, self-modeling and adaptation to bodily damage.

## Body dynamics and regulation

- **Ultrastability and the Homeostat** - When essential variables leave acceptable bounds, a second feedback process changes the system's parameters. Ashby's four-unit machine demonstrates adaptation through finding a stable configuration. [Ashby 1960](<https://www.ashby.info/Ashby%20-%20Design%20for%20a%20Brain%20-%20The%20Origin%20of%20Adaptive%20Behavior.pdf> "Design for a Brain; Chapman & Hall (second edition)").
- **Braitenberg vehicles** - Thought experiments construct increasingly elaborate behavior from simple mechanisms. They connect synthetic machines with psychological interpretations of behavior; the book's vehicles are hypothetical constructions. [Braitenberg 1984](<https://mitpress.mit.edu/9780262521123/vehicles/> "Vehicles: Experiments in Synthetic Psychology; MIT Press").
- **Passive dynamic walking** - Leg geometry and mechanics support a stable walking cycle down a shallow slope without active control. Physical prototypes exploit gravity as the energy source and body dynamics as part of the control solution. [McGeer 1990](<https://doi.org/10.1177/027836499000900206> "Passive Dynamic Walking; Int. J. Robot. Res.").

## Body design and adaptation

- **Evolving virtual creatures** - Genetic search jointly evolves articulated bodies and neural controllers in simulated physics. Swimming, walking, jumping and following emerge under researcher-specified fitness functions. [Sims 1994](<https://www.karlsims.com/papers/siggraph94.pdf> "Evolving Virtual Creatures; SIGGRAPH"); [video](<https://www.karlsims.com/evolved-virtual-creatures.html>).
- **Robot self-modeling** - A four-legged robot tests actions that discriminate candidate models of its body, then uses a model to generate gaits. After a leg segment is removed, revised models support compensatory walking. [Bongard et al. 2006](<https://doi.org/10.1126/science.1133687> "Resilient Machines Through Continuous Self-Modeling; Science").
- **Intelligent trial and error** - A behavior map computed before deployment guides rapid adaptation after damage. Tests use a physical hexapod and a simulated arm; recovery reuses prior search rather than discovering all behaviors after injury. [Cully et al. 2015](<https://doi.org/10.1038/nature14422> "Robots that can adapt like animals; Nature").

## Open questions

- Which behavioral capacities survive changes in the body or environment beyond those used in design and training?
- How much recovery comes from body dynamics, online inference or an externally computed repertoire?

## Related topics

- [Hyperorganism](https://hyperorganism.github.io/)
- [Soft-body computation](https://hyperorganism.github.io/unconventional-computing/#physical-and-biological-computations) - A body can supply dynamics for a trained readout; the readout and drive remain part of the apparatus.
- [Biohybrid systems](https://hyperorganism.github.io/biohybrid-systems/) - Living actuators and neural interfaces add integration questions.
- [Strandbeest](https://hyperorganism.github.io/systems-aesthetics/#bodies-and-living-materials) - Mechanical behavior also has an artistic lineage.
- [Basal Cognition](https://hyperorganism.github.io/basal-cognition/)

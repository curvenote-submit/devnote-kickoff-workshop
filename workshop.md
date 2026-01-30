## Key Themes: Engineering, Integration, and Connections

### Shared Understanding: language, communication, and context
* **Modules, processes, and core capacities:** what is a module and what isn't?
  * **Module:** a well-defined component which performs a task in the biological system (e.g., a genetic circuit which senses a molecule, a hydrogel matrix that provides a color-change output.
  * **Process:** a technique, protocol, or process which is used to build, integrate, or work with a Developer Cell (e.g., phase-transfer encapsulation, 3D printing).
  * **Capacity:** the ability to perform a process in service of building a Developer Cell. More specifically, the superpower of having people or labs within each node focused on operating a capacity to enable other participants to work better and faster (e.g., cell-free circuit validation, diffusion characterization, modeling).
* **Context:** what are we each doing, what are we trying to achieve together, why are we doing it, and how will we do it?
* **Clarity:** the more detail and clarity we have, the more quickly we can identify problems and work together to solve them.
  * **Dependencies:** how do the parts relate, and when does one part have to be complete to avoid blocking progress on other parts?
  * **Requirements:** what must be true for the demo, and how does that flow backwards to engineering design of modules and system. For example, how long must the demo operate for, in what environment, with what equipment? Likewise, how should a module work so that it can be used by others after the project itself is complete?
  * **Hidden Parts:** are there any necessary components that are hidden in the dependency tree. Through discussion though the week, we identified several modules (*E. coli* RNA polymerase, alpha-hemolysin) that were either unspecified or not clearly assigned to a person.

### Shared Problems and Solutions: an opportunity to move faster by working together
* **Internode Collaboration:** both nodes desire (and are planning to determine by experiment) information about or optimization of the same thing. For example, diffusion rates of small molecules through liposome membranes or hydrogels, lipid compositions which are compatible with various hydrogels, sensitivity of Developer Cells to hydrogel crosslinkers (UV, free-radical generation). Coordinating and centralizing this work would save time and effort (though, as a complement, replicating results at least once would improve reliability).
* **Methods and Protocols:** shared data, methods, and consistent approaches will enable us to make use of, and trust, one another's work. We used a consistent fluorescent standard for our plate reader based experiments, and which we will use to normalize it to concrete eGFP concentration standards. However, such a tool does not yet exist for cell microscopy data, and developing one together would enable more effective work both within and beyond the project.
* **Group Knowledge:** many questions had answers that were already known, or could be found rapidly with the help of others across the group. We should find ways to leverage the variety of skill and experience effectively within and between all the nodes.

### Shared Platform: how can we build in similar and interoperable ways
* **Sensible defaults:** what are our default settings for ways to run protocols, compositions of modules, etc. To ensure that modules work together, we should strive to make the minimal necessary changes from these defaults (for example, preferring the same lipid composition for liposome membranes). Likewise, we should optimize systems using the more flexible parameters; to the extent modules already work with a given composition we should maintain it and make other components work with that.
* **Enabling technology:** what could we build (or cause to be built) that would help the work proceed?

## Project Considerations
### Risks
* **Business as usual:** if we operate as a research collaboration, not an engineering project, we won't get it done. We need clear goals and an operation mandate that will allow us to prioritize, specialize, and collaborate.
* **Specificity of design:** if we co-optimize every component, modules won't be interoperable beyond the demo, node, project.
* **Ambiguity:** unknown or yet-to-be decided details prevent forward motion elsewhere; likewise late changes will have an amplified effect. Technical and planning ambiguity must be knocked down as rapidly as possible (e.g., specific molecules and their performance, hydrogel compositions). When in doubt, we likely want to choose simpler or better-understood options if we can.

### Specific Questions and Ideas
* **Key parameters:** osmolarity of reagents and target concentrations of substrates; matrix pore sizes and diffusion behavior; molecular sizes and interactions.
* **Learn more, stay connected:** subgroup meetings, tech talks. There are a number of topics we didn't have time to cover that are fertile ground for learning and discussion: DNA design, deeper metrology of PURE and liposomes, etc.
* **Accessible patterning:** using Opentrons as a baseline platform for 3D printing.
* **A shared glossary of terms:** so we can understand what's going on across the different technical fields.
* **Rapid initial learning through simple experiments:** can we quickly knock down or confirm key questions and risks by running fast prototype experiments. For example, hand-making a dye QR code in hydrogel, exposure bulk PURE to UV light, validating leak using dyes.
* <b><i>More Drawing</i></b> 

## Beyond the Workshop
### Developer Studio

- There is consensus that having whole teams present for the DevStudio will have the greatest likelihood of success for replicating the demonstrations. In this format, the entire team's expertise can be leveraged which will likely be necessary for debugging challenges at Module interfces. 
  
- In the best case, b.next would be able to replicate results before the team fly out to the studio. This will require close iteration loops and regular communication, regular subgroup meetings organized by topics should be scheduled.

- Early sharing of genetic constructs, critical reagents, and enabling documentation will be key with appropriate functional milestones.

### Next Steps
* Get plate reader and microscopy data to b.next so we can make it work with the CDK
* Set up the logistics for shipping PURE
* Publish this Developer Note
* Publish the experimental Developer Note
* Make sure we stay in touch
* *Sleep a bit*

## Reflections and Conclusions

### Reflections on the Workshop

### Zooming out

:::::{tab-set}
::::{tab-item} Whitespace Chart
:::{figure} ./node-san-francisco/whitespace.png
“White space” chart, showing a possible path to engineering biology at scale using synthetic cells. Figure by Richard Murray used under CC-BY-4.0 / unmodified from original.
:::
::::

::::{tab-item} Nucleus Cycle
:::{figure} ./node-san-francisco/nucleus-cycle.png

:::
::::
:::::

* What are our goals?
  * Concrete demos demonstrating the potential of Developer Cells to engineer useful biotechnological solutions to be shared iteratively throughout the year.
  * Build out the open-source portfolio of useful modules that can be replicated and used by others.
  * Build a community of synthetic cell developers committed to improving upon shared practices.
  * Improve the process of synthetic cell engineering and integration by doing it at increasing scale.

:::{pull-quote}
How can we help?
:::
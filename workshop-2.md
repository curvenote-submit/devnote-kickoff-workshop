<!-- # Overview

On December 8, 2025, 19 participants gathered at Nucleus Labs in San Francisco to kickoff the Developer Cells (DevCells) program. This program brings together scientists and engineers with expertise ranging from synthetic biology to materials science representing six different institutions organized into four nodes to build with and extend Nucleus. Two nodes (London and Chicago) will be creating demonstration projects built from integrated synthetic cell components. A third node based in San Francisco will work to ensure that the components developed by the first two nodes are reproducible and sufficiently documented for inclusion on Nucleus. A fourth node based in San Luis Obispo will make use of these components to introduce synthetic cells to an undergraduate audience. 

:::{table}

| Node | Institutions | # of Workshop Participants |
| --- | --- | --- |
| Chicago | Northwestern University, University of Michigan | 7 |
| London | Imperial College, King's College, University College | 6 |
| San Francisco | b.next | 5 |
| San Luis Obispo | CalPoly SLO | 1 |

:::

The workshop had three goals: 1) introduce participants to Nucleus Platform including Cytosol, Devloper Notes (DevNotes), Hub, and the Cell Development Kit (CDK); 2) create a space to discuss and refine the development plan for the demonstration projects; 3) community building.  -->

# Syncing on Node Plans

The DevCells program is requires coordination at multiple levels.

- Inter-node alignment: members of each node must understand how their individual contributions fit together to realize the demonstration project.
- Cross-node overlap: members of each node should identify shared problems, duplicated efforts, opportunities to coordinate in other nodes.
- Reproducibility pathway: members of each node should understand how they will use Nucleus and work with the core development team at b.next to ensure that their development efforts are sufficiently documented for inclusion into Nucleus. 

To ensure that these coordination needs are addressed we organized several structured sessions for participants to turn over the details of individual contributions (modules) and then how those modules will come together in the final demonstration projects. What follows are the key themes that we identified during these discussions.

## Key Themes: Engineering, Integration, and Connections

### Shared Understanding: language, communication, and context

Given the incredible diversity of participant backgrounds both in terms of area of expertise (membrane biophysics, materials science, biosensors) and home institutions, the need to develop shared language and context could not be overstated. We found that the terms "module", "process", and "capacity" were often refererred to and useful but often used in different ways by different people. We aligned on the following definitions:

- **Module:** a well-defined component which performs a task in the biological system (e.g., a genetic circuit which senses a molecule, a hydrogel matrix that provides a color-change output.
- **Process:** a technique, protocol, or process which is used to build, integrate, or work with a Developer Cell (e.g., phase-transfer encapsulation, 3D printing).
- **Capacity:** the ability to perform a process in service of building a Developer Cell. More specifically, the superpower of having people or labs within each node focused on operating a capacity to enable other participants to work better and faster (e.g., cell-free circuit validation, diffusion characterization, modeling).

Once we had established a shared language and understanding of the modules needed to be integrated into the demonstration. It became possible to more clearly articulate project dependencies and requirements. Through these discussions we identified a few hidden parts, any necessary components that are hidden in the dependency tree. For example, we identified several modules (e.g. *E. coli* RNA polymerase, alpha-hemolysin) that were either unspecified or not clearly assigned to a person

### Shared Problems and Solutions: an opportunity to move faster by working together

By bringing project participants together in the same room, we could identify complementary expertise across labs and nodes.

- **Internode Collaboration:** both nodes desire (and are planning to determine by experiment) information about or optimization of the same thing. For example, diffusion rates of small molecules through liposome membranes or hydrogels, lipid compositions which are compatible with various hydrogels, sensitivity of Developer Cells to hydrogel crosslinkers (UV, free-radical generation). Coordinating and centralizing this work would save time and effort (though, as a complement, replicating results at least once would improve reliability).
- **Methods and Protocols:** shared data, methods, and consistent approaches will enable us to make use of, and trust, one another's work. We used a consistent fluorescent standard for our plate reader based experiments, and which we will use to normalize it to concrete eGFP concentration standards. However, such a tool does not yet exist for cell microscopy data, and developing one together would enable more effective work both within and beyond the project.
- **Group Knowledge:** many questions had answers that were already known, or could be found rapidly with the help of others across the group. We should find ways to leverage the variety of skill and experience effectively within and between all the nodes.

### Shared Platform: how can we build in similar and interoperable ways

Facilitating these discussions while also introducing the Nucleus Platform in parallel made it natural to think of what kind of platform improvements would immediately enable the project participants. 

- **Sensible defaults:** what are our default settings for ways to run protocols, compositions of modules, etc. To ensure that modules work together, we should strive to make the minimal necessary changes from these defaults (for example, preferring the same lipid composition for liposome membranes). Likewise, we should optimize systems using the more flexible parameters; to the extent modules already work with a given composition we should maintain it and make other components work with that.
- **Enabling technology:** what could we build (or cause to be built) that would help the work proceed? Critical needs are will likely be unearthed over the course of the project.

### Project Risks

Several key project-level risks were identified that are worth highlighting here:

* **Business as usual:** if we operate as a research collaboration, rather than an engineering project, we will likely fall short of our goals. We need clear milestones and project participants at all levels should be enabled and empowered to prioritize, specialize, and collaborate.
* **Specificity of design:** if we co-optimize every component, modules won't be interoperable beyond the demo, node, project.
* **Ambiguity:** unknown or yet-to-be decided details prevent forward motion elsewhere; likewise late changes will have an amplified effect. Technical and planning ambiguity must be knocked down as rapidly as possible (e.g., specific molecules and their performance, hydrogel compositions). When in doubt, we likely want to choose simpler or better-understood options if we can.

<!-- The DevCell Kickoff Workshop gave participating researchers a valuable hands-on introduction to using Nucleus Cytosol and Nucleus Cells, which will serve as foundational modules for work across the Chicago and London nodes over the coming year. The workshop also included bootcamp-style training on the Nucleus Cell Developer Kit (CDK) for data analysis, along with guided practice in preparing and publishing DevNotes through the Nucleus Hub. Overall, the workshop delivered intensive training in both experimental and digital tools designed to accelerate project development and support the release of concise research outputs throughout the DevCell Project. -->
---
layout: page
title: Projects
---

{% if page.subtitle == "" %}
<div class="empty_subtitle"></div>
{% endif %}
<p style="text-align:center"><a href="#winc">WINC</a> | <a href="#ewic">EWiC</a> | <a href="#quad">QUADRATURE</a> | <a href="#wiplash">WiPLASH</a> | <a href="#gnn">IGNNSPECTOR</a> | <a href="#visorsurf">VISORSURF</a> | <a href="#tugraco">TUGRACO</a> | <a href="#gwc">GWC</a></p>

<br/>
### <a name="winc"></a> WINC: Wireless Networks within Next-Generation Computing Systems
- **Website:** [www.winc-project.eu](https://www.winc-project.eu)
- **Project Type:** ERC Starting Grant
- **Funding:** 1.5 M€
- **Duration:** 2022-2027
- **Media coverage:**
     - [ENG] [HiPEAC Info Magazine](https://www.hipeac.net/magazine/7163.pdf) \| [Spain Arts & Culture](https://spainculturescience.co.uk/winc-sergi-abadal/) \| [UPC News](https://www.upc.edu/en/press-room/news/starting-grant-for-upc-researcher-sergi-abadal-to-develop-a-new-generation-of-faster-and-more-efficient-processors-with-wireless-communication-systems-and-quantum-computing) 
     - [ESP] [LaVanguardia](https://www.lavanguardia.com/vida/20220331/8166863/upc-desarrollara-procesadores-diez-veces-mas-rapidos-actuales.html)
     - [CAT] [Espai Mèdia](https://espai.media/politiques-digitals-i-id/sergi-abadal-de-la-upc-destinara-lajut-starting-grant-al-projecte-winc/)

<p align="center"><img src="/img/ERC-2021-StG-WINC.jpg" width="80%"/></p>

Computing systems are ubiquitous in our daily life and have transformed the way we learn, work, or communicate with each other, to the point that progress is intimately tied to the improvements brought by new generations of the processors that lie at the heart of these systems.

A common trait of current computing systems is that their internal data communication has become a fundamental bottleneck. The anticipated death of Moore’s Law has forced computer scientists and architects to find new ways to build faster processors, which include massive parallelization, specialized accelerator design, and disruptive technologies such as quantum computing. These trends cause an exponential increase in the volume and variability of data transfers within computing systems, rendering traditional interconnects insufficient and threatening to halt progress unless fast and versatile communication alternatives are developed.

In this context, the WINC project envisions a revolution in computer architecture enabled by the integration of wireless networks within computing systems. The main hypothesis is that wireless terahertz technology will lead to at least a tenfold improvement in the speed, efficiency, and scalability of both non-quantum and quantum systems. With a cross-cutting approach, WINC aims to validate the hypothesis by (i) revealing the fundamental limits of wireless communications within computing packages, (ii) developing antennas and protocols that operate close to those limits while complying with the stringent constraints of the scenario, and (iii) developing radically novel architectures that translate the unique benefits of the wireless vision into order-of-magnitude improvements at the system level. If successful, WINC will be the seed of a new generation of non-quantum and quantum systems and foster progress in the computing field for the decades to come.


<br/><br/>
### <a name="ewic"></a> EWiC: Emulation of Wireless Communication among Chiplets inside a Computing System
- **Website:** To be announced
- **Project Type:** ERC Proof of Concept
- **Funding:** 150 K€
- **Duration:** 2024-2026
- **Media coverage:**
     - [ESP] [UPC](https://www.upc.edu/es/sala-de-prensa/noticias/el-investigador-sergi-abadal-recibe-una-subvencion-de-prueba-de-concepto-para-estudiar-la-comunicacion-inalambrica-en-entornos-de-computacion-integrados)
 
<p align="center"><img src="/img/ewic.jpeg" width="50%"/></p>

Domain specialisation (e.g., AI) coupled with skyrocketing manufacturing costs of chips led to a paradigm shift towards chiplet-based computing. However, the current Network-in-Package (NiP) is not suited for the increasing chiplet (CPUs, AI accelerators, etc.) count and their diverse communication needs. As a result, communication has become the main bottleneck to computing advances. Wireless transmission can enable a one-hop communication with low latency parallelism. The wireless links can be reconfigured dynamically for demand-specific services. Finally, the native broadcast capability of wireless transmission will provide natural support for scalability. However, wireless communication is limited by the bandwidth. Hence, the ERC Starting Grant WINC explored via simulation combining wireless communication with the high bandwidth of wired connections, proving potential for >5× speedups. In EWiC, we aim, for the first time, to emulate and demonstrate wireless communication among chiplets inside a computing system. The goal is to experimentally validate our simulation results, which have shown high speedups in multi-chiplet systems. Successful results will generate interest in the industry for further research and application in various domains, such as speeding up computation in pharma for new drug design. EWiC will thus help fully realise the trillion-euro potential of advanced computing, alongside immense social benefits and establishing EU leadership in this field. The EWiC project will thus assess the commercialisation potential of our technology, engaging with key stakeholders such as chipmakers and end-users. Exploitation options including licensing, startup creation, or joint ventures, will be explored based on prototyping results and market entry considerations. Our IPR strategy will involve a thorough analysis to identify and protect the novel results of the project. We will additionally carry out a Freedom to Operate (FTO) analysis to ensure exploitability.


 
<br/><br/>
### <a name="quad"></a> QUADRATURE: Scalable Multi-Chip Quantum Architectures Enabled by Cryogenic Wireless/Quantum-Coherent Network-in-Package
- **Website:** [www.quadrature-project.eu](https://www.quadrature-project.eu)
- **Project Type:** EIC PATHFINDER
- **Funding:** 3.4 M€
- **Duration:** 2023-2027
- **Media coverage:**
     - [ENG] [Equal1](https://www.equal1.com/post/equal1-wins-major-pathfinder-grant-award)
 
<p align="center"><img src="/img/Qvision.png" width="50%"/></p>

Today’s tremendous interdisciplinary efforts towards building a quantum computer is aimed at a machine capable of tackling problems beyond the reach of any classical computer. The so-called quantum advantage has been already claimed with state-of-the-art Noisy Intermediate-Scale Quantum (NISQ) computers consisting of several tens of quantum bits (qubits). Nevertheless, it is widely recognized that addressing any real-world problem will require upscaling to thousands or even millions of qubits. Scaling quantum computers to such a large number of qubits is a major challenge due to, among others, the confluence of (i) technology factors confining the qubits to low fidelity, (ii) the need for cryogenic temperatures to reach practical coherence times, (iii) the dense integration of digital/RF control circuits, which are needed on a per-qubit basis, and (iv) the manifold architectural and algorithmic implications of managing noisy and short-lived qubits.

The QUADRATURE project focuses upon the grand challenge of scalability in quantum computers from an architectural or full-stack standpoint. We are aiming to explore the feasibility of architectures composed of multiple quantum processors (Qcores) that allow to scale up quantum computing systems. This is enabled by networks-in-a-package with a dual character that includes a quantum-coherent link for quantum information transfers coexisting with a cryogenic wireless communication network for exchanging classical data and synchronization.

 
<br/><br/>
### <a name="wiplash"></a> WiPLASH: Architecting More than Moore - Wireless Plasticity for Massive Heterogeneous Computer Architectures
- **Website:** [www.wiplash.eu](https://www.wiplash.eu)
- **Project Type:** H2020 FET-OPEN
- **Funding:** 2.9 M€
- **Duration:** 2019-2023
- **Media coverage:**
     - [ENG] [UPC News](https://barcelonatech-upc.eu/en/press-room/news/the-upc-leads-a-project-to-develop-faster-lower-power-processors-for-artificial-intelligence)
     - [ESP] [Computing.es](https://www.computing.es/movilidad/noticias/1121206046501/upc-investiga-desarrollar-procesadores-ia-mas-sostenibles.1.html)

<p align="center">
<iframe width="80%" height="315" src="https://www.youtube.com/embed/_78MthY30nM" frameborder="0" allowfullscreen></iframe>
</p>
	
    
The main design principles in computer architecture have shifted from a monolithic scaling-driven approach towards an emergence of heterogeneous architectures that tightly co-integrate multiple specialized computing and memory units. This is motivated by the urgent need of very high parallelism and by energy constraints. Heterogeneous hardware specialization requires interconnection mechanisms that integrate the architecture. State-of-the-art approaches are 3D stacking and 2D architectures complemented with a Network-on-Chip (NoC) to interconnect the components. However, such interconnects are fundamentally monolithic and rigid, and are unable to provide the efficiency and architectural flexibility required by current and future key ICT applications. The main challenge is to introduce diversification and specialization in heterogeneous processor architectures while ensuring their generality and scalability.

In order to achieve this, the WiPLASH project aims to pioneer an on-chip wireless communication plane able to provide architectural plasticity, reconfigurability and adaptation to the application requirements with near-ASIC efficiency but without loss of generality. For this, the WiPLASH consortium will provide solid experimental foundations of the key enablers of on-chip wireless communication at the functional unit level as well as their technological and architectural integration. The main goals are to: (i) Prototype a miniaturized and tunable graphene antenna in the terahertz band, (ii) Co-integrate graphene RF components with submillimeter-wave transceivers, and (iii) demonstrate low-power reconfigurable wireless chip-scale networks.

The culminating goal is to demonstrate that the wireless plane offers the plasticity required by future computing platforms by improving at least one key application (mainly biologically-plausible deep learning architectures) by 10× in terms of execution speed and energy-delay product over a state-of-the-art baseline.

 
<br/><br/>
### <a name="gnn"></a> IGNNSPECTOR: Graph-Driven Acceleration of Graph Neural Networks
- **Website:** [NEC Labs Europe](https://www.neclab.eu/careers/nec-student-research-fellowship-program#fellow-985)
- **Project Type:** NEC Labs Europe - Student Research Fellowship
- **Funding:** 75 K€
- **Duration:** 2021-2022
- **Media coverage:**
     - [ENG] [NEC Laboratories Europe](https://www.neclab.eu/blog/nec-student-research-fellowship-interview-with-dr-sergi-abadal)
     
Graph Neural Networks (GNNs) are gaining momentum due to their ability to model and learn from graph-structured data, with profound implications in areas like computer networks, natural language processing, quantum chemistry, or bioscience. However, computing GNNs efficiently is an open problem due to their unique characteristics, i.e. alternating dense and massively sparse phases, dependence on an input graph, and potential need for scaling to large graphs. These render GPU/TPU and DNN accelerators inefficient. This proect aims to tackle this open problem via software acceleration, although the solution can also help speed up hardware-software co-designed solutions. In particular, we want to demonstrate that both the optimal dataflows and software acceleration techniques for GNN computation depend on the GNN algorithm and the graph connectivity, and that optimality may change across partitions of the same graph. Then, the goal is to develop a tool, which we call iGNNspector, that streamlines the training/inference of a GNN based on this knowledge. In more detail, iGNNspector will profile a wide variety of graph datasets and analyze their performance for different GNN variants and frameworks/accelerators. These results will be used to derive a set of heuristics to guide partitioning, scheduling, and runtime for CPU/GPU platforms, and to determine the most appropriate dataflows for ASIC platforms.

 
 <br/><br/>
### <a name="visorsurf"></a> VISORSURF: A Hardware Platform for Software-driven Functional Metasurface
- **Website:** [www.visorsurf.eu](http://www.visorsurf.eu)
- **Project Type:** H2020 FET-OPEN
- **Funding:** 5 M€
- **Duration:** 2017-2021
- **Media coverage:**
     - [ENG] [PublicNow](http://www.publicnow.com/view/B0BA04ADDCC57999D9F4C16BFC8D6F405A889DC6?2017-07-21-10:00:11+01:00-xxx1004) \| [UPC News](http://www.upc.edu/saladepremsa/al-dia/mes-noticies/scientists-from-the-upc-investigate-reconfigurable-and-programmable-metamaterials) \| [The Register](https://www.theregister.com/2020/06/01/irs_wireless_jamming/)
     - [ESP] [La Vanguardia](http://www.lavanguardia.com/vida/20170710/424038208290/cientificos-de-la-upc-investigan-materiales-reconfigurables-y-programables.html) \| [El Periódico](http://www.elperiodico.com/es/sociedad/20170710/cientificos-de-la-upc-investigan-materiales-reconfigurables-y-programables-6158737)

Metasurfaces, thin film planar, artificial structures, have recently enabled the realization of novel electromagnetic and optical components with engineered and even unnatural functionalities. These include electromagnetic invisibility of objects (cloaking), total radiation absorption, filtering and steering of light and sound, as well as ultra-efficient, miniaturized antennas for sensors and implantable communication devices. Nonetheless, metasurfaces are presently non-adaptive and non-reusable, restricting their applicability to a single functionality per structure (e.g., steering light towards a fixed direction) and to static structures only.

Moreover, designing a metasurface remains a task for specialized researchers, limiting their accessibility from the broad engineering field. VISORSURF proposes a hardware platform-the HyperSurface-that can host metasurface functionalities described in software. The HyperSurface essentially merges existing metasurfaces with nanonetworks, acting as a reconfigurable (globally, locally, upon request or depending on the environment) metasurface, whose properties can be changed via a software interface. This control is achieved by a network of miniaturized controllers, incorporated into the structure of the metasurface. The controllers receive programmatic directives and perform simple alterations on the metasur-face structure, adjusting its electromagnetic behavior. The required end-functionality is described in well-defined, reusable software modules, adding the potential for hosting multiple functionalities concurrently and adaptively. VISORSURF will study in depth the novel and unexplored theoretical capabilities of the HyperSurface concept.

 
<br/><br/>
### <a name="tugraco"></a> TUGRACO: Towards Ubiquitous GRAphene based RF COmmunications – demonstrating and understanding graphene based plasmonic THz antenna potential and limitations
- **Website:** [N3Cat Projects](http://www.n3cat.upc.edu/projects/tugraco)
- **Project Type:** H2020 FLAG-ERA - Graphene Flagship
- **Funding:** 250 K€
- **Duration:** 2016-2019

Nanotechnology is increasingly providing a plethora of new tools to design and manufacture miniaturized devices such as ubiquitous sensors, wearable electronics or pervasive computing systems. Such devices require wireless communications for information sharing and coordination. Unfortunately, reducing the size (and concomitantly cost) of such devices is severely restricted by the dimensions of metallic antennas. Graphene offers a radical alternative to downscale antennas by orders of magnitude thanks to its special dispersion relation and its ability to support surface-plasmon polaritons (SPP) in the terahertz frequency band. Indeed, a graphene RF plasmonic micro-antenna with lateral dimensions of a few micrometers is predicted to resonate in the terahertz band (0.3-10 THz) at a frequency up to two orders of magnitude lower and with higher radiation efficiency with respect to metallic counterparts. In consequence, graphene micro-antennas provide a huge integration potential for future miniaturized wireless systems and represents an enabling technology for the future dominant ICT applications envisioned by e.g. Internet of Things.


<br/><br/>
### <a name="gwc"></a> GWC: Graphene-enabled Wireless Communications
- **Website:** [N3Cat Projects](http://www.n3cat.upc.edu/projects/gwc)
- **Project Type:** SAMSUNG Global Research Outreach \| INTEL Doctoral Student Honor Programme
- **Funding:** 150 K€
- **Duration:** 2012-2016
- **Media Coverage:**
    - [ENG] [ExtremeTech](http://www.extremetech.com/extreme/149172-samsung-funds-graphene-antenna-project-for-wireless-ultra-fast-intra-chip-links) \| [Alpha Galileo](http://www.alphagalileo.es/ViewItem.aspx?ItemId=128752&CultureCode=en) \| [Graphene Tracker](http://www.graphenetracker.com/samsung-backs-project-to-develop-graphene-based-micro-antennas/)
    - [ESP] [ThinkBig (Telefonica)](http://blogthinkbig.com/microantenas-de-grafeno-capacidad-computacional/) \| [Europa Press](http://www.europapress.es/portaltic/empresas/noticia-samsung-financia-120000-dolares-proyecto-liderado-upc-desarrollar-microantenas-20130218182118.html) \| [La Razón](http://www.larazon.es/detalle_normal/noticias/1208199/samsung-financia-un-programa-espanol-de-microa#.UhifKBunqaI)
    - [CAT] `[UPC](http://www.upc.edu/saladepremsa/al-dia/mes-noticies/samsung-aposta-per-un-projecte-liderat-per-la-upc-per-desenvolupar-microantenes-basades-en-el-grafe) \| [Ràdio4 (RTVE - Local Radio Station)](http://www.rtve.es/alacarta/audios/lobservatori/lobservatori-2-marc-2013/1701205/)


Graphene, a flat monoatomic layer of carbon atoms tightly packed in a two-dimensional honeycomb lattice, has recently attracted the attention of the research community due to its novel mechanical, thermal, chemical, electronic and optical properties. Since its first isolation by the Nobel laureates Andre Geim and Konstantin Novoselov back in 2004, graphene has given rise to a plethora of potential applications in diverse fields, attracting, as a result, multimillion dollar research funding.

A remarkably promising application of graphene is that of Graphene-enabled Wireless Communications (GWC). GWC advocate for the use of graphene-based plasmonic antennas -graphennas, see Fig. 1- whose plasmonic effects allow them to radiate EM waves in the terahertz band (0.1 – 10 THz). Moreover, preliminary results sustain that this frequency band is up to two orders of magnitude below the optical frequencies at which metallic antennas of the same size resonate, thereby enhancing the transmission range of graphene-based antennas and lowering the requirements on the corresponding transceivers. In short, graphene enables the implementation of nano-antennas just a few micrometers in size that are not doable with traditional metallic materials.

Thanks to both the reduced size and unique radiation capabilities of graphennas, GWC may represent a breakthrough in the ultra-short range communications research area. In this project we will study the application of GWC within the scenario of off-chip communication, which includes communication between different chips of a given device, e.g. a cell phone. The advantages of the resulting Off-Chip Graphene-based Wireless Communication are manifold but can be summarized in two points. On the one hand, the potential of GWC to radiate in the terahertz band provides a huge transmission bandwidth, allowing not only the transmission of information at extremely high speeds but also the design of ultra-low-power and low-complexity schemes. On the other hand, the reduced size of such antennas results in a smaller area overhead than with conventional metallic antennas, factor that may be critical in area constrained scenarios. Moreover, improving the directivity values by means of graphene-based antenna arrays could be possible due to the aforementioned reduced size.

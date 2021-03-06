<!---
Fri 01 Jul 2022 01:44:28 PM UTC
Portfolio Website - m0ham3d.com
--->

<p align="center">
<a href="https://quran.com/51/47" target="blank">
<img src="./infogfx/q5147.png" width="500">
</p>

<p align="center">
<a href="https://twitter.com/m0ham3dxx" target="_blank">
<img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fm0ham3dx%2FFreeQuantumComputingResources&count_bg=%234C0027&title_bg=%23000C66&icon=youtubemusic.svg&icon_color=%23FFE103&title=Lurkers&edge_flat=false"/>
<a href="./LICENSE.MD">
<img src="https://img.shields.io/badge/license-custom-success">
<img src="https://img.shields.io/badge/Progress-WIP-red">
</a>
</a>
</p>
<p align="center">
<a href="https://twitter.com/m0ham3dxx" target="_blank">
<img src="./img/qe.gif" alt="Quantum Entanglement">
<p align="center">
<a href="./infogfx/QEE.jpg" target="_blank">
<i> Illustration of Quantum Entanglement - also referred to as "Spooky Action at a distance". Click me for an illustrative explanation. </i> 
</a>
</p>
</a>
</p>
<p align="center">
<a href="https://twitter.com/m0ham3dxx" target="_blank">
</a>
</p>

----

<h1> TOC </h1>

1. [ℹ️ REPO DESCRIPTION](#ℹ️-repo-description)
2. [🎓LEARNING RESOURCES](#learning-resources)
   1. [Quantum Theory](#quantum-theory)
   2. [Quantum Computing](#quantum-computing)
3. [🎛️ FUNDAMENTAL PRINCIPLES OF QC](#️-fundamental-principles-of-qc)
   1. [Definition of `Quantum`](#definition-of-quantum)
   2. [Quantum Physics](#quantum-physics)
      1. [**Particle Wave Duality**](#particle-wave-duality)
      2. [**Measurement Problem**](#measurement-problem)
      3. [**Superposition**](#superposition)
         1. [Quantum Spin](#quantum-spin)
      4. [**Quantum State**](#quantum-state)
      5. [**👻Entanglement** (also referred to as Spooky Action)](#entanglement-also-referred-to-as-spooky-action)
      6. [**Quantum Tunneling**](#quantum-tunneling)
      7. [**Heisenberg Uncertainity Principle**](#heisenberg-uncertainity-principle)
      8. [**Energy Quantization**](#energy-quantization)
   3. [Standard Model of Particle Physics](#standard-model-of-particle-physics)
      1. [Higgs Boson Particle](#higgs-boson-particle)
   4. [Quantum Particles](#quantum-particles)
   5. [Quantum Mechanics](#quantum-mechanics)
      1. [Difference between QP and QM](#difference-between-qp-and-qm)
      2. [Eigen Spaces](#eigen-spaces)
      3. [Wave Functions](#wave-functions)
4. [🐱‍💻 QUANTUM Computing (FINALLY 🙃)](#-quantum-computing-finally-)
5. [🔎 REFERENCES](#-references)
6. [📒 GLOSSARY](#-glossary)
7. [🎓 CITATION](#-citation)


----

# ℹ️ REPO DESCRIPTION

This repository contains the following information regarding $Quantum \ Computing$ .

```mermaid
graph TD
    A[Quantum<br>Computing<br>Primer<br>] --> A1[Learning<br>Resources]
    A --> |Low<br>Math<br>Proofs|A2[Quantum<br>Theory]
    A --> A3[Quantum<br>Computing]

    %% A1 Boxes 
    A1 --> A11[Quantum<br>Physics+Mechanics]
    A1 --> A12[Quantum<br>Computing]

    %% A2 Boxes 
    A2 --> A21[Brief<br>Quantum<br>Physics]
    A2 --> A22[Brief<br>Quantum<br>Mechanics]

    %% A3 Boxes 
    A3[Quantum<br>Computing] --> A31[Overview]
    A3 --> A32[QC Tools]
    A32 --> A321[Packages<br>Tools<br>Test<br> maybe...]
```

> ⚠️ Information contained is subject to my own interpretation, which has been kept to a minimum. The bulk of the information has been referenced. I cannot guarantee 100% accuracy😟.

> 👉 Many concepts contained are an oversimplification of very deep physics and quantum physics/mechanics. Where examples of the application of equations are lacking. I may come back to that at a later time🙄.

> 🥅 The goal is to understand enough to start experimenting with  the various quantum cloud services, open source packages and find some real world high impact application 🎪. 

<p align = "center">
<a href="https://twitter.com/m0ham3dxx" target="_blank">
<img src = "./infogfx/apfi.gif" width="100">
</a>
</p>

<p align = "center">
I have also added <b>🍌TLDR</b> block to each section, for fast understanding 😉.
</p>

# 🎓LEARNING RESOURCES 

These are going to links to resources which have simplified explanations, that are not math heavy. With a greater focus on videos rather than papers. Note all of these sources have been studied for the content in this repository.

## Quantum Theory 

N | Source | Url | Synopsis
|:--|:--:|:--:|:--:|
1 | ▶️Youtube | [▶️ Quantum Physics made simple - Wave-Particle Duality Animation](https://youtu.be/Xmq_FJd1oUQ) |  Animation describing the dual behavior of a particle as both a wave and a particle
2 | ▶️Youtube | [▶️ Physics - Chapt. 66 Quantum Mechanics (1 of 9) What Is Quantum Mechanics?](https://youtu.be/j-HdVUTemO0) | - Physics lecture on understanding *Quantum Mechanics*, thisi branch exists because standard laws of physics are modified at a subatomic level
3 | ▶️Youtube | [▶️ Quantum Computers, Explained With Quantum Physics](https://youtu.be/jHoEjvuPoB8) |  Understanding quantum computing in light of quantum physics concepts. *Qubits* the fundamenetal processing unit of QC
4 | 📷Slides | [📷 Quantum Physics Infographics](https://slidesgo.com/theme/quantum-physics-infographics) | Simplified understanding of QP by comparison to the macro world
5 | ▶️Youtube | [▶️ If You Don't Understand Quantum Physics, Try This!](https://youtu.be/Usu9xZfabPM) | Source video for *Fig 3: Components of QP*
6 | ▶️Youtube | [▶️ quantum superposition of states and decoherence](https://youtu.be/7B1llCxVdkE) | Animation superposition of quantum states of an electron and decoherence (time taken for the superposition to disappear)
7 | 📃Paper | [📃 Quantum States & Superposition](https://www.southampton.ac.uk/~doug/quantum_physics/superposition.pdf) | Mathematical discussion of Quantum States & Superposition
8 | ▶️Youtube | [▶️quantum tunnel effect and tunneling microscope](https://youtu.be/K64Tv2mK5h4) | Animation quantum teunneling effect, ie., quantum particles can pass through objects
9 | ▶️Youtube | [▶️ Quantum Tunneling](https://youtu.be/RF7dDt3tVmI) | Animation style explanation of a wave functions
10 | ▶️Youtube | [▶️ Breaking The Heisenberg Uncertainty Principle](https://youtu.be/uZDhCW-PTRM) | Short documentary on the uncertainity principle
11 | 📰Article | [📰 What Is Planck's Constant, and Why Does the Universe Depend on It?](https://science.howstuffworks.com/dictionary/physics-terms/plancks-constant.htm) | Article discussing the origins and applications of the planc's constant in modern media
12 | ▶️Youtube | [▶️ Eigenvalues and eigenstates in quantum mechanics](https://youtu.be/p1zg-c1nvwQ) | Discussion of mathematical operators that enable physical observables in quantum mechanics
13 | ▶️Youtube | [▶️ Quantum Entanglement: Spooky Action at a Distance](https://youtu.be/JFozGfxmi8A) | Explanation of Quantum Entanglement from [FermiLab](https://www.fnal.gov/) 
14 | ▶️Youtube | [▶️ The Most Successful Scientific Theory Ever: The Standard Model](https://youtu.be/Unl1jXFnzgo) | Description of the standard model of particle physics - which are the fundamental building blocks of everything in the universe
15 | ▶️Youtube | [▶️ What Is the Higgs Boson? Trapping The God Particle](https://youtu.be/hyIbzN4X6hE) | General video about dark energy, cosmic radiation and particle accelaration experiments
16 | ▶️Youtube | [▶️ The Higgs Discovery Explained - Ep. 1/3 - CERN](https://youtu.be/so2nCu2Jkbc) | Story and description of the discovery of he Higgs-Boson  from [CERN](https://home.cern/) the laboaratory that disovered the particle
17 | ▶️Youtube | [▶️ How the Large Hadron Collider Works in 10 Minutes](https://youtu.be/FuWNp5dmgzo) | Description of the LHC - The Large Hadron Collider at [CERN](https://home.cern/)
18 | ▶️Youtube | [▶️ What is a Higgs Boson?](https://youtu.be/RIg1Vh7uPyw) | Simplified explanation of the *Higgs-Boson* particle from [Fermilab](https://www.fnal.gov/)
19 | ▶️Youtube | [▶️How the Higgs Mechanism Give Things Mass](https://youtu.be/G0Q4UAiKacw) | Simplified explanation of mechanism of higgs boson imparting mass to a particle
20 | ▶️Youtube | [▶️What is Quantum Spin?](https://youtu.be/sB1EPGmpzyg) | Explanation of the SPIN or Intrinsic Angular Momentum, which can't be described as a spinning top
21 | ▶️Youtube | [▶️The Bloch Sphere](https://youtu.be/Ka4eF4zL3-0) | Visualizing a quantum computing vectors space referred to as Bloch Sphere which is a Qubit.
22 | 
23 |

## Quantum Computing


> 🍌 TLDR - Above media is more entertaining than reading the following text

# 🎛️ FUNDAMENTAL PRINCIPLES OF QC

To understand QC we have first to have understand important concepts of quantum physics. The *knowlege tree* looks like the following - 

```mermaid
flowchart TD
    A[Quantum\nComputing] --> B(Define\nQuantum)
    A --> C(Quantum<br>Physics)
    C --> C1(Quantum<br>Mechanics)
    A --> D(Standard<br>Model<br>Particle<br>Physics)
    D --> D1(Quantum<br>Particles)
    C <--> D1
```
<p align="center">
<i>Fig1: QC knowledge tree</i>
<p> 

## Definition of `Quantum`

$Quantum$ (*Singular*) or $Quanta$ (*Plural*) [defined](http://physicsbuzz.physicscentral.com/2018/02/just-what-is-quantum.html) as the smallest and simplest unit of something. In the case of Quantum Mechanics / Quantum Physics, it refers to a [sub atomic particle](https://www.livescience.com/mystery-of-proton-neutron-behavior-in-nucleus.html), such as [electrons (e<SUP>-</SUP>), protons (p<sup>+</sup>), neutrons (n<sup>0</sup>)](https://www.livescience.com/65427-fundamental-elementary-particles.html). 

> 🍌 TLDR - Quantum means the smallest and simplest unit of thing

## Quantum Physics 

[Quantum physics](https://scienceexchange.caltech.edu/topics/quantum-science-explained/quantum-physics) is the study of matter and energy at the most fundamental level. It aims to uncover the properties and behaviors of the very building blocks of nature.

<p align="center">
<a href="https://bigthink.com/hard-science/the-physics-of-everything-in-one-neat-map/" target="_blank">
<img src="./infogfx/phyla.png">
</a>
<i>Fig 2: Current landscape of understanding of physics</i>
</p>

Fig 2 - Illustrates the evolution of our understanding of physics. Until more recent times due to the advancement of experimental technologies, *Quantum Theories* are only now being observed & proved. Please note that their are active efforts of utilizing the Quantum Phenomenon for computing purposes, but our general understanding of it is quite poor.

```mermaid
flowchart TD
    A[Quantum<br>Physics] -->|Objects<br>described as<br>|A1(Wave<br>Functions)
    
    A1 -->|Measuring|B
    subgraph B [Particles Seen]
        direction LR
        B1(Particle Wave<br>Duality) o--o B2(Measurement<br>Problem)
    end

    A1 -->|Consequence|C 
    subgraph C [Quantum Phenomenon]
        direction LR
        C1[Superposition] o--o C11[Entanglement]
        C11 o--o C2
        C2[Quantum\nTunneling] o--oC3[Heisenberg<br>Uncertainity<br>Principle]    
        C3 o--o C4[Energy<br>Quantization]
    end
```
<p align="center">
<i>Fig 3: Components of QP</i>
<p>

### [**Particle Wave Duality**](https://physicsworld.com/a/wave-particle-duality-quantified-for-the-first-time/) 
[![](./infogfx/pawd.png)](https://www.electrical4u.com/wave-particle-duality/)
<p align="center">
<i>Fig 4: Wave Particle Duality</i>
<p>
One of the most counterintuitive concepts in physics – the idea that quantum objects are complementary, behaving like waves in some situations and like particles in others.
   
These [particle waves](http://electron6.phys.utk.edu/phys250/modules/module%202/matter_waves.htm) are referred to as *matter waves*, [Luis de Broglie](https://www.spaceandmotion.com/Physics-Louis-de-Broglie.htm) first proposed that all matter has a *wave function* associated with it. These matter waves are a central part of the theory of $Quantum$ $Mechanics$. The *wavelengths* ($\lambda$) of these particles can be calculated by the following equation by *de Broglie* , which is referred to as *de Broglie's* equation.

😄😊🙂😐😟😫😭

$$🧮de \ Broglie's \ Equation$$

$$\lambda =  \frac{h}{mv}$$

$$\lambda=wavelength \ matterwave$$ 

$$h=planck's \ constant$$ 

$$m = particle \ mass \ moving \ at \ velocity \ v$$

😭😫😟😐🙂😊😄

### **Measurement Problem**
[![](./infogfx/mepr.png)](http://www.quantumphysicslady.org/glossary/measurement-problem/)
<p align="center">
<i>Fig 5: QP Measurement Problem</i>
<p>

According to the [Copenhagen Interpretation](https://physicsworld.com/a/thirty-years-of-against-measurement/) (being debated), which states that [during measurement](https://plato.stanford.edu/entries/qm-copenhagen/), the observer gets a subjective perception of what is going on in the quantum space, which means that these particles exhibit the property of [*non-locality*](https://www.scientificamerican.com/article/how-einstein-revealed-the-universe-s-strange-nonlocality/). *Non-locality which basically means, no observed particles have an absolute location in space.* Sub atomic particles are expressed as [wave functions](https://www.quantumphysicslady.org/glossary/wave-function/) ($ \Psi $) ie., only an approxmation of its actual location is known based on mathematical probabilities and the exact location of the particle is unknown.

The **Measurement Problem** states that these wave functions abruptly collapse into a particle in a point of space in time during observation, whose beahvior is unknown.

### **Superposition**

Superposition | Decoherence 
|:--:|:--:|
[![](./infogfx/QSP1.png)](https://youtu.be/7B1llCxVdkE) | [![](./infogfx/QSP2.png)](https://youtu.be/7B1llCxVdkE)
<p align="center">
<i>Fig 6: Quantum Superposition & Decoherence</i>
<p>

*Superposition* or *Quantum Superposition* is defined as the ability of a sub atomic particle (such as an electron) to be in [multiple quantum states](https://jqi.umd.edu/glossary/quantum-superposition) all at the same time, but when observed only has one state. In the case of an electron which gets excited (jumps to a higher energy state) in the presence of electro magnetic radiation (e.g Magnetic Field), it exists in both a high energy state and a low energy state at the same time. These are also referred to as [*SPIN*](https://www.space.com/39152-weird-quantum-property-of-spin.html)(also referred to as ([angular momentum](https://cronodon.com/Atomic/quantum_angular_momentum.html)) This is deduced from the wave patterns during its observation. An important term to also know at this point is *decoherence* which is when superposition can no longer be measured.

[*Superposition Principle*](http://physics.gmu.edu/~dmaria/590%20Web%20Page/public_html/qm_topics/superposition/superposition.html)

This principle states that a system (such as a group of quantum particles) exist in all *possible states at the same time*, only after measurement it falls to one of the *states* that form the superposition. This destroys its original configuration

The superposition principle is the idea that a system is in all possible states at the same time, until it is measured. After measurement it then falls to one of the basis states that form the superposition, thus destroying the original configuration. The superposition principle explains the "quantum weirdness" observed with many experiments.

Superposition principle equation states that a *statefunction*($\Psi$) can be expanded as a linear combination of the normalized [*eigenstates*](https://web.physics.wustl.edu/alford/physics/essentials.pdf) ($\phi _{n}$) of a particular *operator* that constitute a basis of the space occupied by ($\Psi$). For the discrete case

😄😊🙂😐😟😫😭

$$🧮Superposition \ Principle \ - Discrete  \ Case$$

$$|\Psi\rangle=\sum_{n=1}^{\infty}|b_{n}\varphi_{n}\rangle$$

$$where \ the \ coefficients(b_{n}) = functions \ of \ time(t) and \ given  \ by : $$ 

$$ b_{n}=\langle\varphi_{n}|\Psi\rangle $$

$$ which \ is \ the  \ projetion  \ of (\Psi) \ onto \ the  \ \textbf{eigenvector}(\varphi_{n})$$

😭😫😟😐🙂😊😄

#### Quantum Spin

Pics | Pics 
|:--:|:--:|
[![](./infogfx/Qusp.jpg)](https://cronodon.com/Atomic/quantum_angular_momentum.html) *Fig 6.1: Spin or angular momentum of quantum particles*  | [![](./infogfx/smspins.jpg)](http://animatedphysics.com/insights/particles-of-the-standard-model/) *Fig 6.2: Spin or other particles of the Standard Model*

Amongst the poperties of quantum particles one of them is referred to as [*spin* or *intrinsic angular momentum*](https://www.scientificamerican.com/article/what-exactly-is-the-spin/). This property although referred to as *spin* is not [actually spinning like a top](https://www.forbes.com/sites/startswithabang/2017/04/19/why-does-the-proton-spin-physics-holds-a-surprising-answer/?sh=2f1be3e52c3a), but this property describes its behavior in the presence of an electro-magnetic field [experimentally](https://chem.libretexts.org/Courses/Pacific_Union_College/Quantum_Chemistry/14%3A_Nuclear_Magnetic_Resonance_Spectroscopy/14.01%3A_Nuclei_Have_Intrinsic_Spin_Angular_Momenta). This property is observed but not understood and has no likeness in classical physics, which is broadly referred to as $Quantum \ Weirdness$ ([referring to our inability to comprehend quantum behavior even though it is being observed](https://physics.aps.org/articles/v15/11)). 
1. Fig 6.1 - Describes a simplified view of the *spin* in the presence of an electro-magnetic field. For sake of simoplicity it is referred to as spin-up($s=+\frac{1}{2}$) or spin-down($s=-\frac{1}{2}$), these have been observed experimentally when the stream of particles [group themselves](https://plato.stanford.edu/entries/physics-experiment/app5.html) in the presence of an electro-magnetic field. 
2. Fig 6.2 - Describes these spins in the observed and hypothesized particles of the [Standard Model of Particle Physics](#standard-model-of-particle-physics). 

### [**Quantum State**](https://www2.ph.ed.ac.uk/~ldeldebb/docs/QM/lect1.pdf) 

😄😊🙂😐😟😫😭

Fundamental Law of Quantum Mechanics

$$🧮Quantum \ State \ Equation $$

$$ Quantum\ State\sim \Psi(x,t) $$

$$ \Psi\ = \ complex function $$

$$ x = coordinates $$

$$ t = time $$

😭😫😟😐🙂😊😄

Where the function $\Psi$ is the *complex function* which describes *wave-particle duality* (Fig 4) which depends on the coordinate($x$) and time($t$). This wave function indicates that the behavior of a quantum object is [probabilistic](https://quantumatlas.umd.edu/entry/quantum-states/), this means that the wave function encodes all the probabilistic outcomes of the measurement and this *quantum state* equation captures the full range of these possible measurement outcomes.   

[![](./infogfx/wafu.gif)](https://youtu.be/RF7dDt3tVmI)
<p align="center">
<i>Fig 6.1: 3d Illustration of a wave function</i>
<p>

### **👻Entanglement** (also referred to as Spooky Action)

[![](./infogfx/QEN.png)](https://www.nasa.gov/feature/jpl/particles-in-love-quantum-mechanics-explored-in-new-study)
<p align="center">
<i>Fig 7: Quantum Entanglement or Spooky Action</i>
<p>

In [Quantum Theory](https://blogs.scientificamerican.com/observations/what-does-quantum-theory-actually-tell-us-about-reality/),  [Quantum Entanglement is most bizzare and mysterious properties of quantum particles](https://www.livescience.com/what-is-quantum-entanglement.html), which states that two subatomic particles can be intimately linked to each other even if seperated by [billions of years light years in space](https://www.space.com/31933-quantum-entanglement-action-at-a-distance.html) ie., any change induced in one particle will affect the other. The mechanics of this behavior is unknown.

 These two particles share a common unified [quantum state](https://www2.ph.ed.ac.uk/~ldeldebb/docs/QM/lect1.pdf), such that any observation of one of these particles will provide information about the other entangled particles. And any action to one of these particles will invariably impact the others in the entangled system. 


### **Quantum Tunneling**   

[![](./infogfx/QuTu.gif)](https://youtu.be/K64Tv2mK5h4)
<p align="center">
<i>Fig 8: Quantum Tunneling</i>
<p>

[Quantum Tunnelling is a phenomenen](http://abyss.uoregon.edu/~js/glossary/quantum_tunneling.html) which has no counterpart in classical physics, it states that particles can [penetrate a potential energy barrier](https://opentextbc.ca/universityphysicsv3openstax/chapter/the-quantum-tunneling-of-particles-through-potential-barriers/) with a height greater than the total energy of particles. In simple terms quantum tunnelling is where an atom or a [subatomic particle can appear on the opposite of a barrier](https://www.livescience.com/quantum-tunneling-observed-and-measured.html) that should be impossible for the particle to penetrate. This is an important property in understanding [energy production models of the sun.](https://www.academia.edu/11446310/Quantum_tunnelling_in_the_sun) 

### **Heisenberg Uncertainity Principle**  

[![](./infogfx/hei.png)](https://physicscatalyst.com/graduation/heisenberg-uncertainty-principle/)
<p align="center">
<i>Fig 9: Light microscopy for measuring speed and momentum </i>
<p>

A principle of the quantum realm referring to the measurement of a particle. As we have discussed so far, that a sub atomic particle displays both a wave and particle like behavior, measuring both the *position* and *speed* becomes a challenge. The Heisenberg Uncertainity Principle states that it is [impossible to know exactly both the position & speed of a particle](https://scienceexchange.caltech.edu/topics/quantum-science-explained/uncertainty-principle). And the more effort is done to measure these properties, the less accurate the results. 

In order to see a particle, light has to reflect of the particle and enter our viewing appartus. But the problem occurs when the photons emitted from the device that tries to measure the particle, these photons(light) transfer energy (momentum in the form of Kinetic energy) when striking the particle. This changes the momentum and speed of the particle under observation. So this light when reflected of the particle enters the viewing apparatus is already carrying inaccurate and altered information. 

[The Heisenberg Uncertaining Principle](https://openstax.org/books/university-physics-volume-3/pages/7-2-the-heisenberg-uncertainty-principle) equation is the product of the *uncertainity in position* ($\Delta x$) of a particle and the *uncertainity in its momentum* ($\Delta p$) , which can never be less than one half  ($1\over2$)  of the planck constant($h$).

😄😊🙂😐😟😫😭

$$🧮Heisenberg \ Uncertainity \ Principle \ Equation $$

$$\Delta x . \Delta p \ge \frac{h}{2}$$

$$\Delta x=Change \ in \ position $$

$$\Delta p=Change \ in \ momentum $$

$$h=planck \ constant$$

😭😫😟😐🙂😊😄
### **Energy Quantization** 

[![](./infogfx/enqu.png)](https://slideplayer.com/slide/10879856/)
<p align="center">
<i>Fig 10: Quantization of energy </i>
<p>

[Energy is quantized in some systems](https://opentextbc.ca/openstaxcollegephysics/chapter/quantization-of-energy/), meaning that the system can have only certain energies and not a continuum of energies, unlike the classical case. This would be like having only certain speeds at which a car can travel because its kinetic energy can have only certain values. We also find that some forms of energy transfer take place with discrete lumps of energy. While most of us are familiar with the quantization of matter into lumps called atoms, molecules, and the like, we are less aware that energy, too, can be quantized. Some of the earliest clues about the necessity of quantum mechanics over classical physics came from the quantization of energy. 

[Max Planc](https://www.nobelprize.org/prizes/physics/1918/planck/biographical/) used that idea that atoms and molecules (quantum realm) act like oscillators to absorb and emit radiation. ie., the energy within these particles are not constant, but due to constant absorbtion and emission the energy is *quantized*. He is also credited for [discovering constant proprtionality](https://illuminating.science/what-is-plancks-constant/) which is instrumental in calculation of physical quantities in the quantum mechanics. This proptionality is referred to as the **planc's constant**.

Planc's postulate for the energy state ($E$ $_{n}$) of a quantum mechanical simple harmonic oscillator with the following equation

😄😊🙂😐😟😫😭

$$ 🧮 Planck's \ Postulate - Quantum \ Mechanical \ Simple \ Harmonic \ Oscillator  $$

$$ E_{n}=(n+\frac{1}{2})hv $$

$$ E_{n} = Energy \ State $$

$$ n = non-negative \ integer \ (1,2,3...) $$ 

$$ v = frequency \ of \ oscillations $$

$$ h(planc's \ constant) = 6.62610^{-34}J.s $$

😭😫😟😐🙂😊😄

> 🍌 TLDR - The above are the most basic building blocks of Quantum Physics. These properties are exploited in Quantum Computing


## Standard Model of Particle Physics

The following diagram is an illustration of the [Standard Model](https://simple.wikipedia.org/wiki/Standard_Model) of elementary particles as described by the [particle theory in physics.](https://www.le.ac.uk/se/centres/sci/selfstudy/particle01.html)

[![](./infogfx/Particles.jpg)](https://www.livescience.com/60900-tetraquark-particle-exists.html)
<p align="center">
<i>Fig 11: Standard Model of Particle Physics - Brief </i>
<p>

Pics | Pics 
|:--:|:--:|
[![](./infogfx/SMP.jpg)](https://twitter.com/DominicWalliman/status/1370044170274938886?s=20&t=_6K3BbsgDfXVIvUJf1L1Mg) *Fig 11.1: Standard Model of Particle Physics - Particles, Conservation Laws, Standard Model Interactions, Force Interactions* | [![](./infogfx/smce.jpg)](https://mediaarchive.cern.ch/MediaArchive/Photo/Public/1995/9501005/9501005/9501005-A4-at-144-dpi.jpg) *Fig 11.2: Standard Model Brief from [CERN  - The European Organization of Nuclear Research](https://home.cern/)*


[The Standard Model of Particle Physics](https://www.energy.gov/science/doe-explainsthe-standard-model-particle-physics) is scientists current best theory to describe the most basic building blocks of the universe. It explains how particles called quarks (which make up protons and neutrons) and leptons (which include electrons) make up all known matter. It also explains how force carrying particles, which belong to a broader group of bosons, influence the quarks and leptons. This standard model is represented by the [*Standard Model Equation*](https://www.symmetrymagazine.org/article/the-deconstructed-standard-model-equation)

[![](./infogfx/smpg.gif)](https://youtu.be/Unl1jXFnzgo)
<p align="center">
<i>Fig 11.3: Brief explanation of the <u>Standard Model Equation</u> </i>
<p>


### Higgs Boson Particle

Pics | Pics 
|:--:|:--:|
[![](./infogfx/hb2.png)](https://www.home.cern/science/physics/standard-model) *Fig 11.3: Higgs Particle represenation in the Standard Model by CERN* | [![](./infogfx/hb1.png)](https://www.quantamagazine.org/a-new-map-of-the-standard-model-of-particle-physics-20201022/) *Fig 11.4: Higgs Particle relationship in the Standard Model*


In 2012 [CERN](https://home.cern/) - *The European Organization of Nuclear Research*. Discovered the [*Higgs-Boson Particle*](https://home.cern/science/physics/higgs-boson) (often referred to as Higgs - which was theorized by [Peter Higgs](https://www.nobelprize.org/prizes/physics/2013/higgs/facts/) ), during a particle collission experiment in the [*Large Hadronic Collide* (LHC)](https://home.cern/science/accelerators/large-hadron-collider) at CERN which is the worlds largest and most powerful [particle accelerator](https://opentextbc.ca/universityphysicsv3openstax/chapter/particle-accelerators-and-detectors/) capable of accelerating particles (protons p<sup>+</sup> to the speed of light ($c$) where ($C=3 \times\mathrm{10}_{}^{8} \ m/s$) in both clockwise and anticlockwise directions. These accelerated proton beams then collide at four different locations. The energy from these collissions get coverted into mass according to the [Mass Energy Equivalence Principle](https://energyeducation.ca/encyclopedia/Mass-energy_equivalence) ($E=MC^2$) 

 It was detected via statistical analysis of large amounts of data which was collected by the [ATLAS](https://home.cern/science/experiments/atlas) & [CMS](https://cms.cern/detector) detectors, after the collisions occur. 

Pics | Pics
|:--:|:--:|
[![](./infogfx/LHCMap.png)](https://cds.cern.ch/images/CERN-GRAPHICS-2022-001-1/file?size=large) *Fig: 11.5: Map of the LHC collider*  | [![](./infogfx/lhcgeo.png)](https://spectrum.ieee.org/analyzing-the-lhc-magnet-quenches) *Fig 11.5.1 : Geolocation of LHC collider tunnel, border of* [*switerland and france - **gooogle maps***](https://www.google.com/maps/d/viewer?mid=1tZYHxIanWV9iQDff6jWUHN21jmU&hl=en_US&ll=46.27092216959334%2C6.063294499999978&z=13). 
[![](infogfx/lhcdipolemap.gif)](https://cerncourier.com/wp-content/uploads/2006/10/CCEthe1_10-06.gif) *Fig 11.6: Components of the Dipole from 11.7* |  [![](./infogfx/LHCPIC1.jpg)](https://home.cern/resources/image/accelerators/lhc-images-gallery) <i> Fig: 11.7 A chain of LHC dipole magnets inside the tunnel </i>
[![](./infogfx/atlasdetector.png)](http://opendata.atlas.cern/release/2020/documentation/atlas/experiment.html) *Fig 11.8: Atlas Dector Schemaics* | [![](infogfx/cmsdetector.png)](https://cms.cern/detector) *Fig 11.9: CMS Dector Schemaics* 

**Characteristics of the Higgs ($H^0$) Particle**

Pics | Pics
|:--:|:--:|
[![](./infogfx/hig1g.png)](https://www.britannica.com/science/Higgs-boson#ref44596) *Fig 11.10:  Higgs Particle Generating Event in LHC* | [![](./infogfx/hig2d.png)](https://www.britannica.com/science/Higgs-boson#ref44596) *Fig 11.11: Higgs Particle generation diagram*

[![](./infogfx/higmech.png)](https://www.zmescience.com/science/higgs-boson-10-year/)
<p align="center">
<i> Fig 12: Higgs Mechanism also referred to as the Mexican Hat Potential is how particles acquire mass in the higgs-field </i>
</p>

1. It is the [fundamental particle](https://www.energy.gov/science/doe-explainsthe-higgs-boson) associated with the *higgs field*. Which gives mass to other particles. This field is also thought to [play a role in the big-bang](https://www.smithsonianmag.com/science-nature/how-the-higgs-boson-was-found-4723520/). The [higgs mechanism](https://www.fe.infn.it/~bettoni/particelle/Strong/HiggsMechanism.pdf) is how particles acquire mass. 
   1. This mechanism starts with the premise that the universe is filled with a **spin-zero field**. Then [guage bosons](https://www.chemeurope.com/en/encyclopedia/Gauge_boson.html) (are force carrier particles) & fermions interact with this field and acquire mass.   
   
2. It is  highly unstable particle that quicjly morphs into other particles, and is only [occassionally produced](https://www.quantamagazine.org/the-physics-still-hiding-in-the-higgs-boson-20190304/) in a particle collider.
   
4. It gets its own mass by interacting with the [higgs-field]((https://www.nature.com/articles/d41586-022-01834-5)). It is a $zero \ spin \ particle$ whose mass is $125\ GeV$ 



> 🍌 Every thing can be broken own into smaller units. The most commonly known unit is the *molecule*. *molecules* in turn are made of smaller particles, and so and so forth until we reach the limits of observation.

## Quantum Particles

All matter in the universe can be subdivided into two classes based on their *spin*.[There are two classes of quantum particles](https://www.sciencedirect.com/topics/mathematics/quantum-particle), those with a spin multiple of one-half, called fermions, and those with a spin multiple of one, called **bosons**. 

The spin quantum number of **fermions** can be ($s = +\frac{1}{2}$), ($s =-\frac{1}{2}$), or an odd multiple of ($s = ± \frac{1}{2}$). Electrons, protons, and neutrons are fermions. 

The spin quantum number of **bosons** can be ($s = +1$), ($s = −1$), ($s = 0$), or a multiple of ($s = ±1$).

```mermaid
flowchart LR
    A[Quantum<br>Particles] --> A1[Main Category <br> Fermions]
    A --> A2[Main Category<br>Bosons]
    A --> |Essentially<br>Fermions|A3[Hadrons <br> Combination of <br> Quarks & Antiquarks]

    %% Fermions 
    A1 --> |Held <br> together|Ab1[Gauge<br>Bosons <br> force carrier particles]

    %% Spin
    A1 --> |Spin|A11[Spin = multiples of '1/2']
    A2 --> |Spin|A21[Spin = multiples of '1']
    A3 --> |Spin|A31[Spin = 1/2 multiple of <br> h=h/2pi]

    %% Spin Number
    A11 --> |Spin<br>Quantum<br>Number| A111[s = '+1/2' <br> s = -1/2'<br> s = + or - 1/2]
    A21 --> |Spin<br>Quantum<br>Number| A211[s = +1 <br> s = -1 <br> s = 0 <br> multople of + or i]
    A31 --> A3111[Mesons]
    A31 --> A3111b[Baryons]
    A3111b --> A32[Nucleons]
    A3111b --> A33[Hyperons]

    %% Box Examples
    A111 --> a1x[Leptons, <br> Quarks, <br> Electrons, <br> Protons, <br> Neutrons]
    A211 --> a2x[Force Carrier Particles <br> Mesons]

    a1x --> a1x1[Including<br>Anti-Particles]
```

The [fundamental](https://particleadventure.org/fermibos.html) building blocks of the universe are $fermions$ and force carrier particles $bosons$. There are [other](https://www.chegg.com/learn/physics/introduction-to-physics/hadrons) [particles](https://www.fizzics.org/gauge-bosons/) which may or may not [exist](https://www.fizzics.org/fermions-quarks-leptons-and-hadrons-the-building-blocks-of-our-universe/) or are highly unstable. 

> 🍌 Every thing is made up of smaller units, called elements of matter, these inturn are further made up of quantum particles. Many particles exist naturally, and some exist only in certain conditions. 

## [Quantum Mechanics](https://www.livescience.com/33816-quantum-mechanics-explanation.html) 

```mermaid
graph TD
    A[Quantum<br>Mechanics] --> A1[Hilbert<br>Space]
    A --> A2[Harmonic<br>Osciallator]
    A --> A3[Transformations<br> and Symmetries]
    A --> A4[Angular<br>Momentum]
    A --> A5[Identical<br>Particles]
    A --> A6[Time Independent<br>Perturbation Theory]
```

[![](./infogfx/quamechin.jpg)](https://twitter.com/DominicWalliman/status/1113486268048924673?s=20&t=I0QVXkKeuBJ9ZKBKEbivnw)
<p align="center">
<i> Fig 13: Illustration of the interpretation of Quantum Mecahnics based on the principlels of Quantum Physics as described in the previous sections </i>
</p>

### Difference between QP and QM 

[Quantum Physics](https://www.differencebetween.com/difference-between-quantum-physics-and-vs-quantum-mechanics/) | [Quantum Mechanics](https://www.differencebetween.com/difference-between-quantum-physics-and-vs-quantum-mechanics/) 
|:--:|:--:|
Major branch of science | Branch of Quantum Physics 
Describes the particles | Describes their various interactions 
Defined as Quantum physics is a branch of science that focuses on systems explained by theories such as quantum mechanics and quantum field theory. Scientists and researchers focus on this area in order to use this knowledge to understand the behaviour of particles at the subatomic level. However, sometimes we use the terms “quantum physics” and “quantum mechanics” interchangeably. | Defined as Quantum mechanics is the set of principle that explains the behaviour of matter at atomic (or subatomic) scale. The word ‘quantum’ itself describes a fundamental concept of quantum mechanics – the quantized or discrete nature of matter and energy.

https://digbib.ubka.uni-karlsruhe.de/volltexte/wasbleibt/57355817/57355817.pdf - Ref for principles of QM 

https://www.damtp.cam.ac.uk/user/dbs26/PQM.html - This is more concise 


To Do Items 
- [ ] Describe hilbert space 
- [ ] Describe Schrodinger equation
- [ ] Describe principles of Quantum Mecahnics 
- [ ] Talks about EigenStates

### Eigen Spaces

[Linear Algebra is the language](https://qiskit.org/textbook/ch-appendix/linear_algebra.html) of Quantum Computing. The most important methematical quantity of QC is the $vector(v)\rangle$, $(v)$ is an element of a $set$ known as a $vector\ space$. Fundamentally $(v)$ is a mathematical quantity which has both *magnitude & direction*

In QC often we deal with *state vectors* which are vectors which point to a specific point in space which corresponds to a particular *Quantum State*. These states are visualized as a [Bloch Sphere](https://youtu.be/Ka4eF4zL3-0) which represents a $qubit$.


### Wave Functions


```mermaid 
flowchart TD 
    A --> B
```

# 🐱‍💻 QUANTUM Computing (FINALLY 🙃)

> Under Construction

Now that we have a firm grasp (😁) of the important fundamental of QC, the following are a curated sources for some experimentation


[![](infogfx/qcvtc.png)](https://www.cbinsights.com/research/quantum-computing-classical-computing-comparison-infographic/)


# 🔎 REFERENCES

Majority of the references will be 

1. [Header Quantum Entanglement Gif](https://tenor.com/view/entanglement-quantum-entanglement-science-atoms-gif-17770432) - Actual source of image is not described. The illustration is factual as described [HERE.](https://www.livescience.com/what-is-quantum-entanglement.html)

# 📒 GLOSSARY 

n | Term | Expansion
|:--|:--:|:--|
1 | QC | Quantum Computing 
2 | QP | Quantum Physics 
3 | QP | Quantum Mechanics
4 | SMP | Standard Model of Particle Physics

# 🎓 CITATION

 ```latex
 @misc{m0ham3dxx, title={M0ham3dx/quantum-computing-primer: Quantum computing primer githb repositroy research paper}, url={https://github.com/m0ham3dx/Quantum-Computing-Primer}, journal={Quantum Computing Primer - Github Reserarch Paper Respository }, publisher={https://twitter.com/m0ham3dxx}, author={m0ham3dxx}} 
 ```

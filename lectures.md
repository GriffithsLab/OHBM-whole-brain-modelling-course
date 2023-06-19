---
layout: lectures
title: Lectures
permalink: /lectures/
---

<style>
    h1 {
        color: #333;
        font-size: 28px;
        font-weight: bold;
        margin-bottom: 10px;
    }

    h2 {
        color: #555;
        font-size: 24px;
        font-weight: bold;
        margin-bottom: 10px;
    }

    p {
        color: #777;
        font-size: 16px;
        line-height: 1.5;
    }

    .lecture-time {
        color: #007bff; /* Change the color code to your preference */
        font-weight: bold;
    }

    .presenter {
        font-style: italic;
        color: #333;
    }
</style>

<h1>1) Background / Theory</h1>

<h2>Introduction to Dynamics Systems</h2>
<p class="lecture-time">Time: 09:00-09:45</p>
<p>This introduction will provide an overview of concepts and tools available in dynamic systems as they pertain to neurosciences. Dynamic behaviors will be characterized in one, two, and many degrees of freedom. Examples will be taken from computational neurosciences. I will discuss how complex behaviors arise and explain the relevant mechanisms including criticality, bifurcations, and symmetry breaking. Based on this foundation, I explain the emergence of self-organization phenomena in neuronal networks and show how probability density distributions relate to Free Energy and the Maximum Information Principle, as well as deterministic and stochastic forces.</p>

<h3><strong>Presenter</strong></h3>
<p class="presenter"><a href="https://griffithslab.github.io/OHBM-whole-brain-modelling-course/speakers/#:~:text=Speakers-,Dr.%20Viktor%20Jirsa,-Director%20of%20the">Viktor Jirsa</a><br/>
Institut de Neurosciences des Systèmes Marseille<br/>
France</p>
<br/>

<h2>Introduction to connectivity</h2>
<p class="lecture-time">Time: 09:45-10:30</p>
<p>The dynamics of networked systems is known to be strongly dependent on topological features of the connectivity map, particularly when the system operates at the critical border between incoherence and full synchrony. The map of neuroanatomical connections between brain areas obtained from diffusion imaging thus plays a crucial role not only in mediating the transmission of neural signals between brain areas but actually in shaping brain activity in space and time.
Computational models simulating the interactions between neural signals in the connectome serve as powerful tools to investigate the impact of specific connectome properties, such as its distribution of coupling weights and distances, as well as properties defined from graph theory, on the resulting dynamics. In this lecture I will demonstrate how the brain connectome has features that support non-stationary dynamics driven by transient cluster synchronization.
I will demonstrate how altering the connectome structure by removing nodes or links or reorganizing the distribution of links can greatly disrupt the stability of this critical regime. In addition, I will demonstrate how considering the distance between brain areas introduces an additional degree of complexity that expands the dynamics in the frequency domain, supported by the literature in the physics of delay coupled systems.
Scripts for the simulation of brain dynamics using distinct variations of the connectome structure will be made available and a short demonstration will be performed at the end of the talk.</p>

<h3><strong>Presenter</strong></h3>
<p class="presenter"><a href="https://griffithslab.github.io/OHBM-whole-brain-modelling-course/speakers/#:~:text=The%20Virtual%20Brain.-,Dr.%20Joana%20Cabral,-Postdoctoral%20Research%20Scientist">Joana Cabral</a><br/>
University of Minho Braga<br/>
Portugal</p>
<br/>

<h2>Intro to connectome-based neural mass modelling</h2>
<p class="lecture-time">Time: 10:30-11:15</p>
<p>Mathematical expressions of human brain activity have been central in gaining insights into the hidden mechanisms of the underlying neural processes at multiple scales. In this context, Whole-Brain Modelling (WBM) is a sub-field of computational neuroscience concerned with computational and theoretical models of approximately whole-brain neural activity. The usual objective of this approach is to study how macroscopic spatiotemporal patterns of neural activity result from the interaction of anatomical connectivity structure, intrinsic neural dynamics, and external perturbations (sensory, cognitive, pharmacological, electromagnetic, etc). Such macroscopic phenomena, and models thereof, are of particular scientific interest because a) they represent neural systems in a holistic and relatively intact state, and b) they are the type of measurement that can be most readily obtained from the brains of healthy human subjects, using noninvasive neuroimaging and related methods. Simulations of human brain activity, in both health and disease, are therefore a principal focus of current WBM research.
The basic idea is to model the brain at the macro scale as a network of interconnected regions, where the network nodes representing those regions are defined by (principally) neuroimaging-based brain parcellations, and the presence and weights of the network edges interconnecting the nodes are derived from neuroimaging- or chemical tract tracing-based anatomical connectivity measurements. This can be realized using neural mass models which (NMM) represents the coarse grained activity of large populations of neurons and synapses using a small number of equations to express the mean firing rates and mean membrane potentials of each large neural population. NMM are capable of describing the change in firing rate of neural populations without spatial information and spatiotemporal time delays providing a succinct yet biophysically meaningful description of brain activity at the mesoscopic scale to reflect phenomena observed empirically at the macroscale. The main advantage of NMM is that the simplification of the dynamics reduces the number of dimensions or differential equations that need to be integrated enabling us to hone in on the behavior of a large number of ensembles and understand more clearly their dynamics. Those models aim is to propose a balanced model between mathematical tractability and biological plausibility aimed at reproducing a wide range of empirical data features across multiple measurement modalities.
These features include: fast oscillations in local field potential (LFP) and extracranial electromagnetic (MEG, EEG) signals; slow quasi-periodic activity fluctuations in haemodynamic (BOLD fMRI, fNIRS) signals; inter-regional synchrony/covariance (‘functional connectivity’) and causal interactions (‘effective connectivity’) in both fast and slow activity patterns; sensory- or electromagnetic stimulation-evoked response waveforms; graph-theoretic properties large-scale network activity; and many others.</p>

<h3><strong>Presenter</strong></h3>
<p class="presenter"><a href="https://griffithslab.github.io/OHBM-whole-brain-modelling-course/speakers/#:~:text=mental%20health%20outcomes..-,Sorenza%20Bastiaens,-Ph.D.%20Candidate">Sorenza Bastiaens</a><br/>
CAMH Toronto, Ontario<br/>
Canada</p>
<br/>

<h1>2) Applications 1: Systems/Cognitive</h1>

<h2>Metastable brain waves: Principles and function</h2>
<p class="lecture-time">Time: 13:00-13:45</p>
<p>Traveling patterns of neuronal activity—brain waves—have been observed across a breadth of neuronal recordings, states of awareness, and species. Brain waves occur in models of neuronal activity, including large-scale models of the human brain that incorporate anatomy and connectivity. In my talk, I will walk through the complex nonlinear dynamics that emerge from modeling large-scale spontaneous neural activity on a whole-brain network derived from human tractography. A rich array of three-dimensional wave patterns include traveling waves, spiral waves, sources, and sinks. These patterns are metastable, such that multiple spatiotemporal wave patterns are visited in sequence. These metastable dynamics accord with empirical data from multiple imaging modalities, including electrical waves in cortical tissue, sequential spatiotemporal patterns in resting-state MEG data, and large-scale waves in human electrocorticography. I will also explore possible functional roles for these waves which include information compression, transmission and decoding.</p>

<h3><strong>Presenter</strong></h3>
<p class="presenter"><a href="https://griffithslab.github.io/OHBM-whole-brain-modelling-course/speakers/#:~:text=Dr.%20Michael%20Breakspear">Michael Breakspear</a><br/>
University of Newcastle Newcastle<br/>
Australia</p>
<br/>

<h2>Computational models link cellular mechanisms of neuromodulation to large-scale neural dynamics</h2>
<p class="lecture-time">Time: 13:45-14:30</p>
<p>Decades of neurobiological research have disclosed the diverse manners in which the response properties of neurons are dynamically modulated to support adaptive cognitive functions. This neuromodulation is achieved through alterations in the biophysical properties of the neuron. However, changes in cognitive function do not arise directly from the modulation of individual neurons, but are mediated by population dynamics in mesoscopic neural ensembles. Understanding this multiscale mapping is an important but nontrivial issue. Here, we bridge these different levels of description by showing how computational models parametrically map classic neuromodulatory processes onto systems-level models of neural activity. The ensuing critical balance of systems-level activity supports perception and action, although our knowledge of this mapping remains incomplete. In this way, quantitative models that link microscale neuronal neuromodulation to systems-level brain function highlight gaps in knowledge and suggest new directions for integrating theoretical and experimental work.</p>

<h3><strong>Presenter</strong></h3>
<p class="presenter"><a href="https://griffithslab.github.io/OHBM-whole-brain-modelling-course/speakers/#:~:text=mental%20health%20outcomes.-,Dr.%20James%20Mac%20Shine,-Director%20of%20the">James "Mac" Shine</a><br/>
The University of Sydney Sydney<br/>
Australia</p>
<br/>

<h2>Learning function from structure in neuromorphic networks</h2>
<p class="lecture-time">Time: 14:30-15:15</p>
<p>The connection patterns of neural circuits in the brain form a complex network. Signaling within the network manifests as patterned neural activity and is thought to support the computations that underlie cognition and adaptive behavior. How does the organization of the brain confer computational capacity? One way to address this question is through models that map structural connectivity to emergent neural dynamics and functional connectivity patterns, or to individual differences in behaviour. An alternative way is to directly consider function as a computational property. In this regard, artificial intelligence algorithms offer new ways to study structure-function relationships by conceptualizing function as a computational property. We propose a novel way to address the link between structure and function, but with a focus on computation. To do so, we combine MRI connectomics and reservoir computing to investigate the link between macroscale connectivity, and the computational properties that emerge from network dynamics in the human connectome. Specifically, we construct artificial neural networks endowed with biologically realistic connection patterns derived from diffusion MRI and train them to perform a cognitive task. We provide a use-case driven example that implements a simple memory task to illustrate the power of this approach, and we put forward ideas on how this framework can be extended to study other aspects of the link between structure and function in brain networks.</p>

<h3><strong>Presenter</strong></h3>
<p class="presenter"><a href="https://griffithslab.github.io/OHBM-whole-brain-modelling-course/speakers/#:~:text=and%20neuropsychiatric%20disorders.-,Dr.%20Laura,-Su%C3%A1rez">Laura Suárez</a><br/>
Montréal Neurological Institute, McGill University Montreal, Quebec <br/>
Canada</p>
<br/>

<h1>3) Applications 2: Clinical</h1>

<h2>Whole brain modeling for epilepsy diagnosis</h2>
<p class="lecture-time">Time: 16:15-17:00</p>
<p>Epilepsy affects 1% of the world’s population, making it one of the most common brain diseases. Treatments such as anti-epileptic drugs are common, however 1 in 3 epileptic patients is resistant to medication. For these patients, one of the main treatment options is brain surgery. However, brain surgery has a success rate of 50-70% depending on the type of epilepsy. Improving drug-resistant epilepsy diagnosis can have a significant impact in patient’s lives.
By building personalized whole brain models of epileptic patients, we seek to estimate the epileptogenic zone, i.e. the parts of the patient’s brain where seizures originate from. We do this by integrating different medical imaging data from the same patient. Specifically, T1-MRI is used to reconstruct the patient’s brain in 3D space. By overlaying brain atlases on this structure, the patient’s brain is parcellated in functionally and anatomically relevant regions. Next, diffusion-weighted (DW) MRI is used to estimate the white matter fiber bundles’ position and orientation. We represent brain regions as nodes in space which are connected to each other by edges of different strength. The edge strength is derived from the estimated white matter tract bundles passing between two regions. This is what we also call a brain network model. This brain model is personalized because it is unique to each patient’s MRI data.
To model brain dynamics of drug resistant epilepsy, we equip each node with mathematical equations describing neural activity of populations of neurons, also called neural mass models. The Epileptor model in particular can describe seizure dynamics (Jirsa et al 2014). Using this model, we describe complex spatiotemporal seizure dynamics within personalized brain network models. By mapping out the parameter space of this model against empirical recordings of seizure dynamics, we can estimate the epileptogenic zone using bayesian inference. This virtual epileptic patient (VEP) pipeline is currently used in a clinical trial (EPINOV) in France to diagnose the epileptogenic zone for drug resistant focal epilepsy patients. The goal of the trial is to estimate the predictive capacity of VEP in estimating the epileptogenic zone and to improve the success rate of brain surgery. Our preliminary results point towards a predictive capacity of the VEP pipeline.
Furthermore, in our clinical practice, brain stimulation is applied in drug-resistant epileptic patients in different brain regions with varying parameters (amplitude, frequency, pulse width, location) prior to brain surgery. This is done using implanted SEEG (StereoElectroEncephaloGraphy) electrodes which can stimulate and record local brain activity. Stimulating systematically across zones and across parameters can help in diagnosing the epileptogenic zones. Brain stimulation is a useful clinical practice that is based on empirical trial and error, but with very little knowledge about the mechanistic effects. Most of the stimulation trials do not induce seizures, which means that stimulation is applied also to healthy regions. We aim to reduce the stimulation trials applied to healthy tissue, and save clinical time in finding the optimal stimulation parameters that induce seizures. Personalized virtual brain models can help us better control the effects of brain stimulation. We used this approach to model brain stimulation for drug-resistant epilepsy diagnosis.
We extended the Epileptor model for brain stimulation effects on seizure onset. We hypothesized, based on empirical human data and present literature, an accumulative effect of brain stimulation. We relate this to ionic imbalance, in particular extracellular potassium accumulation. This accumulation is region-specific, and when reaching a certain threshold, it can give rise to seizures. We validated our model against empirical recordings where brain stimulation was applied. We did this for patients that have at least one spontaneous and one stimulated seizure. We found that by changing only stimulation parameters and keeping the virtual brain model unchanged, we could reproduce the various spatiotemporal seizure dynamics observed empirically. Thus, the same brain model can elicit different seizure dynamics, which we also observe clinically. We could then explore the system beyond the limited stimulation parameters. We found that the most determinant factors for brain stimulation effects are: stimulation site, stimulation intensity, brain connectivity and brain state.
These results demonstrate the usefulness of personalized brain models to understand spatiotemporal seizure dynamics and to help in diagnosing drug-resistant epilepsy. Integrating unique patient data allows us to adapt our models to each patient’s brain structure and connectivity, to assist the clinical team in diagnosing the epileptogenic zone.</p>

<h3><strong>Presenter</strong></h3>
<p class="presenter"><a href="https://griffithslab.github.io/OHBM-whole-brain-modelling-course/speakers/#:~:text=inspired%20computing%20systems.-,Borana%20Dollomaja,-Ph.D.%20Candidate">Borana Dollomaja</a><br/>
Institut de Neurosciences des Systèmes Marseille<br/>
France</p>
<br/>

<h2>Linking mechanistic multi-scale brain simulation and knowledge technology – towards a holistic understanding of Alzheimer’s Disease</h2>
<p class="lecture-time">Time: 16:15-17:00</p>
<p>Recent advantages in storing, organizing, and utilizing scientific knowledge sources open a new field towards a mechanistic understanding of brain diseases. Knowledge bases and ontologies incorporate information about protein-protein interaction, genomic features, and biochemical pathways in health and disease. We explore this topic for Alzheimer’s Disease, the most common cause of dementia and one of the leading causes of disability and health-related costs in the world. We show how information from the OMICS scale can be mapped onto the brain and consecutively linked to recent multi-scale brain models of Alzheimer’s Disease that take into account hyperexcitability and its potential usage in the improvement of diagnostic classification.</p>

<h3><strong>Presenter</strong></h3>
<p class="presenter"><a href="https://griffithslab.github.io/OHBM-whole-brain-modelling-course/speakers/#:~:text=Dr.%20Leon%20Stefanovski">Leon Stefanovski</a><br/>
Charité – Universitätsmedizin Berlin Berlin<br/>
Germany</p>
<br/>

---
# === Required fields  ===
# Your name 
name: "James Hefford"
# Your profile picture
imgname: 
  name: "img/main.jpg"
  alt: "Picture of me"
  type: image/jpeg
# More sources can be added (optional) using 
# imgOther:
#   - name: $IMAGE_PATH
#     type: $IMAGE_TYPE
#   - name: $IMAGE_PATH
#     type: $IMAGE_TYPE
# ...
# A title (job title or "Researcher", "PhD student", etc.)
personal_title: "Postdoctoral Researcher"
# An address (you can list multiple)
address: 
  - 
    name: Inria de Saclay
    street: 91120 Palaiseau
#    postal_code: "000000"
#    locality: Earth
    email: firstname.lastname@inria.fr
#    emailImg: 
#        dark: /img/dark_email.png
#        light: /img/light_email.svg
    scholar: https://scholar.google.com/citations?user=lEuOe5MAAAAJ&hl=en
    

# List your publications. The required fields are pdf, title, and image 
# (which should be the image path). The other fields are optional.
publications:
  - 
    authors:
        #- name: J. Hefford 
        #  me: true
        - name: M. Wilson

    title: "A Profunctorial Semantics for Quantum Supermaps"
    date: 2024
    conference: Logic in Computer Science
    image: img/supermaps.png
    pdf: https://arxiv.org/abs/2402.02997
    
    # A list of link that will appear as badges at the bottom of the publication.
    #links:
    #  -
    #    name: Main URL
    #    url: "https://www.nature.com/articles/ncomms2819"

    #description: "We identify morphisms of strong profunctors as a categorification of quantum supermaps. These black-box generalisations of diagrams-with-holes are hence placed within the broader field of profunctor optics, as morphisms in the category of copresheaves on concrete networks. This enables the first construction of abstract logical connectives such as tensor products and negations for supermaps in a totally theory-independent setting. These logical connectives are found to be all that is needed to abstractly model the key structural features of the quantum theory of supermaps: black-box indefinite causal order, black-box definite causal order, and the factorisation of definitely causally ordered supermaps into concrete circuit diagrams. We demonstrate that at the heart of these factorisation theorems lies the Yoneda lemma and the notion of representability."
    
  - 
    authors:
        #- name: J. Hefford 
        #  me: true
        - name: M. Román

    title: "Optics for Premonoidal Categories"
    date: 2023
    conference: Applied Category Theory
    #journal: EPTCS 397
    image: img/premon_optics.png
    pdf: https://arxiv.org/abs/2305.02906
    
    # A list of link that will appear as badges at the bottom of the publication.
    #links:
    #  -
    #    name: Main URL
    #    url: "https://www.nature.com/articles/ncomms2819"

    #description: "We further the theory of optics or ''circuits-with-holes'' to encompass premonoidal categories: monoidal categories without the interchange law. Every premonoidal category gives rise to an effectful category (i.e. a generalised Freyd-category) given by the embedding of the monoidal subcategory of central morphisms. We introduce ''pro-effectful'' categories and show that optics for premonoidal categories exhibit this structure. Pro-effectful categories are the non-representable versions of effectful categories, akin to the generalisation of monoidal to promonoidal categories. We extend a classical result of Day to this setting, showing an equivalence between pro-effectful structures on a category and effectful structures on its free conical cocompletion. We also demonstrate that pro-effectful categories are equivalent to prostrong promonads."
    
  -
    authors:
       - name: M. Earnshaw
       #- name: J. Hefford
       # me: true
       - name:  M. Román
    title: "The Produoidal Algebra of Process Decomposition"
    date: 2024
    conference: Computer Science Logic
    image: img/produoidal.png
    pdf: https://arxiv.org/abs/2301.11867
    #description: "We introduce the normal produoidal category of monoidal contexts over an arbitrary monoidal category. In the same sense that a monoidal morphism represents a process, a monoidal context represents an incomplete process: a piece of a decomposition, possibly containing missing parts. We characterize monoidal contexts in terms of universal properties. In particular, symmetric monoidal contexts coincide with monoidal lenses, endowing them with a novel universal property. We apply this algebraic structure to the analysis of multi-party interaction protocols in arbitrary theories of processes."
    
  -
    authors:
       #- name: J. Hefford
       # me: true
       - name:  A. Kissinger
    title: "On the Pre- and Promonoidal Structure of Spacetime"
    date: 2022
    conference: Applied Category Theory
    #journal: EPTCS 380
    image: img/spacetime.png
    pdf: https://arxiv.org/abs/2206.09678
    #description: "The notion of a joint system, as captured by the monoidal (a.k.a. tensor) product, is fundamental to the compositional, process-theoretic approach to physical theories. Promonoidal categories generalise monoidal categories by replacing the functors normally used to form joint systems with profunctors. Intuitively, this allows the formation of joint systems which may not always give a system again, but instead a generalised system given by a presheaf. This extra freedom gives a new, richer notion of joint systems that can be applied to categorical formulations of spacetime. Whereas previous formulations have relied on partial monoidal structure that is only defined on pairs of independent (i.e. spacelike separated) systems, here we give a concrete formulation of spacetime where the notion of a joint system is defined for any pair of systems as a presheaf. The representable presheaves correspond precisely to those actual systems that arise from combining spacelike systems, whereas more general presheaves correspond to virtual systems which inherit some of the logical/compositional properties of their ''actual'' counterparts. We show that there are two ways of doing this, corresponding roughly to relativistic versions of conjunction and disjunction. The former endows the category of spacetime slices in a Lorentzian manifold with a promonoidal structure, whereas the latter augments this structure with an (even more) generalised way to combine systems that fails the interchange law."
    
  -
    authors:
       #- name: J. Hefford
       # me: true
       - name:  C. Comfort
    title: "Coend Optics for Quantum Combs"
    date: 2022
    conference: Applied Category Theory
    #journal: EPTCS 380
    image: img/coend_optics.png
    pdf: https://arxiv.org/abs/2205.09027
    #description: "We compare two possible ways of defining a category of 1-combs, the first intensionally as coend optics and the second extensionally as a quotient by the operational behaviour of 1-combs on lower-order maps. We show that there is a full and bijective on objects functor quotienting the intensional definition to the extensional one and give some sufficient conditions for this functor to be an isomorphism of categories. We also show how the constructions for 1-combs can be extended to produce polycategories of n-combs with similar results about when these polycategories are equivalent. The extensional definition is of particular interest in the study of quantum combs and we hope this work might produce further interest in the usage of optics for modelling these structures in quantum theory."
    
  -
    authors:
       - name: O. Higgott
       - name: M. Wilson
       #- name: J. Hefford
       # me: true
       - name: J. Dborin
       - name: F. Hanif
       - name: S. Burton
       - name: D.E. Browne
    title: "Optimal local unitary encoding circuits for the surface code"
    date: 2021
    journal: Quantum
    image: img/surface_code.png
    pdf: https://quantum-journal.org/papers/q-2021-08-05-517/
    #description: "The surface code is a leading candidate quantum error correcting code, owing to its high threshold, and compatibility with existing experimental architectures. Bravyi et al. showed that encoding a state in the surface code using local unitary operations requires time at least linear in the lattice size L, however the most efficient known method for encoding an unknown state, introduced by Dennis et al., has O(L2) time complexity. Here, we present an optimal local unitary encoding circuit for the planar surface code that uses exactly 2L time steps to encode an unknown state in a distance L planar code. We further show how an O(L) complexity local unitary encoder for the toric code can be found by enforcing locality in the O(logL)-depth non-local renormalisation encoder. We relate these techniques by providing an O(L) local unitary circuit to convert between a toric code and a planar code, and also provide optimal encoders for the rectangular, rotated and 3D surface codes. Furthermore, we show how our encoding circuit for the planar code can be used to prepare fermionic states in the compact mapping, a recently introduced fermion to qubit mapping that has a stabiliser structure similar to that of the surface code and is particularly efficient for simulating the Fermi-Hubbard model."
    
  -
    authors:
       #- name: J. Hefford
       # me: true
       - name: S. Gogioso
    title: "CPM Categories for Galois Extensions"
    date: 2021
    conference: Quantum Physics and Logic
    #journal: EPTCS 343
    image: img/galois_cpm.png
    pdf: https://arxiv.org/abs/2106.01209v2
    #description: "By considering a generalisation of the CPM construction, we develop an infinite hierarchy of probabilistic theories, exhibiting compositional decoherence structures which generalise the traditional quantum-to-classical transition. Analogously to the quantum-to-classical case, these decoherences reduce the degrees of freedom in physical systems, while at the same time restricting the fields over which the systems are defined. These theories possess fully fledged operational semantics, allowing both categorical and GPT-style approaches to their study."
    
  -
    authors:
       #- name: J. Hefford
       # me: true
       - name: S. Gogioso
    title: "Hyper-decoherence in Density Hypercubes"
    date: 2020
    conference: Quantum Physics and Logic
    #journal: EPTCS 340
    image: img/hypercubes.png
    pdf: https://arxiv.org/abs/2003.08318
    #description: "We study hyper-decoherence in three operational theories from the literature, all examples of the recently introduced higher-order CPM construction. Amongst these, we show the theory of density hypercubes to be the richest in terms of post-quantum phenomena. Specifically, we demonstrate the existence of a probabilistic hyper-decoherence of density hypercubes to quantum systems and calculate the associated hyper-phase group. This makes density hypercubes of significant foundational interest, as an example of a theory which side-steps a recent no-go result in an original and unforeseen way, while at the same time displaying fully fledged operational semantics."
---

# Bio

I am an Inria postdoctoral researcher in the [Quacs group](https://lmf.cnrs.fr/Research/Quant) at LMF. My interests include category theory and the application of these methods to problems in physics, particularly quantum theory and models of spacetime.

I completed my DPhil at the University of Oxford. Prior to this I did an MSci in Mathematics at Imperial College London and an MRes in Quantum Technologies at University College London.

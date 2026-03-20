
---
# === Required fields  ===
# Your name 
name: "Orvar Lorimer Olsson"
# Your profile picture
imgname: 
  name: "img/OLOpic.jpg"
  alt: "Profile picture"
  type: image/jpeg
# More sources can be added (optional) using 
# imgOther:
#   - name: $IMAGE_PATH
#     type: $IMAGE_TYPE
#   - name: $IMAGE_PATH
#     type: $IMAGE_TYPE
# ...
# A title (job title or "Researcher", "PhD student", etc.)
personal_title: "PhD student"
# An address (you can list multiple)
address: 
  - 
    name: studying Logic at 
    street: Department of Philosophy, Linquistics and Theory of Science
    postal_code: University of Gothenburg,
    locality: Sweden

# === Optional fields ===
# Add an email with a mailto: hyperlink
# email: aaaa@example.com
# Add an email "image" for spam protection. With light and dark mode
# emailImg: 
#   dark: /img/dark_email.png
#   light: /img/light_email.png

# List your publications. The required fields are pdf, title, and image 
# (which should be the image path). The other fields are optional.

# comment out next row and the publication is published
# publications:
  - 
    authors:
        - name: Rothe, S. 
          me: true
        - name: Andreyev, A. N. 
        - name: Antalic, S.
        - name: Borschevsky, A.
        - name: Capponi, L.
        - name: Cocolios, T. E.
        - name: De Witte, H.
        - name: Eliav, E.
    title: "Measurement of the First Ionization Potential of Astatine by Laser Ionization Spectroscopy"
    # Will write "In ${journal}, ${date}"
    date: 2013
    journal: Nature Communications
    image: img/paper_illustration.png
    # A bibtex (or any other format) citation that people can copy directly from the website.
    citation: "@article{article,\n
author = {Rothe, Sebastian and Andreyev, A and Antalic, Stanislav and Borschevsky, Anastasia and Capponi, Luigi and Cocolios, Thomas and De Witte, Hilde and Eliav, Ephraim and Fedorov, D.V. and Fedosseev, Valentin and Fink, D and Fritzsche, s and Ghys, Lars and Huyse, M and Imai, Nobuaki and Kaldor, U and Kudryavtsev, Yu and Koester, Ulli and Lane, J and Wendt, Klaus},\n
year = {2013},\n
month = {05},\n
pages = {1835},\n
title = {Measurement of the first ionization potential of astatine by laser ionization spectroscopy},\n
volume = {4},\n
journal = {Nature communications},\n
doi = {10.1038/ncomms2819}\n
}"
    pdf: https://www.nature.com/articles/ncomms2819.pdf
    # A list of link that will appear as badges at the bottom of the publication.
    links:
      -
        name: Main URL
        url: "https://www.nature.com/articles/ncomms2819"
      -
        name: ResearchGate
        url: "https://www.researchgate.net/publication/236836716_Measurement_of_the_first_ionization_potential_of_astatine_by_laser_ionization_spectroscopy"
    # A description for the paper.
    description: The radioactive element astatine exists only in trace amounts in nature. Its properties can therefore only be explored by study of the minute quantities of artificially produced isotopes or by performing theoretical calculations. One of the most important properties influencing the chemical behaviour is the energy required to remove one electron from the valence shell, referred to as the ionization potential.
---
## Under construction
This homepage is currently being constructed. Please come back at a later stage.


## Presentation
 
I am a student and researcher of (mathematical) formal logics. With a warm heart for algebra, and a tendency for abstraction, I am interested in fundamental questions regarding formulations of logical semantics and proof systems: identifying classes of systems, translations between systems, systematically generating new systems from known structures, etc. A lot of my approach could fall under the umbrella of "universal logic" and questions regarding how fundamental changes in formulation effects the complexity in expressing or proving properties of a system. Hopefully these investigations will in the long run give some insights in the fundamental question of "logicality": what distinguishes properties that can be considered "logical" from other properties?

## My PhD thesis project : Lifting formal systems from individuals to groups 
A standard understanding of what it means for a statement to be "logically valid" is that it is satisfied in every possible interpretation. Reflecting this notion, many formal semantic systems are expressed in terms of some collection of tokens (be it objects, worlds, assignment functions or the like) for which formal statements may be satisfied or not. This defines a semantics in terms of properties of individuals.

Given such semantic setup, we can also consider satisfaction in terms of groups of semantic tokens. This lifts the statement of the semantics to properties of "teams" of individuals. Such lift gives rise to a much richer semantic space, and makes it possible to extend the formal language with statements about groups  that are not meaningfully stated about individual tokens, e.g. notions of dependent choices. 
This type of semantic lift has been most explicitly used to define *dependence logic* by means of *team semantics* capable of describing forms of quantification not expressible in standard first order logic. Similar lifts has also been used to form semantics with notions of  ambiguity or *plurivalence* for multi-valued logics. Furthermore, in an abstract sense we can also describe the notion of Kripkean possible worlds semantics as the result of a similar type of semantic lift from possible worlds to related groups of possible worlds.

In my thesis work I try to pin down exactly how the semantic lift from individuals to group really works and what properties of the underlying system that are forced on the lifted semantics: Given a logic with a well understood semantic system in terms of individual tokens, what do we know about the team semantics that it induces? What is the expressive power of the induced formula language? Is the lift categorical for the logic or dependent of the semantic representation? Does a proof system for the underlying logic inform us how to form a proof system for the logic of the lifted semantics? etc. 

As a general slogan applicable outside of pure logic, the main research question can be posed as follows:
Given information about properties of individuals, what does it tell us about the properties of the groups they can form?

Currently I have approach these questions by studying algebraic structures and their *power-structures*, being the structures formed by their subsets, investigating some of the above questions primarily for propositional logics. The goal is to also extend this work to predicate logics, and higher order languages,  with particular care for results regarding different types of generalised quantifiers. 

## Contact 
To find my official contact information, please find me through the institution I am affiliated with. 







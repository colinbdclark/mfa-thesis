# Vibrant Digital Bodies: Cinema, Software, and Community

The goals of this section are to:
* Extend the concepts of materiality and embodiment to include digital cinema and computation
* Explore the relationship between community methods, my software artworks, and materiality
* Propose, based on Jane Bennett ("Texts are bodies that can light up, by rendering human perception more acute, those bodies whose favoured vehicle of affectivity is less wordy: plants, animals, blades of grass, household objects, trash") and Mark Hansen ("all reality is mixed reality", "technics are co-constitutive of our embodied perception"), that computation is itself embodied: software has a body, and enacts real bodily effects/affects in the world


## The Materials of Community

This project involves two primary and interrelated software development activities:

1. Creating videos and music such as _In Passing_, _Tofino_, and the soundtrack for _Font Màgica_, which are generated or processed by means of software that I designed and built specifically for these pieces and their idiosyncrasies.
2. Designing, developing, and sharing with a community a set of creative tools and frameworks, _Flocking_ and _Aconite_, which were designed initially as a generalized support structure for my own creative endeavours, but also intended to be used by other artists in their own creative work

Every piece of "software art" in this project, along with the supporting technical frameworks and documentation, have been made using collaborative open source methods. Early ideas and concepts emerged via discussions with a distributed community of artists, designers, and programmers who have formed around the Fluid Infusion and Flocking communities<sup>1</sup>. Even this text itself, from my first tentative notes and initial annotated bibliography through to the comments from reviews of each section, was produced using open source strategies<sup>2</sup>. In the case of Flocking, a community of perhaps one hundred people from around the world, mostly composers and sound artists, have used or contributed to it<sup>3</sup>.

### Open as Method

Open community methods first emerged within the research software development culture of the 1970s at MIT, Berkeley, and elsewhere, and evolved into a more formalized body of practice in the late 1990s with the communities that formed to develop freely-distributed and openly-licensed software such as the Linux operating system and the Firefox web browser (Voyce 416) (Bretthauer 16). In _Wide Open: Open Source Methods and Their Future_, Mulgan, Steinberg, and Salem define open source software as "any computer software distributed under a license which allows users to change or share the software's source code. Source code is the human-readable version of a computer program" (8). It is worth noting that, even within this simple description, the predominant emphasis, by open source software developers and academics alike, is placed directly on the source code as an originary and authorial text. Source code is cast as the "human readable" manifestation of software, in contrast to its runtime form. This issue will be taken up below, following a brief discussion of open source methods and my practice.

Mulgan, Steinberg, and Salem note that open source methods are "at the cusp of familiar tools," often resembling conversations, formal research teams, academic scholarship, and DIY communities (15-6). Amongst the characteristics of open source methodologies described in _Wide Open_, several are particularly germane to my practice: transparency, peer review and feedback loops, and incrementalism (16). These strategies have helped to expand the networks of use and criticism for my work beyond my own local scholarly and creative communities. Work on _Flocking_, in particular, has been substantially supported by the very diverse perspectives that make up its community of users, contributors, and critics. By working transparently so that each change (or "commit") to the system is visible to those following the project using the Github collaboration site<sup>4</code>, Flocking's community is able to offer feedback, advice, and critical improvements while I work.

Working transparently is a strange prospect, particularly when the software being developed is still in the early stages of creative articulation. Yet, as a result of this openness, members of the community often feel motivated to reciprocally share their artistic projects with me. I have benefitted from this mutual exchange significantly, not only gaining new design insights into how to support the creative needs and processes of artists who are significant unlike me<sup>5</sup>, but also catalyzing new aesthetic strategies by studying, experiencing, and working through software art created by others in the community. In the past, as a traditional instrumental music composer, I was rarely able to have such ready access to the scores and recordings of "non-master" composers except within my immediate (though nonetheless highly germane) sphere of my artistic friendships within Toronto. To be clear, this is not an argument for global networks and against local ones; rather, it is call for the recognition of new forms of locality that emerge "telesthetically" around the creative currents and capabilities of shared artifacts and practices.

### From Free to Material

However, for me, the most essential characteristic of openness is not so much the availability of source code (although this is a prerequisite for other forms of openness) nor the enactment of a specific set of technical governance and legal practices, but the way that collaborative practices, performed in the context of an inclusive community, can engender artifacts that in some way materially embody these practices. Software that forms, to use McKenzie Wark's term, new creative "vectors for a collective becoming" (_Hacker Manifesto_ 159-60).

The term "open source" is highly contested, particularly by those who identify instead with the "free software" movement. The distinction is marked by differences of legal position and political philosophy. "Free" requires, as an explicit feature of its license, that all modifications or derivations of the source code, including its combination with other works, must be distributed under the same open terms (Stallman 32). This is "viral" licensing; its legal terms spread to anything a piece of software touches; sharing is legally mandated, never a spontaneous gift. Free software advocates promote this as being "free as in speech," an ensconcement of a programmer's right to the source code, instead of just "free as in beer" (Stallan 43). Neither the term "open source" nor "free software" fits my project, though there are aspects of each that am I interested in.

I use the "open" here instead of "free" intentionally. I remain concerned by the suffix "source"; instead, I prefer to use the term "open community" instead. In part, this term aims to avoid what I see as the blunt ideological rhetoric and overt legalism of "copyleft" free software advocates, while simultaneously hinting at the possibility that "openness"--to creative expression and personal adaptation of software--might be increasingly conceived of as a characteristic of software artifacts themselves, not just of source code. In other words, software has the potential, if approached differently, to form a kind of _material_ that can be worked on by means of itself, where the power to create and modify is available to all creators, not only computer programmers.

Wendy Chun: "Richard Stallman, in his critique of nonfree software, has argued that an executable program 'is a mysterious bunch of numbers. What it does is secret.' Against this magical execution, source code supposedly enables an understanding and a freedom--the ability to map and know the workings of the machine, but, again, only through a magical erasure of the gap between source and execution, an erasure of execution itself" (51).

It is this Cartesian dualism of computation, source/execution...

I argue, as a result of this failure to confront the material realities of software, that "free software", as a political movement, is largely a technocratic construction: creative control is centralized in software's programming language source code, where only a limited community--those who have access to the specialized knowledge of software programming--are able to benefit from its purported "liberty" and "freedom." Via my software development practice, manifest here in Flocking, Aconite, In Passing, Tofino, and _Font Màgica_, I aim to extend the values and methods of open source practice into the material of my software.

* this idea of software as vector, as material, starts to eat away at the form/content dichotomy, since a piece of software, as art (content), is also a medium (form) for engendering new works.


### The Transformative/Material Commons

Stephen Voyce outlines an "open source poetics" based on "a decentralized and nonproprietary model of shared cultural codes, networks of dissemination, and collaborative authorship" (407). His view of open source creativity is largely focused on appropriative, readymade, remix, and "uncreative" strategies, which call into question the role of singular authorship, shifting creative emphasis instead towards how poetry contributes to a "poetic commons" (408). In my soundtrack for Izabella Pruska-Oldenhof's _Font Màgica_, at her request, I used a recording of Chopin's Prelude No. 15 ("Raindrop") as a primary source, layering and blending it with recordings of radio astronomy events. These source materials, particularly the Chopin, were algorithmically transformed to draw out the shape and in-between moments of... The homemade Flocking signal processing algorithms... , producing an eerie and slightly warped expressivity
    * a process of de-registering and offsetting and making multiples, some stretched out in time or in a gesture, others just gently warped by an algorithm--and then re-registering the multiplicity of raindrop versions onto each other
    * and each version is somehow produced by a reading of the piece itself, through a different lens
    * like izabella's visuals, it's an overtly refractive piece, full of distortion and ghost versions overlaid on the original, sounding the transformations of a handful of algorithms plus variations of the recording--a little slower or faster, here, worrying over a region of expressive detail, there skipping
    * but then the piece is open differently; each layer, each point of refraction is available to be separated out, reused, or modified in some way. Each node and edge in the assemblage has a name and a handle by which it can be manipulated and extended, "warbledRightPiano" and "distortedLeftPiano," every volume curve or synth that represents the macro structure equally with every grain of the stuttering piano is available to "touch"
    * the point of font magica isn't that I composed or programmed with extra-musical concerns in mind, but that it was supported by a _material substrate_ (flocking and infusion) and a set of open community methods that support its extension--that support its use as both "source" and "secondary" (and tertiary, and so on), as well as supporting its linkage between static and executable forms, its "potential" and "actual" forms
    * connection with Chris Welsby's _Colour Separation_

Voyce sees the generative potential in such citational-appropriative techniques, ...

I am interested in the way that software artifacts can be made to support "material linkages" between existing and new works in a manner that goes in some way beyond citation or appropriation. Voyce insightfully imagines that avant-garde poetics can protect and contribute to a "commons"

"The responsibility of the avant-garde will instead require an activistic obligation to create and fortify public domains of open source knowledge, to challenge excessive restrictions placed on language and information, to bring forth marginalized knowledges from a position of inaccessibility to the public at large, and to produce and share artistic tactics and works that challenge intellectual property. That which is at stake is nothing less than open accessibility to culture" (427-8).


### The Work as Vector

* Define what open source methods are
* Ask the question, why do open source, especially when many of the artifacts are personal?--it's unlikely that people will want to fork or remix or reuse this thesis
* Stephen Voyce suggests the potential of an open source poetics: "While modifying a source text might involve deleting or excising, it can also involve extending, transforming, and sharing a given work... Such techniques release a portion of a text from its static, fixed position in a single work, enabling it to participate in a proliferation of potential texts amid continuously changing assemblages of authorial, intertextual, and communal networks."
* And yet he largely links transformation to appropriative tactics or those that "break down conventions of authorship" [my quote] (which are great, but not always what I do) rather to what we call "artifactual linkage" where a work is a Warkian vector-- A vector is more or less a "technological medium"--in principle, anyway, with our approach a given application or, here, artwork, has the potential to serve in some way as the medium for some second-order creativity: an artwork that becomes the medium for other artworks, not as quotation but as "transformation"
* One of the key reasons for producing my artworks (as opposed to just tools that are directly intended to be used and reused) using open source collaborative methods is to turn them into _vectors_--more than just artworks but the basis for new abstractions and potentialities (this of course requires a very different approach not aesthetically, as one might imagine, but technically--to the tools that support software creativity)
* Acknowledge the aspirational character of this work--Alan Kay and the cardboard mockup


an approach to creating and distributing software and texts--including this document--in which artifacts are generated and refined in a transparent and community-oriented fashion and licensed in a manner that encourages reuse, modification, and extension.



## Notes

1. I am particularly indebted to the conversations I have had over the past several years via open source collaborative vectors with Dr. Antranig Basman, lead research architect at Raising the Floor International; Dana Ayotte, an artist and inclusive designer at the Inclusive Design Research Centre; Michelle D'Souza, senior inclusive developer at the IDRC; Dr. Clemens Nylandsted Klokmose at the University of Aarhuis; my primary advisor, Dr. Adam Tindale; and others.

2. The full history of changes to this thesis over time can be seen in its "version control repository" hosted on Github: https://github.com/colinbdclark/mfa-thesis/commits/methods.

3. This figure is based on interpolating between the number of "forks" of the Flocking repository on Github (thirty seven as of January 30, 2016), representing people who have in some way modified the source code (https://github.com/colinbdclark/Flocking/network/members), and "stargazers" (currently 297), consisting of people who have declared interested in the project (https://github.com/colinbdclark/Flocking/stargazers).

4. Github is "a code-hosting repository based on the Git version control system. Github is an iconic example of a knowledge-based workspace. This site integrates a number of social features that make unique information about users and their activities visible within and across open source projects" (Dabbish et. al. 2). Many of my research and creative artifacts, including papers such as this one, are hosted on Github at https://github.com/colinbdclark.

5. Exposing a project to a diversity of perspectives, along with the "value of the unpopular," are key characteristics of inclusive design methods and are potential catalysts for innovation according to Jutta Treviranus. See Treviranus and Hockema, _The Value of the Unpopular_, and Treviranus, _Designing for the Full Range of Human Diversity_ http://inclusivedesign.ca/about/

## Boneyard


The injection of "community" into my terminology emphasizes not just specific communities of design/development practice, but the argument that creative expression should be possible within context of the aforementioned "vectors of collective becoming," meaning that the act of _working_ a software material should offer the possibility of cohesion, not only of separation (which always remains a choice). Today's software rarely functions in this way, and software's "freedom" is always expressed in terms of its source code, never its "living form" at runtime; freedom here takes the form of a "right" that only an elite access.


The value of working transparently and in a feedback loop with  linking it as much to other like-minded creators around the world as to, equally, exposing it to different approaches that cut
    * working transparently and openly is strange
    * my work takes on different qualities by being openly available--serving as example for other other artists, and subtly influencing the kinds of works that are made by others
    *

The expression of such a material creative influence, however, can undoubtedly not retain its singularity--the myth of _the_ source as a singular "text"...

Chun: ". If we consider source code as a fetish, the fact that source code has hardly deprived programmers of their priestlike/wizard status makes complete sense. If anything, such a notion of programmers has been disseminated ever more and the history of computing--from direct manipulation to hypertext--has been littered by various 'liberations.'"
    * in response to Chun's apparently weariness (and wariness) about liberational projects in computing, I argue that we nonetheless need to pursue new and different approaches to computational liberation, since the litter she refers to is in fact cast atop an even more substantial landscape of consumption and control

Substantive changes made to software source code must always be negotiated through an essentially _centralized_ conception of community--all participants must agree to a kind of material "rule of law," or a "fork" will occur, splitting the common artifactual linkage between changes. (NEED A FOOTNOTE ABOUT OPEN SOURCE FORKING).

4. See (Stallman) for an overview of the libertarian politics of the free software movement, whose freedoms are always predicated upon the possession of the specialist skill of being able to write, review, modify, or verify software's _source code_. In contrast, I am interested in challenging (via practical efforts) the basic Cartesian dualism of computation: the distinction between "code" and its execution, where the nexus of change and influence is currently centralized in the source code, rather than the running artifact of software. I will pick this theme up again later in the section on _Software Bodies_.

# What is Edion?
Edion is aiming to build an autonomous educational system that can work on an interplanetary scale. The goal is to automate teaching, decentralize knowledge and provide quality education for all.

## Why education needs an upgrade
Compiling and enforcing a curriculum is no easy task. Every national and international educational programme relies on the hard work of leading professionals in the sphere of education. Unfortunately, these professionals cannot make educational programmes catch up to the exponential acceleration of technological and social progress, nor can they make these programmes fool-proof in the face of social, economic, political, and, soon, ecological instability.

In some regions, education gets relentlessly stripped of truthful information, replaced with propaganda to make a false image of the state of the world. The global family needs a fully-transparent and uncensorable alternative to counter disinformation.

The model of education used globally has not changed much since the industrial revolution. Thanks to the recent renaissance in the development of artificial intelligence and network technologies, education can and must be reconceived by utilizing these state-of-the-art technologies to tailor exclusive educational roadmaps for every student everywhere.

## Late 21st-century education conceived
Every student on the planet has a life-long, personally tailored, coherent educational experience based on their interests, talents and preferences. Their roadmaps get generated based on information in a freely accessible ever-expanding ledger of immutable sources. Their assessments get automatically generated and marked in a fully trustless fashion. There is minimal intervention from human actors, and their authority is deserved and limited. The entire platform runs as a decentralized autonomous organization based on proof-of-personhood, where every student and educator can vote democratically on the platform's expansion and improvement. Creating learning material and making course progress are both incentivized and gamified by tokenomics. The quality of education is very high and consistent for everyone, everywhere, always.

## The four use cases
There are four use cases for using Edion in the current global social setting. Each employs the recommendation algorithm used for curriculum personalization to different extents.
1. As a class management system for unaffiliated schools and teachers (the recommendation algorithm not used)
2. As an accredited online school with pre-configured roadmaps and diplomas issued by qualification providers such as the IBO or the CIE (the recommendation algorithm is suggestive)
3. Curricula builder for qualification providers and schools (the recommendation algorithm is suggestive for building but not used for teaching)
4. As a standalone fully-personalized continuous educational system ready-made for an interplanetary civilization (the recommendation algorithm is central)

# An (almost) technical specification
## Layer 0: the core
Edion's core. A distributed ledger of sources and learning materials hosted on the IPFS peer-to-peer network. The process of writing, generating, adding and organizing these materials is regulated via layer 1.

The distributed nature of the ledger prevents tampering with learning materials by permanently storing file history.

### Layer 0.alt
Due to copyright restrictions, some materials will have to be hosted by the foundation in a federated network and integrated with layer 1, independently of the materials hosted on IPFS.

## Layer 1: the automated professor
If layer 0 is the textbook, then layer 1 is the professor.

Layer 1 consists of the user-mechanics module, the roadmap configurator, trustless exam proctoring, a mentoring system, plagiarism detection and exercise/exam generation.

### User-mechanics module
The user-mechanics module defines account activity for two types of users. An account may be both types of user.

#### User type 1: student
A student account goes through the initial roadmap configuration and then works through their educational roadmap. The roadmap gets revised after every assignment/assessment submission using the recommendation algorithm.

#### User type 2: educator
There are three educator ranks.

##### Rank 0: supervisor
This rank has access to the progress tracker, class statistics and class blog moderation in the first use case.

This rank may submit resources and assignments to the knowledge ledger (layer 0), but these submissions are revised and approved by educator accounts of rank 1.

##### Rank 1: marker
This rank is privileged to mark complex assignments that cannot be marked algorithmically in the second and fourth use cases. A score must get agreed upon by a plurality of marker accounts first. After an agreement gets reached, the score gets awarded to the student.

Additionally, this rank may review the level of compliance of submitted learning materials before these materials can get added to the knowledge ledger. Similarly to marking, a plurality of marker-ranked accounts must agree on the level of compliance.

##### Rank 2: mentor
This rank has live mentoring privileges and must be a teacher with valid teaching credentials supplied through a decentralized identity management service such as Civic.

### Roadmap configurator
A roadmap is a sequence of meta-blocks consisting of learning materials arranged to make a cohesive learning experience. Each meta-block consists of a block, and each block consists of a sub-block.

In use cases 1-3, the roadmap gets pre-configured for students by schools, with optional suggestions from the recommendation algorithm.

In use case 4, the roadmap gets configured entirely based on preferences and suggestions from the recommendation algorithm.

#### Recommendation algorithm
The recommendation algorithm uses student account data to (1) make roadmap configuration recommendations and (2) improve future recommendations.

The student account data usable for making recommendations consists of an initial set of examinations testing for proficiency in the full range of skills/subjects, a HEXACO model of personality structure completed meta-blocks/blocks/sub-blocks and the level of success, as well as personal preference questionnaires.

### Trustless exam proctoring
If a block includes an examination, this examination has to get proctored. All proctoring solutions available on the market are proprietary and heavily infringe on privacy. Trustless exam proctoring has to be decentralized and does not involve a middle person.

AI takes care of facial recognition, spatial analysis and eye-tracking to spot potential academic dishonesty and reports this potentiality to an educator. The educator does not have access to evidence for academic dishonesty until the student provides it to them themselves along with their case.

Alternatively, the student may choose to retake the exam with a different set of questions.

### Plagiarism detection
For written assignments, a plagiarism detection mechanism is a requirement.

In contrast to plagiarism detectors already on the market (e.g. Turnitin), on Edion, plagiarism detection relies on the IPFS knowledge ledger to sort through all the learning materials and past assignment submissions.

Additionally, the detector parses the clearnet just like the proprietary alternatives.

### Exercise generation
Some exercises and problems may get generated at the time of access. For example, exercises that test for knowledge of physics equations, worded mathematical application exercises, exercises relating to chemical reactions, etc.

Skeletons for such problems will be hosted on the IPFS network (layer 0), while the final exercises get generated in contracts (layer 1).

### Gamification
Edion tokenomics rely heavily on the gamification properties of the system. For students, the Edion token gets earned in proportion to the quality of submitted assignments, block completion and examination scores. For educators, the Edion token gets paid for submitted learning materials, marking and mentoring. Along with the token payments, both types of accounts get exposed to a level-up system, badges, and leaderboards based on location, study categories and age. Tokens may get spent on in-game avatar customization or get withdrawn.

### Incentivization
Although both student and educator accounts earn the Edion token for task completion, the tasks linked to educator accounts pay much more than any student account task. Additionally, only educator accounts that have passed a threshold for task completion have access to a native fiat bridge, enabling them to withdraw their funds directly to their bank account.

Student accounts may withdraw their funds to an exchange that supports the Edion token or spend directly on in-game avatar customization.

### Decentralized autonomous organization (DAO)
Edion runs as a multilevel decentralized autonomous organization based on proof of personhood (PoP). Every account that has passed verification via Civic gains a single vote usable for voting on proposals to the protocols.

Only educator accounts get to vote on proposals related to the educator side of the ecosystem, and only student accounts get to vote on proposals related to the student side of the ecosystem. Similarly, the educators can vote only for the protocol proposals that concern their rank.

### Integrations
Civic, used for identity verification in cases where the student is seeking qualification (use case 1) and for educator ranks marker and above

Jitsi, used for mentoring and unscheduled video calls with an additional VR customizable avatar replicating facial expressions, is available for cases where the student or teacher seeks to retain anonymity.

Matrix, used for chat-functionality on group assignments, resolving academic dishonesty issues and marking appeals

## Layer 2: the user interface
A virtual classroom, consisting of a calendar, chat, unscheduled call functionality and other features, conceived as a decentralized and free/libre and open-source alternative to ManageBac and AtlasNext.

# The philosophy
Edion relies on free/libre and open-source software (FLOSS) exclusively. As an autonomous system without a central governing authority, anyone must have the ability to look at and contribute to the code.

Distribution and decentralization are at the core of Edion. Network models employed must be as distributed as possible to preserve the integrity of the mechanism and the materials.

Since Edion seeks to become the standard for education globally, simplicity and neutrality must be central, both technically and visually, to accommodate scalability, readability and cultural diversity.

---
You can contact Edion's founder by sending an email to **deliev at gjh period sk**.

<a href="http://www.softwarefreedom.org/">
<img src="http://www.softwarefreedom.org/img/support-sflc.png" alt="[frdm] Support SFLC" height="31" width="88" border="0" title="Software Freedom Law Center" />
</a>
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

# PAC's Balloon Team as an Organization
## Structure
### Organizational Design

+ PAC Directors
  + Team Leads
    + Deputy Directors
    + Engineers

It is the engineers and deputy directors that empower and drive the club. Everything above is designed to abstract as much of *funding, recruiting, school coordination, scheduling, etc.* away, so that the engineering teams do not need to deal with these things themselves.

A more detailed description of these roles:
#### PAC Directors 
Guide the overall strategy of the club and work to coordinate operations, financing, and the public-facing needs of the club so that these are abstracted away to the build teams, which can then focus on engineering. They handle most school-club interaction and work to garauntee the continued success of the club.
#### Team Leads
Responsible for coordinating the engineering operations of the team, setting the vision for the project, and recruiting, growing, and maintaining a successful team environment that enables engineers and deputy directors.
#### Deputy Directors
Responsible for helping subteams design and build features that match the vision of the project. They bridge the role of engineering and management as they are fielded for becoming a Team Lead. They are responsible for understanding how different features will interact and for resolving conflicts.
#### Engineers
Responsible for building to ensure a successful project -- whatever the needs of the project are. Though the role is titled *engineer*, people in this core position will find themselves filling the reponsibilities of quite a few roles:

| Role | Description |
| ---| --- |
| Engineers | This is the baseline expectation. There are features to be built! But what determines those features? |
| Product Managers | Engineering subteams are also responsible for deciding what features to build. Doing this requires them to think about their feature in the context of the larger vision of the project and in reference to the other subteams. |
| Field Engineers | In the end, these features will be launched in the balloon -- and we don't have a launch team. Engineers must consider the needs and restrictions of the launch when building their subsystem and be ready to deploy it during launch. |
| Teachers | Part of building a diverse team is the reality that each person comes in with different bases of knowledge. Engineers are expected to be both empowering teachers and good students. Each person is on the team because they have something valuable to contribute, and there is always something to be learned from others. |

---
### Functional Design

Our team is delimited primarily by functional units that define features of the platform:

| Subteam | Description |
| --- | :---------- |
| Core | Responsible for payload structure, integration, and required systems. Every other subteam will find themselves working very closely with Core to garauntee that the payload is built to support their subsystem and the reverse. |
| Altitude Control | Responsible for enabling the payload to support altitude-based maneuvers. This feature is important for gathering good data for experiments / photography and is the first step in enabling lateral manueverability. |
| Experiments | Responsible for carrying out scientific procedures that take advantage of HAB's access to high altitudes, cold temperatures, low pressure, and aptmospheric conditions. Part of successfully building out HAB as a platform is continually validating that it meets the needs of applications built on the platform. |
| Communications | Responsible for guaranteeing conistent 2-way communications throughout the flight. Being able to send and receive constant data streams and commands allows the team to cater to different autonomous needs and enable more complex, ground-based decisions. |
| Sensing / Imaging | Responsible for adding useful sensing data that extends the baseline data streams the platform provides. New integrations empower applications built on the platform and better imaging extends the clubs social reach and ability to provide novel experiences. |

## Meetings

Different meetings play different roles, and often follow a progression. Here is a common development of meetings:

**1. Labs**

In these meetings, a large number of important topics will be covered. Common labs we will run are. These exist to help the team learn important HAB concepts.

 - High Altitude Ballooning
 - Arduino
 - Git
 - Physics
 - Control Theory
 - Launch Ops

**2. Design Meetings**

Here the team will sit down and sketch out what they want to build, which features to implement, and to communicate with other teams to understand what other teams need and how their subsystem fits in the context of the whole. By the end the team should produce a document demonstrating the features and capabilities of their subsystem. This will include technical design aspects.

**3. PDR (Principle Design Review)**

The principle design review is a technical deep dive. Each subsystem will present their design and open themselves up to interrogation, suggestions, and comments. These often include third-party engineers and experts who can look at the subsystems with fresh and critical eyes.

**4. Work Meetings**

In these meetings, subteams will actually build out their features. Early work meetings are meant to be done as a whole team, that way subteams can effectively communicate with each other, and later meetings are meant to be in smaller subteams, at this point parameters are well established and only need to be made.

**5. CDR (Critical Design Review)**

Much like the principle design review, but this is in the later stages of build. This is used to evaluate that the subsystem will work as expected, was not built with any serious flaws, and will be able to effectively integrate in the larger system. Again third-party experts will often be brought in for evaluation.

**6. Integration Meetings**

These meetings should again include the entire engineering team, and will include working to make sure all the subsytems effectively communicate with each other and integrate well. It is here that all the components will be combined and begin communicating with each other. It is here that lots of launch planning will also happen.

**7. Launch**

The grand finale of the project (except it is more of an iterative finale, as launches are quite frequent). We take the integrated box somewhere, attach it to a big balloon, let it go, and chase it down. Enough said ... (see section on HAB).

#### Social Events

- Dinners -- a PAC team is a family, and families not only work, but also eat. 
- After-launch meals and dinners -- Whether or not the balloon lands in a field or a tree, in New Jersey or in the Atlantic Ocean, there is reason to celebrate.
- Day-offs -- Replacing a normal meeting time with something fun or outside. Its always a present surprise.

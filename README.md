# Extensions-for-Open-Courseware
Moodle is a community of academic institutions, commercial organizations and individuals who work together to develop a common Collaboration and Learning Environment.It is also a free, community source, educational software platform distributed under the Educational Community License (a type of open source license) mainly is used for teaching, research and collaboration. Systems of this type are also known as Course Management Systems (CMS), Learning Management Systems (LMS), or Virtual Learning Environments (VLE).

One important aspect that Moodle still lacks so far is support for Open Courseware (OCW). The idea of Open Courseware is to make quality educational content (as taught in institutes of higher learning) public and in reach of every person in world irrespective of geographical and other barriers. The idea was popularized by MIT in 2002 and subsequently many other universities followed suit. Today it has developed into an active movement and organizations such as Open Courseware Consortium are trying to integrate, standardize and further promote such initiatives.

Following are the major goals envisioned for this project:
a) Basic OCW support to enable what content to be made open

b) P2P networking of Moodle installations so that the OCW content can be located

c) Semantic searching of content using ideas like Semantic Overlay Networks

In Peer-to-Peer (P2P) systems, content based full text search is a very challenging problem. There are many traditional approaches to developing a SON which are either centralized or use flooding to ensure accuracy of the results returned. But the major problems with these systems were that if the central server went down all connected nodes would also disconnect thereby resulting in system crash. We then researched on more efficient algorithms namely pSearch, iCluster, pFusion, Chord, CAN and recitations by many different authors to come up with an efficient algorithm to implement in our project. Many of these algorithms were based on forming clusters of nodes having similar content and then searching through these clusters whenever a query cam to speed up the searching process. The nodes are also decentralized thereby no problem of system crashing would occur.

The algorithm, we developed, draws from all of the algorithms we studied. All the nodes are interconnected in a peer-to-peer fashion with some nodes raised to the status of super-peers that handle the flow of queries in the network and manage their own sub-network of nodes. This sub-network is formed on the basis of interests of each node, as classified by a document classification algorithm. This classified grouping of nodes allows to prune out the irrelative nodes and ask only those nodes that are most likely to have the requested file to serve a search query. Hence fast and efficient results are achieved.

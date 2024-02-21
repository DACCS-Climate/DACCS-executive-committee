# Federation

## Introduction

The Marble Network ("Network") is a federated network that consists of independently operated and maintained computing
infrastructure ("Node") that deploy the Marble software stack and connect with one another under the framework laid out
in this document. While anyone is free is deploy the software stack on their own hardware and use it as they choose, in
order to join the Network as a Node, the Node needs to provide certain capabilities and minimum operating standards, as
laid out in this document, and which must be agreed upon by the person(s) responsible for maintaining the Node ("Node
Administrator").

## Principles of Federation

The following sections describe the requirements for operating and maintaining a Node.

### Operations

- Deployment of software stack: Each Node should deploy the Marble software stack. Node Administrators are required to
  upgrade the software stack to the latest Marble stack within two weeks of the updates release date.
- Node maintenance: Node Administrators accept that joining the Network implies that they are responsible for
  provisioning, funding and maintaining their own Node.
- Node security: Node Administrators are responsible for maintaining secure access to their node and for coordinating
  with the hosting institution regarding any security related considerations prior to the deployment of the Node. Admin
  access to the Node must be restricted to listed Node Administrators.
- Downtime policy: A Node should strive to recover from unscheduled downtime as soon as possible. If a Node is
  unexpectedly down, the node administrator must either immediately bring the node back online, or if this is not
  possible, to send out a communication to their users to indicate when the Node should be expected to come back online.
  If a Node needs to be taken offline for scheduled maintenance purposes, the Node Administrator must provide users at
  least 2-weeks notice.
- New user signups: Node Administrators are responsible for the signups of users on their own Nodes. All new signup
  requests should be verified and approved or rejected as soon as possible, ideally within 2 business days.
- Node configuration: The Marble deployment stack consists of core components and optional components. A Node can enable
  or disable non-core components as per the decisions of the Node Administrator. However, when a feature/component is to
  be removed, adequate notice for the change should be given to the Node’s users, ideally at least 2 weeks.

### User Support

Node Administrators are expected to provide technical support to users of their Nodes in a timely manner. This support
must include:

- helping users set up or manage an account on the Node.
- helping users troubleshoot access to services provided by the Node.

This support does not have to include helping users with programming, workflow, or scientific questions.

### User Data and Privacy and Recovery

- Privacy: No Personal Identifying Information belonging to a User can be made accessible to anyone except the User in
  question, the Node Manager and the Executive Committee without explicit written consent of the User in question.
- No User Generated Data can be made accessible to another User without the User’s permission. User Generated Data can
  not be made accessible outside the Network without the User’s permission.

### Data Management and Recovery

- The Node Administrator is required to have a mechanism in place to recover Published Data and User Generated Data in
  case of unexpected data loss. Possible mechanisms could include: RAID, regular back-ups, etc.
- Node Administrator should provide Users at least one-week notice before removing or modifying Published Data from the
  Node.

## Steps to Federation (Joining the Network)

Our aim is to make the process of joining the Network as simple as possible, however, in order to ensure that the
Principles of Federation are met and agreed upon, and in order to ensure that there is no system-wide disruption from
the process of onboarding a new Node, we have outlined the following process:

1. Contact the Executive Committee to indicate you would like to deploy a Node.
    - Create an Issue in the [Node Registry](https://github.com/DACCS-Climate/Marble-node-registry) describing your
      proposed Node.
    - A member of the Executive Committee will contact you for further discussion.
2. Create a Node running the Marble software stack.
3. Integrate the Node into the network by adding your Node information to
   the [Node Registry](https://github.com/DACCS-Climate/Marble-node-registry).

## Defederation

There are two ways a Node can be defederated from the Network: voluntary or forced.

Voluntary removal is instigated by a Node Administrator who submits a request to the Executive Committee for the removal
of the Node (that the Administrator manages) from the Network. In this case, the Executive Committee will work with the
institution hosting the node and the local Node Administrator to work out a solution that would provide minimal
disruption to the users of the Network and assist with the transfer of any unique data to another Node in the Network if
desired. We encourage Node Administrators to provide as much notice as possible of the pending removal of the node to
users and the Executive Committee. Ideally, this should be at least 3 months.

A forced removal of a Node can occur in two situations: if a Node consistently fails to meet the requirements of this
Charter, or if the Node is affecting the stability of the Network. If a Node has consistently failed to meet the
requirements of this Charter, despite all reasonable efforts by the Executive Committee to work with the Node
Administrator to resolve outstanding issues, then the Committee can decide to remove the Node from the Network. The Node
Administrator of a removed Node can re-apply to be part of the Network if all issues have been resolved after the
defederation to the satisfaction of the Executive Committee.
If there is a malfunctioning of a Node that is affecting the stability of the Network, the Executive Committee can,
without delay, remove the Node from the Network on a temporary basis and then work with the Node Administrators to
resolve the issue.

## Definitions

- Executive Committee: the group responsible for oversight of the Marble network
- Network: a federated network that consists of interconnected Marble Nodes
- Node: independently operated and maintained computing infrastructure that deploy the Marble software stack and is
  connected to other nodes in the Marble Network
- Node Administrator: the person(s) responsible for maintaining a Node
- Personal Identifiable Information: data that reveals the identity of a User through direct or indirect means. This may
  include their name, email address, etc.
- Published Data: data that is managed by a Node Administrator and cannot be directly edited by a User
- User: an entity with an account on at least one Node in the Network
- User Generated Data: a work product or data created by a User during the course of using a Node. This includes data
  uploaded to a Node by the User. This may include workflows, scripts, notebooks, processed data, etc.

# Federation

## Introduction

The DACCS Network (“Network”) is a federated network that consists of independently operated and maintained computing
infrastructure (“Node”) that deploy the DACCS software stack and connect with one another under the framework laid out
in this document. While anyone is free is deploy the software stack on their own hardware and use it as they choose, in
order to join the Network as a Node, the Node needs to provide certain capabilities and minimum operating standards, as
laid out in this document, and which must be agreed upon by the person(s) responsible for maintaining the Node (“Node
Administrator”).

## Principles of Federation

The following sections describe the requirements for operating and maintaining a Node.

### Operations

- Deployment of software stack: Each Node should deploy the DACCS software stack. Node Administrators are required to
  upgrade the software stack to the latest DACCS stack within two weeks of the updates release date.
- Node maintenance: Node Administrators accept that joining the Network implies that they are responsible for
  provisioning, funding and maintaining their own Node.
- Node security: Node Administrators are responsible for maintaining secure access to their node and for coordinating
  with
  the hosting institution regarding any security related considerations prior to the deployment of the Node. Admin
  access
  to the Node must be restricted to listed Node Administrators.
- Downtime policy: A Node should strive to maintain downtime of no more than 5%. If a Node needs to be taken offline for
  scheduled maintenance purposes, the Node Administrator must provide users at least 2-weeks notice.
- New user signups: Node Administrators are responsible for the signups of users on their own Nodes. All new signup
  requests should be verified and approved or rejected within 2 business days.
- Node configuration: The DACCS deployment stack consists of core components and optional components. A Node can enable
  or
  disable non-core components as per the decisions of the Node Administrator. However, when a feature/component is to be
  removed, adequate notice for the change should be given to the Node’s users.

### Support and Documentation

A Node should maintain a public web-page with:

1. basic information about the Node,
2. instructions for new users to
   sign up for an account at the Node,
3. basic usage policies (as determined by the Node Administrator), and
4. support information.

We encourage Node Administrators to develop additional documentations and tutorials, if they can,
as it will be of great value to users on that Node and to other users on the Network, but we do not require it.

Node Administrators are expected to provide technical support to users of their Nodes in a timely manner.

### User Data and Privacy

- Privacy: No Personal Identifying Information belonging to a User can be made accessible to anyone except the User in
  question, the Node Manager and the DACCS Executive Committee (“Executive Committee”) without explicit written consent
  of
  the User in question.
- No User Generated Data can be made accessible to another User without the User’s permission. without the user’s
  permission. User Generated Data can not be made accessible outside the Network without the User’s permission.
- Back-up of User Generated Data: The Node Administrator should have a mechanism in place to regularly back up a user’s
  main
  working directory, and have a mechanism in place to retrieve the back-up data upon a user’s request.

### Published Data

Published Data must be discoverable and readable by all Users on a Node. Node Managers are responsible for ensuring that
all published data is recoverable in case of data loss. Node managers should provide Users at least one-week notice
before removing or modifying Published Data from the Node.

## Steps to Federation (Joining the Network)

Our aim is to make the process of joining the Network as simple as possible, however, in order to ensure that the
Principles of Federation are met and agreed upon, and in order to ensure that there is no system-wide disruption from
the process of onboarding a new Node, we have outlined the following process.

1. Submission of an initial proposal to the DACCS EC with the following:
    1. Basic info on the Node
    2. Type of Node. What would be special about the Node?
    3. Funding and support statement
2. Agreement between DACCS EC and Node Admin
3. Deployment of test node with fully functioning front page with documentation and support.
4. Full deployment and integration into the Network

## Defederation

There are two ways a Node can be defederated from the Network: voluntary or forced.

Voluntary removal is instigated by a Node Administrator who submits a request to the Executive Committee for the removal
of the Node (that the Administrator manages) from the Network. In this case, the Executive Committee will work with the
institution hosting the node and the local Node Administrator to work out a solution that would provide minimal
disruption to the users of the Network and assist with the transfer of any unique data to another Node in the Network if
desired.-. We encourage Node Administrators to provide as much notice as possible of the pending removal of the node to
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

- Network: a federated network that consists of interconnected DACCS Nodes
- Node: independently operated and maintained computing infrastructure that deploy the DACCS software stack and is
  connected to other nodes in the DACCS Network
- Node Administrator: the person(s) responsible for maintaining a Node
- Executive Committee: the group responsible for oversight of the DACCS network
- User: an entity with an account on at least one Node in the Network
- User Generated Data: a work product or data created by a User during the course of using a Node. This includes data
  uploaded to a Node by the User. This may include workflows, scripts, notebooks, processed data, etc.
- Personal Identifiable Information: data that reveals the identity of a User through direct or indirect means. This may
  include their name, email address, etc.
- Published Data: data that is managed by a Node Administrator and cannot be directly edited by a User

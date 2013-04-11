OHM Protocol Overview
=====================

The OHM Protocol is subdivided into three essential smaller sub-protocols.  Additionally, there is a set of optional protocols which may be employed but which are not mandatory for a system to be OHM-compliant. The three essential sub-protocols are:

### Structure:
  The Structure protocol provides the core verbs required to perform actions on the Environment's data tree structure.  These commands provide for actions such as creating, modifying, reading, and deleting elements.

### Agent-Session:
	The Agent-Session protocol describes the commands needed for an Agent to manage their session within an Environment.  This includes joining the Environment, binding external services to the session, saving session data, and ending the session.  

### Permissions:
	This protocol establishes the verbs required for discovering and managing the permissions an Agent is granted within the various Elements contained within the Environment data tree.

Together these three protocols provide the baseline functionality required for an Agent to connect to an Environment and successfully interact with it.  Collectively, they can be referred to by the acronym SAP.  

At this time there are two supplemental sub-protocols which are still in the early stage of being defined:

### Remote Administration:
	This protocol provides as set of custom commands for authorized XMPP users to perform administrative actions on the Environment.

### Enviroment-Specific Protocols (ESP):
  ESP provides a set of faculties for defining and utilizing ad-hoc meta-protocols specialized to the needs of a specific Environment.  This allows for a less verbose protocol flow and helps streamline the development process of specialized Environment use cases.

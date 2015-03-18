What is it?

A capability-secure set of data-processing and message passing frameworks based upon E's Elib (http://www.e-rights.org) ported to C++.

Scatter is a rather ambitious project that involves several modules and serveral phases. It is oriented around capability-secure efficient message passing, event management, and availability management in a distributed environment. In the short term it will be a library that will allow easy construction of distributed data processing and message passing components. The First phase will have 4 modules.

What does it include?

Client - The framework for creating a secure listener/observer type system in a distributed environment.

Server - The framework for creating dispatcher type components in a secure distributed environment. (note, in most architectures, nodes will be both client and server, but the distincion is made for clarity)

Registrar - A framework for managing connections between clients and servers, analyzing traffic, optimizing the network, etc. This is often the start point for authorization for foaf type referrals to server nodes.

Core Lib - A set of tools and libraries and additional analogies and abstractions of existing network tasks.

What is it good for?
Scatter can be used for things as simple as task delegation for processor intensive operations. Some of the goals for Scatter are a distributed inference correlation engine, an online game, and a generic work sharing framework. Once in its stable stages, it will have the capabilities for ad-hoc task and resource management, user management and monitoring. So it will, in a sense become a distributed OS.

What platforms will be supported?
The core libs and frameworks will be created in Posix oriented C++, so it will be available for most 
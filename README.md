README DRIVEN DESIGN
# Multi-Tenant and RBAC Membership System for Asp.NET #

> (from wikipedia) Multitenancy refers to a principle in software architecture where a single instance of the software runs on a server, serving multiple client organizations (tenants). Multitenancy is contrasted with a multi-instance architecture where separate software instances (or hardware systems) are set up for different client organizations. With a multitenant architecture, a software application is designed to virtually partition its data and configuration, and each client organization works with a customized virtual application instance.

> (from wikipedia) In computer systems security, role-based access control (RBAC) is an approach to restricting system access to authorized users. It is used by the majority of enterprises with more than 500 employees, and can implement mandatory access control (MAC) or discretionary access control (DAC). RBAC is sometimes referred to as role-based security.

The tenant piece should be fairly straight forward.  A user will belong to one or more tenants.

RBAC put shortly is just a check to see if a user can perform an action granted through participation in a role.  Such as a particular "customer rep" (user) "can update a customers phone number" (FunctionalAbility) because they are a member of "Customer Admins" (role).

A lot of the heavy lifting will be done via the membership provider.


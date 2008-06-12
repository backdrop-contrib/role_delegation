$Id$

README file for the Role Delegation Drupal module.


Description
***********

This module allows site administrators to grant some roles the authority to
assign selected roles to users, without them needing the 'administer access
control' permission.

It provides its own tab in the user profile so that roles can be assigned
without needing access to the user edit form.


See also
********

RoleAssign (http://drupal.org/project/roleassign): Adds a new 'assign roles'
permission to allow assignment of roles by authorized users, without having to
grant them the 'administer access control' permission. Unlike Role Delegation,
RoleAssign provides no way of selecting what roles can be assigned (anyone with
the 'assign roles' permission may assign any of the existing roles to other
users).


Installation
************

1. Extract the 'role_delegation' module directory, including all its
   subdirectories, into your Drupal modules directory.

2. Go to the Administer > Site building > Modules page, and enable the module.

3. Go to the Administer > User management > Access control and scroll down to
   the role_delegation group of permissions. Each role now has a corresponding
   'assign X role' permission. Grant this permission to roles that shall have
   the power to assign role X to users.

If a user has the 'access user profiles' permission and at least one of
role_delegation's 'assign role' permissions, a 'roles' tab appears when visiting
any user's profile page. Roles can be assigned from that tabbed page.


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

RoleAssign (http://drupal.org/project/roleassign).


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


Credits
*******

* Developed by David Lesieur (http://davidlesieur.com,
  http://drupal.org/user/17157) for Bluesponge (http://bluesponge.com).

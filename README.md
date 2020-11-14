Role Delegation
===============

This module allows site administrators to grant some roles the authority to
assign selected roles to users, without them needing the 'administer
permissions' permission.

For each role, Role Delegation provides a new 'assign `<ROLE>` role' permission to
allow the assignment of that role.

The module also adds an 'assign all roles' permission. Enabling this permission
for a role is a convenient way to allow the assignment of any other role without
having to check all the 'assign `<ROLE>` role' permissions in the Permissions
page.

If an administrator has the 'administer users' permission, a role assignment
widget gets displayed in the account creation or editing form, and bulk
add/remove role operations become available on the user administration page.
Otherwise, if s/he has at least the 'access user profiles' permission, the
module adds its own 'Roles' tab to the user profile so that roles can be
assigned.

Installation
------------

Install this module using the official Backdrop CMS instructions at
<https://backdropcms.org/guide/modules>

- Go to the Administer > Configuration > User Accounts > Permissions and scroll
  down to the role_delegation group of permissions. Each role now has a
  corresponding 'assign `<ROLE>` role' permission. Grant this permission to roles
  that shall have the power to assign role ROLE to users.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
<https://github.com/backdrop-contrib/role_delegation/issues>

Current Maintainers
-------------------

- [Kristin Snelling](https://github.com/kelizoliva).
- [Herb v/d Dool](https://github.com/herbdool).

Credits
-------

- Ported to Backdrop CMS by [Kristin Snelling](https://github.com/kelizoliva).
- Maintained for Drupal by [Jeroen Tubex](https://www.drupal.org/u/jeroent).
- Maintained for Drupal by [Ben Dougherty](https://www.drupal.org/u/benjy).

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

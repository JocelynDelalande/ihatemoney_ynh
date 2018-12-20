Yunohost app for Ihatemoney budget web app
==========================================

Supported Yunohost version : 2.7.x

Backs on MySQL database, the identifiers are per-project, not per-user, so no
way to do advanced SSO integration with yunohost accounts.

The behaviour is either:

- **non-public app**:
  - yunohost login required
  - per-project identifiers required
  - any yunohost user with authorized access to the app can create a new
    project).
- **public app** :
  - no yunohost login required
  - per-project identifiers required
  - any visitor can create a new project.

Update
------

To update the app, use:

`sudo yunohost app upgrade ihatemoney -u https://github.com/YunoHost-Apps/ihatemoney_ynh`
  

Maintainer
----------

I rely on
[ihatemoney official releases](https://github.com/spiral-project/ihatemoney/releases)
(tarballs). Don't hesitate to pull-request this repo if I missed one :-).


Ihatemoney license
------------------

> The code is distributed under a BSD beerware derivative: if you meet the
> people in person and you want to pay them a craft beer, you are highly
> encouraged to do so.

[Full license text](https://github.com/spiral-project/ihatemoney/blob/master/LICENSE)


---
id: 6980441b-9485-49c0-85a3-5d58e59a7f7e
title: Users
desc: ''
updated: 1605290156764
created: 1604763626578
---

<!-- CSS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
<!-- jQuery and JS bundle w/ Popper.js -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
<!-- Font Awesome -->
<script src="https://kit.fontawesome.com/489c6dd9c4.js" crossorigin="anonymous"></script>

# Management of users

The list of administrators is available in the page `Users`. This list describes accounts which are inscribed on the platform and their associated informations. It also enables to add/create a new user.

## User profil

An user account is associated to the following informations :

- User name
- First name
- Last name
- Telephone number
- Password
- Email adress

It is possible to activate/desactivate users. A desactivated user is disconnected and can't access the platform anymore.

## Roles

Every user can have one or several roles. Every role gives access to some platform features.

| Role                                      | Customer | Bike messenger | Restaurant | Shop | Admin |
| ----------------------------------------- | :------: | :------------: | :--------: | :--: | :---: |
| To edit his/her own personal informations |    ✔     |       ✔        |     ✔      |  ✔   |   ✔   |
| To create and modify restaurants          |          |                |     ✔      |      |   ✔   |
| Mannage orders                            |          |                |     ✔      |      |   ✔   |
| To edit a receipt                         |          |                |     ✔      |      |   ✔   |
| To create and modify menus                |          |                |     ✔      |      |   ✔   |
| To create shops                           |          |                |            |      |   ✔   |
| To modify shops                           |          |                |            |  ✔   |   ✔   |
| To create a delivery                      |          |                |            |  ✔   |   ✔   |
| To manage deliveries                      |          |       ✔        |            |      |   ✔   |
| To access CoopCycle API                   |          |       ✔        |     ✔      |      |   ✔   |
| To edit roles for users                   |          |                |            |      |   ✔   |
| To edit contracts and tarifications       |          |                |            |      |   ✔   |

## Assignation of a shop/restaurant

On the informations about an user which has the `Restaurant` role, you can assignate him/her (To make him/her owner) a shop that you have previously created. It also works for an user who has a `shop-owner` role.
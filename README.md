Original App Design Project - README Template
===

# SIMPLE_SNAPCHAT

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
A Simple version of Snapchat

### App Evaluation
Evaluation of your app across the following attributes
- **Category:**
- **Mobile:**
- **Story:**
- **Market:**
- **Habit:**
- **Scope:**

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

- [x] User will be able to log in.
- [x] User will be able to show stories of whoever is on the app.
- [x] User will be able to add to/delete from their story.


**Optional Nice-to-have Stories**

- [ ] User will be able to send messages to other users.
- [ ] User will be able to access photos stored on phone.

### 2. Screen Archetypes

* First screen
   * Login page
* Second screen
   * Stream page
   * Stories page
   * camera 

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Stream
* stories
* login/prfile
* camera

**Flow Navigation** (Screen to Screen)

* Stream
   * stories
   * login camera
* Stories
   * stream
   * camera
* Login
    *None

## Wireframes
[Add picture of your hand sketched wireframes in this section]
<img src="YOUR_WIREFRAME_IMAGE_URL" width=600>

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 
### Models
#### Story
|Property |Type |Description  |
|--------|----|-----------|
|object_id  |String |ID for the story object  |
|author|Pointer to User |Author of story  |
|image |File |File used for the story |
|title |String |Caption for story |
|date_added |DateTime |Date the story was posted |

#### User
|Property |Type |Description  |
|--------|----|-----------|
|username |String |Username of user  |
|password |String |Password of user  |
|Name |String |preferred name of user |
|Bio |String |Bio of the user |

### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]

# codedocs.org
CodeDocs Official Website Source Code

[![Build Status](https://travis-ci.org/CodeDocsJECRC/codedocsjecrc.github.io.svg?branch=master)](https://travis-ci.org/CodeDocsJECRC/codedocsjecrc.github.io)

#### Team Members
- The profile page should be in ```people/``` dir, and name as _username.html_
```yml
---
layout: people
title: Name | Team - CodeDocs
description: Name | Team - CodeDocs
id: team
person: Name
designation: Team Member
branch: Branch
img: image #/assets/people/
email: email
facebook: username
twitter: username
github: username
linkedin: username
skills:
  - skill: Skill 1
  - skill: Skill 2
bio: A bio about yourself
---
```
- The team directory list
Mention details in ```_data/team.yml``` file
```yml
- id: username //the same as above created file
  name: Full Name
  img: image name #/assets/people/
  branch: Branch
  role: Team Member
  skills: Skills
```
- The image
The image should be placed in ```/assets/people/``` folder with the same name specified in ```team.yml``` data file and ```/people/name.html``` file.
Recommended size of image - _480x480_


---
layout: post
title: "Understanding Coding Notes"
date: 2023-07-21 08:07:56 +0000
categories: development
banner: https://res.cloudinary.com/dtiwg4oto/image/upload/v1690445906/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2023-07-27_171833_q0ryga.png
tags: coding ui/ux development
---

![Myimage](https://res.cloudinary.com/dtiwg4oto/image/upload/v1690445906/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2023-07-27_171833_q0ryga.png)

To develop Android app, we need 3 elements, which are language, Platform, and tool.

- Language = Kotlin, JAva, C+++. .apk(Android Package), or .aab(Android App Bundle)

### Project Components

- Manifests - defines the structure and metadata of our application, its components, and its requirements.
- Codes
- Resources - images, audio files, and anything relating to the visual presentation of the app (animations, colors, fonts)
- Cradle - build Tool

### Layout Editor

**Palette** : Contains various views and view groups that you can drag into your layout.
**Component Tree** : Shows the hierarchy of components in your layout.
**Toolbar** : Click these buttons to configure your layout appearance in the editor and change layout attributes.
**Design Editor** : Edit your layout in Design view, Blueprint view, or both.
**Attributes** : Controls for the selected view's attributes.
**View mode**: View your layout in either Code , Design , or Split modes. **Split** mode shows both the Code and Design windows at the same time.
**Zoom and pan controls** : Control the preview size and position within the editor.

### Layouts & Widgets

- Layout - ViewGroup as container

- Widget - View Object as element

- Unique ID for almost every Components

- Z- index

![Myimage](https://res.cloudinary.com/dtiwg4oto/image/upload/v1690446858/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2023-07-25_162649_rsdlny.png)

### Constraint Layout

Constrain a widget on the horizontal and vertical axis:

- Horizontal Axis: left, right, start and end sides

- Vertical Axis: top, bottom sides and text baseline

layout_contraint TOP \_to BOTTOM Of image view

- layout_contraint${SIDE}_to${SIDE}Of Asset

to constrain a given side of a widget to another side of any other widget

- Width, Height, Margin, Padding, and Background.

![Myimage](https://res.cloudinary.com/dtiwg4oto/image/upload/v1690446859/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7_2023-07-25_163553_xpr1lz.png)

### Basic Interface

- Toolbar - app actions

- Tabs

- Navigation bar - compact view of the structure

- Editor window - write code

- Project - project(Heirarchy) android(app components)

- Status bar

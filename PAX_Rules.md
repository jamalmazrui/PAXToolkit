---
title: Pax Rules, with Heading Structure for Category, Impact, and Name
author: Jamal Mazrui, Consultant, Access Success LLC
date: July 14, 2024
---

# Pax Rules, with Heading Structure for Category, Impact, and Name

## Table of Contents

- Introduction
- Screens
- Controls
- Gestures
- Navigation
- Forms
- Readability
- Media
- Apps

## Introduction

Central to the Pax framework is a comprehensive, cross-surface set of accessibility rules, with consistent terminology across web, mobile, and desktop surfaces. Pax implements a consistent way of measuring accessibility regardless of the tool for automated testing or the procedure for manual testing.

Pax rules are divided into eight UI categories.  Each may be considered a conceptual lense for identifying accessibility problems that might not otherwise be found.

## Screens

### Critical

#### adjustable-moving-content

Can the user stop moving content, e.g., scrolling, updating, flickering, or animated?

Manual

Check that the screen contains moving content, and if so, whether it can be stopped by either a convenient control or OS shortcut.

#### adjustable-screen-orientation

Can the user set screen orientation to portrait or landscape without loss of functionality?

Hybrid

In a mobile app, after turning the screen 90 degrees, chec that its orientation adjusts to landscape mode, either automatically or via a setting.

#### iframe-name

Does each iframe have a name?

Auto

Check that the iframe has an descriptive name.

#### maximum-flashing-frequency

Is flashing content at most the maximum frequency (3 times per second)?

Manual

Check that the screen contains flashing content, and if so, whether a timer finds the frequency to be more than 3 times per second.

#### maximum-moving-content

Is moving content at most the maximum duration (5 seconds)?

Manual

Check that the screen contains moving content, and if so, whether a timer finds the motion to last more than 5 seconds.

#### no-auto-refresh

Does the screen avoid automatic refreshes?

Hybrid

Check if the screen refreshes automatically after one minute.

#### no-horizontal-scrolling

Is full functionality available, without the need to horizontally scroll, when the screen is zoomed to 400%?

Hybrid

After zooming to about 400%, check that all interactive controls on the screen may be engaged without scrolling horizontally.

#### proper-css

Is CSS coded according to best practice?

Hybrid

Check that CSS syntax follows best practice.

#### proper-html

Is HTML coded according to best practice?

Auto

Check that HTML syntax follows best practice.

#### screen-name

Does the screen have a name?

Auto

Check that the screen has a name.

#### status-message

Is a status message conveyed programmatically without changing focus (e.g., an error notification is available through a combination of cues involving an icon, color, sound, or text)?

Manual

Take an action that results in an error sound and check that a visual cue indicates this condition as well.

With a screen reader active, check that a status message is announced automatically.

#### valid-screen-language

Does the screen designate a valid human language?

Auto

Check that the screen defines the natural language of its content, e.g., the lang attribute of the html tag has a value of en for English.

In a web app, check whether the screen language is explicit and appropriate.


### Major

#### content-warning

Is a user warned in advance of sensitive content that may trigger an emotional reaction?

Manual

Check that the screen contains sensitive content, and if so, whether advance warning makes it avoidable.

#### distinct-screen-name

Is the name of the screen distinct among screens of the app?

Hybrid

Check if more than one screen has the same name.

#### local-help

At a focus point where a user may be unsure of a decision, is context-sensitive help available?

Manual

Check that an adjacent link to help content is available for a control that requires further explanation to an unfamiliar user.

#### valid-css

Does CSS syntax conform to official spec?

Auto

Check that CSS syntax is valid.

#### valid-html

Does HTML syntax conform to official spec?

Auto

Check that HTML syntax is valid.


### Minor

#### proper-screen-name

Is the screen name descriptive of its purpose, succinct in wording, and sequenced with the most inportant information first?

Manual

Check that, without reading content on the screen, its purpose is conveyed by the name.

Check if the screen name is worded in a redundant or verbose manner, and whether its pieces of information are ordered from more to less specific.

## Controls

### Critical

#### adjustable-moving-content

Can the user stop moving content, e.g., scrolling, updating, flickering, or animated?

Manual

Check that the screen contains moving content, and if so, whether it can be stopped by either a convenient control or OS shortcut.

#### adjustable-screen-orientation

Can the user set screen orientation to portrait or landscape without loss of functionality?

Hybrid

In a mobile app, after turning the screen 90 degrees, chec that its orientation adjusts to landscape mode, either automatically or via a setting.

#### iframe-name

Does each iframe have a name?

Auto

Check that the iframe has an descriptive name.

#### maximum-flashing-frequency

Is flashing content at most the maximum frequency (3 times per second)?

Manual

Check that the screen contains flashing content, and if so, whether a timer finds the frequency to be more than 3 times per second.

#### maximum-moving-content

Is moving content at most the maximum duration (5 seconds)?

Manual

Check that the screen contains moving content, and if so, whether a timer finds the motion to last more than 5 seconds.

#### no-auto-refresh

Does the screen avoid automatic refreshes?

Hybrid

Check if the screen refreshes automatically after one minute.

#### no-horizontal-scrolling

Is full functionality available, without the need to horizontally scroll, when the screen is zoomed to 400%?

Hybrid

After zooming to about 400%, check that all interactive controls on the screen may be engaged without scrolling horizontally.

#### proper-css

Is CSS coded according to best practice?

Hybrid

Check that CSS syntax follows best practice.

#### proper-html

Is HTML coded according to best practice?

Auto

Check that HTML syntax follows best practice.

#### screen-name

Does the screen have a name?

Auto

Check that the screen has a name.

#### status-message

Is a status message conveyed programmatically without changing focus (e.g., an error notification is available through a combination of cues involving an icon, color, sound, or text)?

Manual

Take an action that results in an error sound and check that a visual cue indicates this condition as well.

With a screen reader active, check that a status message is announced automatically.

#### valid-screen-language

Does the screen designate a valid human language?

Auto

Check that the screen defines the natural language of its content, e.g., the lang attribute of the html tag has a value of en for English.

In a web app, check whether the screen language is explicit and appropriate.


### Major

#### content-warning

Is a user warned in advance of sensitive content that may trigger an emotional reaction?

Manual

Check that the screen contains sensitive content, and if so, whether advance warning makes it avoidable.

#### distinct-screen-name

Is the name of the screen distinct among screens of the app?

Hybrid

Check if more than one screen has the same name.

#### local-help

At a focus point where a user may be unsure of a decision, is context-sensitive help available?

Manual

Check that an adjacent link to help content is available for a control that requires further explanation to an unfamiliar user.

#### valid-css

Does CSS syntax conform to official spec?

Auto

Check that CSS syntax is valid.

#### valid-html

Does HTML syntax conform to official spec?

Auto

Check that HTML syntax is valid.


### Minor

#### proper-screen-name

Is the screen name descriptive of its purpose, succinct in wording, and sequenced with the most inportant information first?

Manual

Check that, without reading content on the screen, its purpose is conveyed by the name.

Check if the screen name is worded in a redundant or verbose manner, and whether its pieces of information are ordered from more to less specific.

## Gestures

### Critical

#### adjustable-moving-content

Can the user stop moving content, e.g., scrolling, updating, flickering, or animated?

Manual

Check that the screen contains moving content, and if so, whether it can be stopped by either a convenient control or OS shortcut.

#### adjustable-screen-orientation

Can the user set screen orientation to portrait or landscape without loss of functionality?

Hybrid

In a mobile app, after turning the screen 90 degrees, chec that its orientation adjusts to landscape mode, either automatically or via a setting.

#### iframe-name

Does each iframe have a name?

Auto

Check that the iframe has an descriptive name.

#### maximum-flashing-frequency

Is flashing content at most the maximum frequency (3 times per second)?

Manual

Check that the screen contains flashing content, and if so, whether a timer finds the frequency to be more than 3 times per second.

#### maximum-moving-content

Is moving content at most the maximum duration (5 seconds)?

Manual

Check that the screen contains moving content, and if so, whether a timer finds the motion to last more than 5 seconds.

#### no-auto-refresh

Does the screen avoid automatic refreshes?

Hybrid

Check if the screen refreshes automatically after one minute.

#### no-horizontal-scrolling

Is full functionality available, without the need to horizontally scroll, when the screen is zoomed to 400%?

Hybrid

After zooming to about 400%, check that all interactive controls on the screen may be engaged without scrolling horizontally.

#### proper-css

Is CSS coded according to best practice?

Hybrid

Check that CSS syntax follows best practice.

#### proper-html

Is HTML coded according to best practice?

Auto

Check that HTML syntax follows best practice.

#### screen-name

Does the screen have a name?

Auto

Check that the screen has a name.

#### status-message

Is a status message conveyed programmatically without changing focus (e.g., an error notification is available through a combination of cues involving an icon, color, sound, or text)?

Manual

Take an action that results in an error sound and check that a visual cue indicates this condition as well.

With a screen reader active, check that a status message is announced automatically.

#### valid-screen-language

Does the screen designate a valid human language?

Auto

Check that the screen defines the natural language of its content, e.g., the lang attribute of the html tag has a value of en for English.

In a web app, check whether the screen language is explicit and appropriate.


### Major

#### content-warning

Is a user warned in advance of sensitive content that may trigger an emotional reaction?

Manual

Check that the screen contains sensitive content, and if so, whether advance warning makes it avoidable.

#### distinct-screen-name

Is the name of the screen distinct among screens of the app?

Hybrid

Check if more than one screen has the same name.

#### local-help

At a focus point where a user may be unsure of a decision, is context-sensitive help available?

Manual

Check that an adjacent link to help content is available for a control that requires further explanation to an unfamiliar user.

#### valid-css

Does CSS syntax conform to official spec?

Auto

Check that CSS syntax is valid.

#### valid-html

Does HTML syntax conform to official spec?

Auto

Check that HTML syntax is valid.


### Minor

#### proper-screen-name

Is the screen name descriptive of its purpose, succinct in wording, and sequenced with the most inportant information first?

Manual

Check that, without reading content on the screen, its purpose is conveyed by the name.

Check if the screen name is worded in a redundant or verbose manner, and whether its pieces of information are ordered from more to less specific.

## Navigation

### Critical

#### adjustable-moving-content

Can the user stop moving content, e.g., scrolling, updating, flickering, or animated?

Manual

Check that the screen contains moving content, and if so, whether it can be stopped by either a convenient control or OS shortcut.

#### adjustable-screen-orientation

Can the user set screen orientation to portrait or landscape without loss of functionality?

Hybrid

In a mobile app, after turning the screen 90 degrees, chec that its orientation adjusts to landscape mode, either automatically or via a setting.

#### iframe-name

Does each iframe have a name?

Auto

Check that the iframe has an descriptive name.

#### maximum-flashing-frequency

Is flashing content at most the maximum frequency (3 times per second)?

Manual

Check that the screen contains flashing content, and if so, whether a timer finds the frequency to be more than 3 times per second.

#### maximum-moving-content

Is moving content at most the maximum duration (5 seconds)?

Manual

Check that the screen contains moving content, and if so, whether a timer finds the motion to last more than 5 seconds.

#### no-auto-refresh

Does the screen avoid automatic refreshes?

Hybrid

Check if the screen refreshes automatically after one minute.

#### no-horizontal-scrolling

Is full functionality available, without the need to horizontally scroll, when the screen is zoomed to 400%?

Hybrid

After zooming to about 400%, check that all interactive controls on the screen may be engaged without scrolling horizontally.

#### proper-css

Is CSS coded according to best practice?

Hybrid

Check that CSS syntax follows best practice.

#### proper-html

Is HTML coded according to best practice?

Auto

Check that HTML syntax follows best practice.

#### screen-name

Does the screen have a name?

Auto

Check that the screen has a name.

#### status-message

Is a status message conveyed programmatically without changing focus (e.g., an error notification is available through a combination of cues involving an icon, color, sound, or text)?

Manual

Take an action that results in an error sound and check that a visual cue indicates this condition as well.

With a screen reader active, check that a status message is announced automatically.

#### valid-screen-language

Does the screen designate a valid human language?

Auto

Check that the screen defines the natural language of its content, e.g., the lang attribute of the html tag has a value of en for English.

In a web app, check whether the screen language is explicit and appropriate.


### Major

#### content-warning

Is a user warned in advance of sensitive content that may trigger an emotional reaction?

Manual

Check that the screen contains sensitive content, and if so, whether advance warning makes it avoidable.

#### distinct-screen-name

Is the name of the screen distinct among screens of the app?

Hybrid

Check if more than one screen has the same name.

#### local-help

At a focus point where a user may be unsure of a decision, is context-sensitive help available?

Manual

Check that an adjacent link to help content is available for a control that requires further explanation to an unfamiliar user.

#### valid-css

Does CSS syntax conform to official spec?

Auto

Check that CSS syntax is valid.

#### valid-html

Does HTML syntax conform to official spec?

Auto

Check that HTML syntax is valid.


### Minor

#### proper-screen-name

Is the screen name descriptive of its purpose, succinct in wording, and sequenced with the most inportant information first?

Manual

Check that, without reading content on the screen, its purpose is conveyed by the name.

Check if the screen name is worded in a redundant or verbose manner, and whether its pieces of information are ordered from more to less specific.

## Forms

### Critical

#### adjustable-moving-content

Can the user stop moving content, e.g., scrolling, updating, flickering, or animated?

Manual

Check that the screen contains moving content, and if so, whether it can be stopped by either a convenient control or OS shortcut.

#### adjustable-screen-orientation

Can the user set screen orientation to portrait or landscape without loss of functionality?

Hybrid

In a mobile app, after turning the screen 90 degrees, chec that its orientation adjusts to landscape mode, either automatically or via a setting.

#### iframe-name

Does each iframe have a name?

Auto

Check that the iframe has an descriptive name.

#### maximum-flashing-frequency

Is flashing content at most the maximum frequency (3 times per second)?

Manual

Check that the screen contains flashing content, and if so, whether a timer finds the frequency to be more than 3 times per second.

#### maximum-moving-content

Is moving content at most the maximum duration (5 seconds)?

Manual

Check that the screen contains moving content, and if so, whether a timer finds the motion to last more than 5 seconds.

#### no-auto-refresh

Does the screen avoid automatic refreshes?

Hybrid

Check if the screen refreshes automatically after one minute.

#### no-horizontal-scrolling

Is full functionality available, without the need to horizontally scroll, when the screen is zoomed to 400%?

Hybrid

After zooming to about 400%, check that all interactive controls on the screen may be engaged without scrolling horizontally.

#### proper-css

Is CSS coded according to best practice?

Hybrid

Check that CSS syntax follows best practice.

#### proper-html

Is HTML coded according to best practice?

Auto

Check that HTML syntax follows best practice.

#### screen-name

Does the screen have a name?

Auto

Check that the screen has a name.

#### status-message

Is a status message conveyed programmatically without changing focus (e.g., an error notification is available through a combination of cues involving an icon, color, sound, or text)?

Manual

Take an action that results in an error sound and check that a visual cue indicates this condition as well.

With a screen reader active, check that a status message is announced automatically.

#### valid-screen-language

Does the screen designate a valid human language?

Auto

Check that the screen defines the natural language of its content, e.g., the lang attribute of the html tag has a value of en for English.

In a web app, check whether the screen language is explicit and appropriate.


### Major

#### content-warning

Is a user warned in advance of sensitive content that may trigger an emotional reaction?

Manual

Check that the screen contains sensitive content, and if so, whether advance warning makes it avoidable.

#### distinct-screen-name

Is the name of the screen distinct among screens of the app?

Hybrid

Check if more than one screen has the same name.

#### local-help

At a focus point where a user may be unsure of a decision, is context-sensitive help available?

Manual

Check that an adjacent link to help content is available for a control that requires further explanation to an unfamiliar user.

#### valid-css

Does CSS syntax conform to official spec?

Auto

Check that CSS syntax is valid.

#### valid-html

Does HTML syntax conform to official spec?

Auto

Check that HTML syntax is valid.


### Minor

#### proper-screen-name

Is the screen name descriptive of its purpose, succinct in wording, and sequenced with the most inportant information first?

Manual

Check that, without reading content on the screen, its purpose is conveyed by the name.

Check if the screen name is worded in a redundant or verbose manner, and whether its pieces of information are ordered from more to less specific.

## Readability

### Critical

#### adjustable-moving-content

Can the user stop moving content, e.g., scrolling, updating, flickering, or animated?

Manual

Check that the screen contains moving content, and if so, whether it can be stopped by either a convenient control or OS shortcut.

#### adjustable-screen-orientation

Can the user set screen orientation to portrait or landscape without loss of functionality?

Hybrid

In a mobile app, after turning the screen 90 degrees, chec that its orientation adjusts to landscape mode, either automatically or via a setting.

#### iframe-name

Does each iframe have a name?

Auto

Check that the iframe has an descriptive name.

#### maximum-flashing-frequency

Is flashing content at most the maximum frequency (3 times per second)?

Manual

Check that the screen contains flashing content, and if so, whether a timer finds the frequency to be more than 3 times per second.

#### maximum-moving-content

Is moving content at most the maximum duration (5 seconds)?

Manual

Check that the screen contains moving content, and if so, whether a timer finds the motion to last more than 5 seconds.

#### no-auto-refresh

Does the screen avoid automatic refreshes?

Hybrid

Check if the screen refreshes automatically after one minute.

#### no-horizontal-scrolling

Is full functionality available, without the need to horizontally scroll, when the screen is zoomed to 400%?

Hybrid

After zooming to about 400%, check that all interactive controls on the screen may be engaged without scrolling horizontally.

#### proper-css

Is CSS coded according to best practice?

Hybrid

Check that CSS syntax follows best practice.

#### proper-html

Is HTML coded according to best practice?

Auto

Check that HTML syntax follows best practice.

#### screen-name

Does the screen have a name?

Auto

Check that the screen has a name.

#### status-message

Is a status message conveyed programmatically without changing focus (e.g., an error notification is available through a combination of cues involving an icon, color, sound, or text)?

Manual

Take an action that results in an error sound and check that a visual cue indicates this condition as well.

With a screen reader active, check that a status message is announced automatically.

#### valid-screen-language

Does the screen designate a valid human language?

Auto

Check that the screen defines the natural language of its content, e.g., the lang attribute of the html tag has a value of en for English.

In a web app, check whether the screen language is explicit and appropriate.


### Major

#### content-warning

Is a user warned in advance of sensitive content that may trigger an emotional reaction?

Manual

Check that the screen contains sensitive content, and if so, whether advance warning makes it avoidable.

#### distinct-screen-name

Is the name of the screen distinct among screens of the app?

Hybrid

Check if more than one screen has the same name.

#### local-help

At a focus point where a user may be unsure of a decision, is context-sensitive help available?

Manual

Check that an adjacent link to help content is available for a control that requires further explanation to an unfamiliar user.

#### valid-css

Does CSS syntax conform to official spec?

Auto

Check that CSS syntax is valid.

#### valid-html

Does HTML syntax conform to official spec?

Auto

Check that HTML syntax is valid.


### Minor

#### proper-screen-name

Is the screen name descriptive of its purpose, succinct in wording, and sequenced with the most inportant information first?

Manual

Check that, without reading content on the screen, its purpose is conveyed by the name.

Check if the screen name is worded in a redundant or verbose manner, and whether its pieces of information are ordered from more to less specific.

## Media

### Critical

#### adjustable-moving-content

Can the user stop moving content, e.g., scrolling, updating, flickering, or animated?

Manual

Check that the screen contains moving content, and if so, whether it can be stopped by either a convenient control or OS shortcut.

#### adjustable-screen-orientation

Can the user set screen orientation to portrait or landscape without loss of functionality?

Hybrid

In a mobile app, after turning the screen 90 degrees, chec that its orientation adjusts to landscape mode, either automatically or via a setting.

#### iframe-name

Does each iframe have a name?

Auto

Check that the iframe has an descriptive name.

#### maximum-flashing-frequency

Is flashing content at most the maximum frequency (3 times per second)?

Manual

Check that the screen contains flashing content, and if so, whether a timer finds the frequency to be more than 3 times per second.

#### maximum-moving-content

Is moving content at most the maximum duration (5 seconds)?

Manual

Check that the screen contains moving content, and if so, whether a timer finds the motion to last more than 5 seconds.

#### no-auto-refresh

Does the screen avoid automatic refreshes?

Hybrid

Check if the screen refreshes automatically after one minute.

#### no-horizontal-scrolling

Is full functionality available, without the need to horizontally scroll, when the screen is zoomed to 400%?

Hybrid

After zooming to about 400%, check that all interactive controls on the screen may be engaged without scrolling horizontally.

#### proper-css

Is CSS coded according to best practice?

Hybrid

Check that CSS syntax follows best practice.

#### proper-html

Is HTML coded according to best practice?

Auto

Check that HTML syntax follows best practice.

#### screen-name

Does the screen have a name?

Auto

Check that the screen has a name.

#### status-message

Is a status message conveyed programmatically without changing focus (e.g., an error notification is available through a combination of cues involving an icon, color, sound, or text)?

Manual

Take an action that results in an error sound and check that a visual cue indicates this condition as well.

With a screen reader active, check that a status message is announced automatically.

#### valid-screen-language

Does the screen designate a valid human language?

Auto

Check that the screen defines the natural language of its content, e.g., the lang attribute of the html tag has a value of en for English.

In a web app, check whether the screen language is explicit and appropriate.


### Major

#### content-warning

Is a user warned in advance of sensitive content that may trigger an emotional reaction?

Manual

Check that the screen contains sensitive content, and if so, whether advance warning makes it avoidable.

#### distinct-screen-name

Is the name of the screen distinct among screens of the app?

Hybrid

Check if more than one screen has the same name.

#### local-help

At a focus point where a user may be unsure of a decision, is context-sensitive help available?

Manual

Check that an adjacent link to help content is available for a control that requires further explanation to an unfamiliar user.

#### valid-css

Does CSS syntax conform to official spec?

Auto

Check that CSS syntax is valid.

#### valid-html

Does HTML syntax conform to official spec?

Auto

Check that HTML syntax is valid.


### Minor

#### proper-screen-name

Is the screen name descriptive of its purpose, succinct in wording, and sequenced with the most inportant information first?

Manual

Check that, without reading content on the screen, its purpose is conveyed by the name.

Check if the screen name is worded in a redundant or verbose manner, and whether its pieces of information are ordered from more to less specific.

## Apps

### Critical

#### adjustable-moving-content

Can the user stop moving content, e.g., scrolling, updating, flickering, or animated?

Manual

Check that the screen contains moving content, and if so, whether it can be stopped by either a convenient control or OS shortcut.

#### adjustable-screen-orientation

Can the user set screen orientation to portrait or landscape without loss of functionality?

Hybrid

In a mobile app, after turning the screen 90 degrees, chec that its orientation adjusts to landscape mode, either automatically or via a setting.

#### iframe-name

Does each iframe have a name?

Auto

Check that the iframe has an descriptive name.

#### maximum-flashing-frequency

Is flashing content at most the maximum frequency (3 times per second)?

Manual

Check that the screen contains flashing content, and if so, whether a timer finds the frequency to be more than 3 times per second.

#### maximum-moving-content

Is moving content at most the maximum duration (5 seconds)?

Manual

Check that the screen contains moving content, and if so, whether a timer finds the motion to last more than 5 seconds.

#### no-auto-refresh

Does the screen avoid automatic refreshes?

Hybrid

Check if the screen refreshes automatically after one minute.

#### no-horizontal-scrolling

Is full functionality available, without the need to horizontally scroll, when the screen is zoomed to 400%?

Hybrid

After zooming to about 400%, check that all interactive controls on the screen may be engaged without scrolling horizontally.

#### proper-css

Is CSS coded according to best practice?

Hybrid

Check that CSS syntax follows best practice.

#### proper-html

Is HTML coded according to best practice?

Auto

Check that HTML syntax follows best practice.

#### screen-name

Does the screen have a name?

Auto

Check that the screen has a name.

#### status-message

Is a status message conveyed programmatically without changing focus (e.g., an error notification is available through a combination of cues involving an icon, color, sound, or text)?

Manual

Take an action that results in an error sound and check that a visual cue indicates this condition as well.

With a screen reader active, check that a status message is announced automatically.

#### valid-screen-language

Does the screen designate a valid human language?

Auto

Check that the screen defines the natural language of its content, e.g., the lang attribute of the html tag has a value of en for English.

In a web app, check whether the screen language is explicit and appropriate.


### Major

#### content-warning

Is a user warned in advance of sensitive content that may trigger an emotional reaction?

Manual

Check that the screen contains sensitive content, and if so, whether advance warning makes it avoidable.

#### distinct-screen-name

Is the name of the screen distinct among screens of the app?

Hybrid

Check if more than one screen has the same name.

#### local-help

At a focus point where a user may be unsure of a decision, is context-sensitive help available?

Manual

Check that an adjacent link to help content is available for a control that requires further explanation to an unfamiliar user.

#### valid-css

Does CSS syntax conform to official spec?

Auto

Check that CSS syntax is valid.

#### valid-html

Does HTML syntax conform to official spec?

Auto

Check that HTML syntax is valid.


### Minor

#### proper-screen-name

Is the screen name descriptive of its purpose, succinct in wording, and sequenced with the most inportant information first?

Manual

Check that, without reading content on the screen, its purpose is conveyed by the name.

Check if the screen name is worded in a redundant or verbose manner, and whether its pieces of information are ordered from more to less specific.



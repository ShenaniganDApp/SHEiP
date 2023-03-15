---
SHEiP: SHEiP-5
title: Development: DAOH3 Website
author: Vict0xr (@youngkidwarrior)
discussions-to: N/A
status: Draft
category: Improvement
type: Development
created: 2023-03-14
edited: N/A
---

## Simple Summary

This SHEiP proposes the implementation of a website for the SHE Hash House Harriers DAO, DAOH3 to streamline event organization, registration, and communication among members.

## Abstract

The DAOH3 Hash House Harriers group requires a dedicated website to facilitate event organization, registration, and communication among members. This SHEiP outlines the technical specifications, design, and development of the website, focusing on a user-friendly interface to promote event attendance.

## Motivation

The primary motivation for building the DAOH3 website is to effectively promote and spread the word about the group's events, attracting new participants and enhancing the overall experience for existing members. A dedicated website will centralize event information, improve accessibility, and create a cohesive online presence for the group.

## Specification

The website will consist of the following features:

1. Homepage: An overview of the DAOH3 Hash House Harriers group, including its mission, history, and upcoming events.
2. Events: A calendar of scheduled events, with detailed information on each event, including location, time, and organizer contact details.
3. Registration: A secure registration system for events, requiring user authentication and integration with DAOH3 multisig and On-chain Delaware UNA for beer donations.
4. Members Area: A dedicated section for registered members, including a forum for discussions, a gallery of past events, and member profiles.
5. Contact Us: A contact form for inquiries or feedback.
6. Discord Integration: Include a link to the SHE Discord at the top of the website for easy access to the community.

The website will be developed using the Astro framework and hosted on Netlify.

## Rationale

A dedicated website for the DAOH3 Hash House Harriers group will effectively promote events and create a cohesive online presence for the group. The proposed features are designed to address the group's current challenges, and the chosen development technologies are widely supported and appropriate for the project's scope.

## Backwards Compatibility

This SHEiP does not introduce any backwards incompatibilities as it proposes the development of a new website.

## Implementation

[Check Out the website](https://github.com/ShenaniganDApp/DAO-H3)

The website will be developed in stages:

1. [Design](<(https://www.figma.com/file/IuEzwYqfrJdLD70zKu9iwq/SHE-x-Raid-Brood-Assets?node-id=0:1&t=EOxWGoGhe3ebpK8F-0)>): Use the provided Figma design file to create the website layout and user interface.
2. [Development](https://github.com/ShenaniganDApp/DAO-H3): Write the Astro framework code for the website, implementing the features outlined in the specification and ensuring compatibility with Netlify hosting.
3. Testing: Test the website on various devices and browsers, ensuring compatibility and responsiveness.
4. [Deployment](https://hash.she.energy): Launch the website on Netlify using the domain.
5. Maintenance: Ongoing updates and improvements based on user feedback and group needs.

## Security Considerations

Security is a crucial aspect of the proposed website, particularly concerning the registration system and user data. The website will implement secure authentication protocols, encryption, and secure payment processing. Regular security audits and updates will ensure that the website remains secure and up-to-date with industry standards.

## Copyright

Copyright and related rights waived via CC0.

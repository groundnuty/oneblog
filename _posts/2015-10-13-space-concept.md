---
layout: post
title: Onedata Spaces
---

We all are used to our file being accessible to us via. our laptops, tablets or mobiles, regardless of where or when we want to access them. It's difficult to find a person who never stored or shared their data on a service like Dropbox, GoogleDrive, Box, or OneDrive; and while those are perfect for sharing photos, documents or video; they fail to meet performance execrations when it comes to swiftly accessing big volumes of data.

## What is a Space?

To address this problem, in Onedata we introduced a concept of Space. Similarly to services mentioned, a Space is a virtual directory where user can store his data and share it with others (link do dokumentacji o sherowaniu). However it's where similarities end! Each user can create multiple Spaces and regulate sharing and access rights to the Space  in a much more detailed fashion (link do dokumentacji). Spaces work well with big data volumes and are meant for high performance data access, they allow users to collaborate on huge datasets regardless of their location.

## Space collaboration 

Since big datasets are rarely used only by one person, users can form Groups (link do dokumentacji) and share their Spaces with other Groups. For instance a team of researchers working with cancer data has been given a read-only access to a Space governed by doctors at a city Hospital where they upload high-resolution images of cancer cells. Managing complex access rights to your data has never been easier!

## Increase Space size 

Big data volumes, require tones of storage space - preferably close to the source of the data. Since Onedata is a data access platform, we actually do not provide any physical storage Space. When created a Space has actually no physical space attached to it (0MB). Each Space is characterized by a unique token. Than token can be used to request a storage space with one of OneData Providers - again preferably one hosted in a datacenter near your location. (list of Onedata Providers currently available in Europe).




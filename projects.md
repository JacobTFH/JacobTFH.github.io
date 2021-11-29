---
layout: page
title: "Projects"
---


# Projects

[Home](index.md) / [Strummi](#the-strummi) / [RePlay](#replay-musical-instrument-for-stroke-rehabilitation) / [Adapted Bass Guitar](#adapted-bass-guitar)

## Strummi

<iframe width="560" height="315" src="https://www.youtube.com/embed/wUR-tp6DT4I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

_Strummi_ is a guitar-based Accessible Digital Musical Instrument _(ADMI)_ designed to make guitar playing more physically accessible while preserving the tactile and acoustic response of real guitar strings.
It was developed as part of my PhD research at Queen Mary University of London, with my co-researcher Robert Jack.
It runs on c++ on the [Bela](https://bela.io/) environment.

_Strummi_ was influenced by instruments such as the [Kalichord](https://blog.bela.io/2017/05/15/kalichord/) and [BladeAxe](https://ccrma.stanford.edu/~rmichon/bladeaxe/).
It uses the real acoustic signal from dampened guitar strings to excite a physical model of a vibrating string.
The resulting sound is quite realistic and allows for a lot of the subtleties of string plucking gestures to be preserved.
The benefit of doing it this way rather than using full-length acoustic guitar strings is that the tuning is done digitally, so the strings can be very short.
This gives us a lot of flexibility in terms of the shape and size of the instrument, and the method for changing chords and notes.

It has been used in a number of research projects as well as community music sessions and live performances.
We are hoping to continue developing the Strummi and hope to work with disabled musicians to develop the design and see it on stage.

The Strummi appears in the following publications:

Harrison, Jacob, Robert H. Jack, Andrew P. McPherson 2018. “When is a Guitar not a Guitar? Cultural Form, Input Modality and Expertise” Proceedings of the International Conference on New Interfaces for Musical Expression (NIME) [Download](http://www.eecs.qmul.ac.uk/~andrewm/jharrison_nime2018.pdf)

Jack, Robert H., Jacob Harrison, Andrew P. McPherson 2018. “Democratising DMIs: the relationship of expertise and control intimacy” Proceedings of the International Conference on New Interfaces for Musical Expression (NIME) [Download](https://www.researchgate.net/publication/324390561_Democratising_DMIs_the_relationship_of_expertise_and_control_intimacy)

Harrison, Jacob, Alan Chamberlain, Andrew P. McPherson 2019. “Accessible Instruments in the Wild: Engaging with a Community of Learning-Disabled Musicians” Proceedings of the International Conference on Human Factors in Computing (CHI) [Download](https://dl.acm.org/doi/10.1145/3290607.3313037)

Jack, Robert H., Jacob Harrison, Andrew P. McPherson 2020. “DMIs as Research Products” Proceedings of the International Conference on New Interfaces for Musical Expression (NIME) [Download](http://instrumentslab.org/data/jacob/DMIs_Research_Products.pdf)

[Strummi Github Repository](https://github.com/JacobTFH/Strummi)

[Back to top](#projects)

## RePlay: Musical instrument for stroke rehabilitation

<iframe src="https://player.vimeo.com/video/403623242" width="560" height="315" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

The _RePlay_ study is an ongoing collaborative project between Queen Mary University of London and CWPlus at Chelsea and Westminster Hospital.
Working with Robert Jack and Andrew McPherson at the [Augmented Instruments Lab](http://instrumentslab.org/) and Andrew Hall from [CWPlus](https://www.cwplus.org.uk/), we developed an instrument designed to support stroke rehabilitation exercises for upper limb impairments.
Drawing on the expertise of the occupational therapists at the Nell Gwynne stroke ward, we designed an instrument based on a harp which would encourage patients to practice arm extension exercises for broad 'strums' and finer motor skills for individual 'plucks'.
The instrument uses a large number of touch-sensitive brass rods, each one filed and polished to varying sizes.
The layout of the rods enables patients to strum chords and arpeggios by focusing on the larger rods, and pluck melodies from other degrees of the scale on the smaller rods embedded in between.
Our goal was to ensure that the instrument didn't have the appearance of a piece of medical equipment, instead aiming for an 'heirloom' quality, using materials such as wood and brass, and obscuring the embedded digital technology inside.

The project has unfortunately been postponed since March 2020 due to the Covid-19 pandemic, but we are looking forward to collecting more data from the patients and staff when it is safe to do so.

[Click here](https://www.cwplus.org.uk/blog/2020/04/03/the-replay-study/) for more information on the Replay project.

[Back to top](#projects)

## Adapted Bass Guitar

<iframe width="560" height="315" src="https://youtu.be/k6tvavgYHDA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

In summer 2016 I worked with the [OHMI Trust](https://www.ohmi.org.uk/) on a design project concerned with adapting the bass guitar for one-handed playing.
While some previous approaches to one-handed guitar playing rely on using a robotic picking hand, we wanted to give the performer the high degree of control over the expressivity of the sound that can be conveyed by the right hand.
For this reason we designed an instrument that combines the picking hand of the performer with a mechanical fretting device.
Inspired by musical robotics projects, we decided to design and build a prototype solenoid-actuated fretting mechanism, which attaches to the neck of a bass guitar.
The mechanism is controlled via MIDI, which allows a range of controllers to be used.
As it’s a prototype device we only used six solenoid motors on the 2nd 3rd and 4th frets of the A and D strings.

Read more about the _Adapted Bass_ in the [Journal of New Music Research](https://www.tandfonline.com/doi/abs/10.1080/09298215.2017.1340485) or on the [Bela blog](https://blog.bela.io/2017/02/01/making-the-one-handed-bass-with-bela/)

This project was featured in the [BBC Teach](https://www.youtube.com/watch?v=0lA4Oppg4UM) series _Computer Science: Problem Solved_.

[Back to top](#projects)

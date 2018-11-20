---
permalink: /ac18-intro/
title: "Brief Introduction with a block diagram of a typical communication system"
excerpt: "This is a page not in the main menu"
author_profile: true
redirect_from: 
  - "/intro/"
  - "/intro.html"
---


<iframe width="100%" height="300" src="//jsfiddle.net/cZxey/75/embedded/result/" allowfullscreen="allowfullscreen" allowpaymentrequest frameborder="0"></iframe>
A typical communication system starts with the concept of a source of information, which outputs that information of interest which you want to send somewhere. Typically, this information will first have to be converted into electrical form through appropriate transducer. This source of information after its electrical conversion is given to a system, some equipment, which at the moment; we will simply call a transmitter. And the job of the transmitter is to prepare this information for actually sending through some physical medium through which the propagation of the information has to take place.

> So, in a sense the transmitter matches the characteristics of the signal which is coming from the information source to the characteristics of the medium, through which the information has to be transmitted so that, efficient transmission is possible.
The physical medium through which we transmit this information is called the channel. At the other end we have a receiver, whose job is to ensure that the information is given to the information us in a nice form so that, we can interpret it properly or we can use it for whatever purpose we want to use it.

So in a communication system, there are these five major blocks of which the most important components are information source, transmitter, channel, receiver and information user.

> Receiver’s job is to undo some harmful degradations that might have taken place, while the signal has been transmitted through the channel. Also additionally, it will try to amplify the signals, because typically signal will attenuate as it propagates, it has to remove noise; it also has to remove other kinds of interference.

### Information source:

There can be many kinds of sources of information - speech or voice, motion pictures (TV), still pictures (facsimile), data from and to computers and so on.

Each of these kinds of information source has different kinds of requirements from the communication system, through which it must be passed so that, effective communication can take place.

One of the important features of information sources that is particularly relevant to the discussion on communication systems is the spectral band. If it is a non-deterministic signal or a random signal it is usually better to talk not about the spectrum of signal, but about the power spectrum of the signal.

For telephonic communication most of the intelligence as well as essence of speech, without losing much on either the intelligence or the quality of speech between 300 hertz to about 3300 hertz. So, that is why we say that a voice bound channel has a bandwidth of about 4 kilohertz, that 4 kilohertz includes some guard band, some additional frequency band to make sure that we do not lose anything.

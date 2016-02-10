![alt text](https://github.com/bitDubai/media-kit/blob/master/MediaKit/Fermat%20Branding/Fermat%20Logotype/Fermat_Logo_3D.png "Fermat Logo")

# Welcome to the Fermat APPs Queue

## Introduction

Fermat is designed to easily build Android APPs running on top of the Fermat Framework. We call these APPs _Fermat APPs_. Anybody can code these APPs, but in the early stage where the Fermat project currently is, _Fermat APPs_ are not so easy to build since all the tools we expect to build to streamline the process are not ready yet.

At the same time, we need real world APPs to be running in order to fine-tune the underlaying mechanisms of the Fermat Framework. For that reason the same network of developers building Fermat is willing to write the code of the first set of Fermat APPs in order to stress test the overall architecture of the system.

We managed a queue of third party APPs to be coded by ourselves as a way of bootstraping the system. 


### Who can add candidate APPs to the queue? 

Any industry member that has a service running can add a candidate APP to the queue. The @fermat-apps-queue-team will evaluate the candidate APPs and assign a weight according to how well it fits into Fermat's strategy at this stage; other considerations are detailed below. This weight repositions the candidate on the queue or waiting list. When a dev-team is ready to process the next APP on the queue it will start working on the one positioned first.

## The Queue

|Startup|Project Name|Version|Status|Weight|Bounty|Own Devs|Description|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Digicoins|Exchange Wallet|1|Started|80||0|Multi-currency exchange users wallet|
|Digicoins|Exchange Wallet|2|Next in Queue|||0|Mobile registration|
|Digicoins|Exchange Wallet|3|Queued|||0|Local accounts features|
|Digicoins|Merchant Wallet|1|Queued|||0|Merchat wallet with product catalog|
|Digicoins|Exchange Wallet|4|Queued|||0|Merchat discovery and interaction|
|Tatiana|Artist Platform|1|Queued|||0|Artist APP|
|Tatiana|Artist Platform|2|Queued|||0|Artist Fan APP|
|Paint All Over Me|Digital Asset Store|1|Queued|||0|Shop for Selling Digital Assets|
|Paint All Over Me|Digital Asset Store|2|Queued|||0|Shoppers APP|
|Paint All Over Me|Digital Asset Store|3|Queued|||0|Redeem Points APP|

## The Rules

### Adding a Fermat APP candidate to the Queue

Open an Issue in this repo and follow this steps carefully:

* At the subject, state your startup name and mention that you are requesting to add a project to the queue.
* At the message body give a brief description of what your APP needs to do. Don't forget to tag the @fermat-apps-queue-team to call our attention.

This issue will start the process of adding your APP to the queue. After a short exchange your APP should be added.

### Setting the weight

To estimate the weight the @fermat-apps-queue will usually consider how reusable the components needed to be built for your Fermat APPs are. The more reusable, the bigger the weight. If you need several components specifically for you, consider offering a cash bounty for your own developers to help with those cases.

### Project partitioning

Projects will usually be partitioned in more than one part. This makes the development process easier for everyone. The first part is usually the MVP (Minimun Viable Product). Each part of the project will be queued independently as they represent different versions of your Fermat APP. 

### Offering a bounty

You are free to offer a cash bounty for your APP to be processed faster. Remember this is an open source project and bounty programs are a common mechanism to get things done. The bounty will impact on the weight assigned to your project. Consider a bounty to support a functionality that is unique to your use cases or that cannot be reused easily.

### Fermat APP components

All Fermat APPs are built with reusable components. This means that in order to build yours, we are going to reuse whatever fits in your project. At the same time many of the new components built are not going to be specific for your APP. In fact we expect to build as little specific components as possible. Usually what is specific is the component representing the user interface, and the component accesing your back end web services. The rest are either components already built or intended to be reused later.

### Involving your developers

If you want to, you can also get your own developers involved in building your Fermat APP. This will help you later, to be in control of the source code of your APP.


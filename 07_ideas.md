---
layout: default
title: Project ideas
permalink: ideas.html
---

This is the list of ideas for projects that contribute to Duckietown
for **Google Summer of Code 2018**.

They are calibrated for about 12 weeks of almost-full-time (35 hours/week) work.

## Mentors for GSoC

Mentors will be professors, postdoctoral researchers, and senior Ph.D. students at the universities in which the Duckietown development took place.

The senior mentors and contact persons are:
prof. Liam Paull (University of Montréal),
Dr. Andrea Censi (ETH Zürich),
Dr. Jacopo Tani (ETH Zürich),
prof. Nick Wang (National Chiao Tung University, Taiwan),
prof. Matthew Walter (Toyota Technological Institute at Chicago, USA).
In addition, we have 2-3 mentors at each of the above institutions.

We plan to assign the students to mentors based on a combination of interest matches and time zones (so that they can easily communicate over chat).

## Description of pre-requisites and skills

We use the following tags to discuss the projects:

* <span class="SW"/>: These are projects for which it is necessary to have **good Python skills**.
* <span class="SWP"/>: These are infrastructure projects that require having **advanced software engineering background**, including knowledge of continuous integration.
* <span class="AI"/>: For these, you need to know or learn the required **AI/robotics/computer vision** techniques. At least an advanced undergraduate preparation is necessary.
* <span class="AIP"/>: These are projects that are close to the state of the art. A **graduate-level education in CS, EE, machine learning,** or similar discipline is required.
* <span class="PHY"/>: For these projects, it is essential to work with a physical Duckiebot.
* <span class="PHYP"/>: For these projects, it is essential to work with a physical Duckiebot, and it is necessary to have some space to build a Duckietown or portions thereof.
* <span class="EDU"/>: These projects are tailored to improving the educational contribution.

## Projects about performance optimization

Performance optimization projects are relatively easy. You have some functionality already implemented. You need to make it more efficient, while the unit tests continue to pass. Easy!

<div class='idea' markdown='1'>

### Improving the performance of the line detection

Motivation:

<span class="bronze"/>

<span class="silver"/>

<span class="gold"/>

<span class="SW"/>

</div>

## Projects to implement new functionality or behaviors

<div class='idea' markdown='1'>

### When Duckiebot meets RobotX Challenge

RobotX challenge is the competition for autonomous surface and underwater vehicles initiated by the Office of Naval Research (ONR) and ran by the Association of Unmanned Vehicle System International (AUVSI). The next competition will be in Hawaii in Dec 2018. Can we use Duckietown to train students to get ready for RobotX? We aim to design RobotX-like scenarios for a Duckiebot to accomplish!

<span class="bronze"/>

<span class="silver"/>

<span class="gold"/>

<span class="SWP"/>

</div>


<div class='idea' markdown='1'>

### Duckiebots Taking on Driving Tests

Human novice drivers need to pass the driving road tests in order to get a license. Can a self-driving vehicle achieve the same tasks? We will use a 1/16 sized testing environment including various tasks, such as parking, S-shaped curved road, stop sign, ramp, and etc. Such environments allow us to examine the level of autonomy and robustness of a self- driving vehicle. 

<span class="bronze"/>

<span class="silver"/>

<span class="gold"/>

<span class="SWP"/>

</div>

<div class='idea' markdown='1'>

### Multi-Duckiebot Patrolling 

It is known that multi-robot experiments are typically performed in simulation or with limited amount of real robots. Nevertheless, in real world the location of each robot may be uncertain, and each of them may encounter unexpected delays, making the patrolling problem challenging. We wish to use a fleet of Duckiebots to work together and achieve a goal autonomously in semi-structured environments. 

<span class="bronze"/>

<span class="silver"/>

<span class="gold"/>

<span class="SWP"/>

</div>

## Projects on the User Interface

<div class='idea' markdown='1'>

### Increasing user-friendliness of operations

Motivation: Currently one interacts with robot only using the command line interface.
It would be great if it was easier to interact with the robot, such as starting and stopping, and activating the various behaviors through a graphical interface.

<span class="bronze"/>

<span class="silver"/>

<span class="gold"/>


<span class="SW"/>
<span class="PHY"/>

</div>


<div class='idea' markdown='1'>

### Building monitoring platform for teachers

Motivation: Imagine  a class with 20 people and 20 robots: how can the teacher know that everything is ready for the next experience?

<span class="bronze"/>

<span class="silver"/>

<span class="gold"/>


<span class="SWP"/>
<span class="EDU"/>

</div>


<div class='idea' markdown='1'>

### Scratch interface

Motivation:

<span class="bronze"/>

<span class="silver"/>

<span class="gold"/>


<span class="SW"/>
<span class="EDU"/>
<span class="PHY"/>

</div>



## Idea Group: Infrastracture

<div class='idea' markdown='1'>

### Improving backend

The Duckietown project relies on several backend tools for cloud-based integration tests and regression tests. These tools can be greatly improved. Some of the examples are:

* Improving log database, adding automatic submissions;
* Improving the regression tests.


<span class="bronze"/>

<span class="silver"/>

<span class="gold"/>


<span class="SWP"/>

</div>

<style>
.SW, .SWP,
.AI, .AIP, .EDU,
.PHY, .PHYP {
    display: block:

border:solid 1px red;
    color: white;
    font-size: smaller;
    font-variant: small-caps;
    padding-left: 2px;
    padding-right: 4px;
    padding-top: 2px;
    padding-bottom: 2px;

}
.SW { background-color: darkred; }
.SWP { background-color: red; }
.AI { background-color: darkblue; }
.AIP { background-color: blue; }
.EDU { background-color: brown; }
.PHY { background-color: darkgreen; }
.PHYP { background-color: green; }

.SW::before { content: "programming"; }
.SWP::before { content: "programming++"; }
.AI::before { content: "AI"; }
.AIP::before { content: "AI++"; }
.PHY::before { content: "physical"; }
.PHYP::before { content: "physical++"; }
.EDU::before { content: "educational"; }

.silver::before {content: "Silver-level achievement: "}
.gold::before {content: "Gold-level achievement: "}
.bronze::before {content: "Bronze-level achievement: "}
.silver { background-color: grey; margin-left: 2em; }
.gold { background-color: gold; margin-left: 2em;}
.bronze { background-color: brown;margin-left: 2em; }

div.idea {

    box-shadow:2px 2px 5px #000000;
border-radius: 15px;
    margin: 1em;
    padding: 0.5em;
}
div.idea h3 {
    text-align: center;
    margin-top: 0;
}
h2 { font-family: arial; }
h3 { font-family: arial; font-weight: bold; color: black;}
</style>

## FAQ from students

**Can we get assigned to a specific mentor/institution?**

To facilitate communication, we will match students to the institutions in the same time zone.



<span class="SW"/>
<span class="SWP"/>
<span class="AI"/>
<span class="AIP"/>
<span class="EDU"/>
<span class="PHY"/>
<span class="PHYP"/>
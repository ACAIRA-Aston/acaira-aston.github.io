---
title: "When Does Learning Make Sense? A Factorial Study of Coordination in Robot Fleets (11/11/26)"
date: '2026-10-08T14:00:00+01:00'

event_name: ACAIRA Seminar Series
event_url: 

location: Main Building, Room MB231
address:
  street:
  city: Birmingham
  region: 
  postcode:
  country: United Kingdom

summary: Investigating when learning-based coordination outperforms simple heuristics in autonomous robot fleets.
abstract: |
  Autonomous robot fleets are increasingly deployed in logistics, delivery, and service environments, where they must allocate tasks under deadlines, battery limits, and fluctuating demand. Learning-based coordination is often proposed as the answer, but most studies evaluate policies at a single fixed operating point, so it remains unclear when the added engineering cost of learning is justified over a simple heuristic.
  
  This talk presents an experimental framework accompanied by a study that decomposes coordination difficulty into four operational axes: temporal constraints, battery limitations, task load, and fleet scale and availability. Across 36 configurations and 7,200 evaluation episodes, we compare centralised and decentralised greedy heuristics, random allocation, and a deliberately simple deep Q-learning policy, chosen to isolate the value of learning itself rather than architectural sophistication.
  
  Three findings emerge. First, decentralised greedy coordination recovers most of the benefit of global information when local observations are informative. Second, learning’s clearest advantage is in worst-case delivery latency under hard deadlines, constrained availability, and dense load. Third, difficulty arises from interactions between constraints: deadlines and battery limits combine non-additively under low availability, producing cascading failures that single-axis analysis misses. The talk closes with practical guidance on when learning pays off, when greedy suffices, and when capacity, not coordination, is the bottleneck.

  We also demonstrate our multi-agent simulation platform, LEMUR, that enables reproducible, regime-aware evaluation of coordination policies through independently controllable complexity axes.

# Talk start and end times.
event_start: '2026-11-11T13:00:00+01:00'
event_end: '2026-11-11T14:00:00+01:00'
event_all_day: false

authors:
  - me

tags:
  - Robotics
  - Sustainability-Transport

featured: true

image:
  caption: ''
  focal_point: Center

links:
  - icon: user
    name: Presenter Profile - Pranup Chhetri
    url: https://www.linkedin.com/in/pranup/

projects: []
---

<div style="margin: 25px 0;">
  <a href="https://teams.microsoft.com/meet/3537441090221382?p=ywQxKMsT0Z06gjmQOQ"
     target="_blank"
     rel="noopener noreferrer"
     style="
       display: inline-flex;
       align-items: center;
       gap: 12px;
       padding: 13px 24px;
       background-color: #6264A7;
       color: white;
       text-decoration: none;
       border-radius: 8px;
       font-weight: 600;
       font-size: 16px;
       box-shadow: 0 3px 8px rgba(0,0,0,0.15);
       transition: background-color 0.2s ease;
     ">
    <i class="fab fa-microsoft" style="font-size: 22px;"></i>
    Join Seminar via Microsoft Teams
    <i class="fas fa-external-link-alt" style="font-size: 12px;"></i>
  </a>
</div>

<div style="
    margin: 25px 0;
    padding: 20px 24px;
    background: #f3f5fc;
    border-left: 5px solid #6264A7;
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 15px;
">
  <div>
    <strong style="font-size: 17px; color: #333;">
      <i class="fas fa-video" style="color: #6264A7;"></i>
      Attend Online
    </strong>
    <p style="margin: 5px 0 0; color: #666;">
      Join the seminar remotely through Microsoft Teams.
    </p>
  </div>

  <a href="https://teams.microsoft.com/meet/3537441090221382?p=ywQxKMsT0Z06gjmQOQ"
     target="_blank"
     rel="noopener noreferrer"
     style="
       display: inline-block;
       padding: 11px 20px;
       background: #6264A7;
       color: white;
       border-radius: 6px;
       text-decoration: none;
       font-weight: 600;
       white-space: nowrap;
     ">
    Join Meeting →
  </a>
</div>

Pranup Chhetri is an AI Specialist for Autonomous Systems and Knowledge Transfer Partnership (KTP) Associate working jointly between Aston University and Aurrigo, where he researches and develops decentralised fleet management and multi-agent task allocation technologies for autonomous vehicles. Holding an MSc in Artificial Intelligence from Aston University, where he graduated with a distinction and received multiple departmental awards for his dissertation on Graph Neural Networks for social robot navigation, he contributes to cutting-edge research in multi-agent systems, human-robot interaction, and reinforcement learning, with recent work presented at conferences such as EUMAS and UKAI 2026.
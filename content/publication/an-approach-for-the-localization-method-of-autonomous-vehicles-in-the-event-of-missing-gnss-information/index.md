---
title: "An Approach for the Localization Method of Autonomous Vehicles in the Event of Missing GNSS Information"

authors:
- Yul Y. Nazaruddin
- admin
- Eraraya R. Muten
- Prasetyo W. L. Sanjaya
- Gilbert Tjahjono
- Joshua A. Oktavianus

author_notes:
- "Supervisor, Corresponding author"
- ""
- ""
- ""
- ""
- ""

date: "2021-09-10T00:00:00Z"
doi: ""

publication_types: ["3"]

publication: In *2021 the Society of Instrument and Control Engineers*
publication_short: In *SICE*

abstract: The swift development of autonomous vehicle raises concern about its safety, although in theory, it has potential to be safer compared to human driver. Reliable system for localization is one of the most important factor in the safety of autonomous vehicle. A combination of Inertial Measurement Unit (IMU), wheel encoder, and Global Navigation Satellite System (GNSS) is commonly used to estimate the vehicle position. However, GNSS is prone to disconnection because of its high dependency to the external environment and low sampling rate. This paper proposes assisted GNSS localization system to address the problem. This system utilizes Error-state Kalman Filter (ESKF) and Residual Long Short-Term Memory (Residual LSTM) as an estimator for the vehicle’s position when GNSS disconnection happens. A neural-network model approach with Residual LSTM is independent to external environment and easily accessible locally, making it a more reliable replacement for estimating position in the event of GNSS’s disconnection. Implementation in CARLA Simulator shows the system could reduce the deviation in position estimation caused by the absence of GNSS. By having a localization system that works in fully offline mode without meaningful additional cost, the proposed idea is expected to enable a low-cost, reliable global navigation system in the future.

url_pdf: ''

tags: [Deep Learning, Neural Networks, Autonomous Car, Autonomous Vehicle, Localization, State Estimation, Kalman Filter]

---
# Jakub Wesołowski

M.Sc. student in **Smart Aerospace and Autonomous Systems** at Université d'Évry Paris-Saclay, as a double degree with **Automatic Control and Robotics** at Poznań University of Technology.

**Looking for a 6-month end-of-studies internship in France, starting March 2027** — Paris region preferred. Robotics, autonomous systems, perception, applied machine learning.

## Selected projects

| Project | What it is |
|---|---|
| [autonomous-remote-monitoring-system](https://github.com/kubuswes2003/autonomous-remote-monitoring-system) | B.Eng. thesis, team of two — I built the software and data layer: LoRaWAN payload decoder, ChirpStack → MQTT → InfluxDB pipeline, and a live bilingual dashboard. 4.3 km radio link verified in field tests. |
| [ros-bridge-labbot-demo](https://github.com/kubuswes2003/ros-bridge-labbot-demo) | Controlling a ROS 1 Melodic robot from ROS 2 Humble, by chaining Melodic → Noetic master → `ros1_bridge` → Humble in Docker, since no official bridge covers Melodic. Validated against a mock robot. |
| [robot_foas](https://github.com/kubuswes2003/robot_foas) | Vector-field controller tracking a circular path on a real MTracker robot with OptiTrack pose only — no odometry, no IMU. Under 2 cm steady-state radius error on a 0.4 m circle. |
| [transport_extractor](https://github.com/kubuswes2003/transport_extractor) | A tool that is actually used: it reads freight orders from PDF in Polish and German (pattern matching plus spaCy NER for city names), stores them in SQLite and produces weekly per-truck summaries. It replaced manual retyping at a transport company and runs there daily. |
| [PLUG-AND-PLAY_CHATBOT](https://github.com/kubuswes2003/PLUG-AND-PLAY_CHATBOT) | *In development, with a colleague.* Embeddable support chat widget: FastAPI, a locally hosted LLM (Bielik 11B via Ollama) and RAG over a company's own documents. |
| [micromouse-controller-pcb](https://github.com/kubuswes2003/micromouse-controller-pcb) | Two-layer ESP32-S3 robot controller board in KiCad, 73 components — design project, team of two, my part was component placement. Reviewed by a lecturer, not fabricated. |

**FlowTrack** *(private repository)* — a time-blocking planner built as a PWA with Next.js and Supabase (row-level security, three languages), used daily by two people. The code stays closed because it is a live application holding personal data; happy to walk through it or demo it.

## Tools I actually use

- **Core:** Python · ROS / ROS 2 · MATLAB
- **Machine learning:** scikit-learn · spaCy · LLMs and RAG
- **Infrastructure:** Docker · Linux · MQTT · FastAPI

## Contact

[LinkedIn](https://www.linkedin.com/in/jakub-wesolowski-386bb91ab) · kubuswes2003@gmail.com

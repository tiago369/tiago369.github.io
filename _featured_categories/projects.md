---
layout: page
title: Projects
---
# Projects
This page contains all the projects that I have made in recent years.

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
  gap: 1.5rem;
  margin: 1.5rem 0 2.5rem;
}
.project-card {
  display: flex;
  flex-direction: column;
  border-radius: 10px;
  overflow: hidden;
  background: rgba(127, 127, 127, 0.08);
  box-shadow: 0 1px 4px rgba(0, 0, 0, 0.12);
  text-decoration: none;
  color: inherit;
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}
.project-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.18);
}
.project-card .thumb {
  width: 100%;
  height: 150px;
  object-fit: cover;
  display: block;
  background: #1c1c1c;
}
.project-card .body {
  padding: 0.9rem 1rem 1.1rem;
}
.project-card .body h4 {
  margin: 0 0 0.4rem;
  font-size: 1.05rem;
}
.project-card .body p {
  margin: 0;
  font-size: 0.88rem;
  line-height: 1.4em;
  opacity: 0.85;
}
</style>

# Robotics & Autonomous Systems Competence Center

<div class="project-grid">
  <a class="project-card" href="https://tiago369.github.io/2022-01-07-dobot/">
    <img class="thumb" src="../assets/img/blog/dobot/dobot.jpg" alt="Dobot Magician pick and place">
    <div class="body">
      <h4>Dobot Magician</h4>
      <p>Pick-and-place with the Dobot Magician manipulator over ROS.</p>
    </div>
  </a>
  <div class="project-card">
    <img class="thumb" src="../assets/img/blog/turtlebot/turtle.png" alt="TurtleBot">
    <div class="body">
      <h4>TurtleBot</h4>
      <p>Mobile base used for navigation and autonomy work in the lab.</p>
    </div>
  </div>
  <div class="project-card">
    <img class="thumb" src="../assets/img/blog/desfioslab/ros.png" alt="ROS">
    <div class="body">
      <h4>ROS</h4>
      <p>Core middleware behind most of the lab's robotics stack.</p>
    </div>
  </div>
</div>

# SoftRobots & SUBOT — SENAI CIMATEC

<div class="project-grid">
  <div class="project-card">
    <img class="thumb" src="../assets/img/blog/softrobots/teleoperated-prototype.png" alt="Teleoperated soft manipulator prototype">
    <div class="body">
      <h4>SoftRobots — Teleoperated Prototype</h4>
      <p>Tendon-driven soft manipulator, teleoperated by hand controller.</p>
    </div>
  </div>
  <a class="project-card" href="https://www.instagram.com/p/C217ewRAuA4/">
    <img class="thumb" src="../assets/img/blog/softrobots/quadruped-manipulator.png" alt="Continuum manipulator mounted on a quadruped mobile base">
    <div class="body">
      <h4>SoftRobots — Quadruped Manipulator</h4>
      <p>Continuum manipulator mounted on a quadruped mobile base.</p>
    </div>
  </a>
  <a class="project-card" href="https://atarde.com.br/bahia/boge-2025-senai-investe-em-formacao-e-tecnologia-para-petroleo-e-gas-1329284">
    <img class="thumb" src="../assets/img/blog/subot/subot-robot.png" alt="SUBOT autonomous inspection robot prototype">
    <div class="body">
      <h4>SUBOT Robot</h4>
      <p>Autonomous localization and navigation prototype for oil & gas inspection, with EMBRAPII and SENAI CIMATEC.</p>
    </div>
  </a>
</div>

# Open Source

A few things from my [GitHub](https://github.com/tiago369):

<div class="project-grid">
  <a class="project-card" href="https://github.com/tiago369/cross-engine-humanoid-benchmark">
    <img class="thumb" src="../assets/img/blog/cross-engine-humanoid-benchmark/comparison_plots.png" alt="Cross-Engine Humanoid Benchmark results">
    <div class="body">
      <h4>Cross-Engine Humanoid Benchmark</h4>
      <p>Benchmarks a 29-DoF Unitree G1 across MuJoCo and PyBullet, then closes the sim-to-sim gap with PSO-based calibration. CI, statistical trials, full reproducibility.</p>
    </div>
  </a>
  <a class="project-card" href="https://github.com/tiago369/bonzi-buddy">
    <img class="thumb" src="../assets/img/blog/bonzi-buddy/waving.png" alt="Desktop Monkey Assistant">
    <div class="body">
      <h4>Desktop Monkey Assistant</h4>
      <p>A Bonzi-Buddy-style desktop assistant answering typed or spoken questions through a fully local LLM (Ollama) — no cloud APIs.</p>
    </div>
  </a>
  <a class="project-card" href="https://tiago369.github.io/2026-08-23-ros2-tooling/">
    <img class="thumb" src="../assets/img/blog/desfioslab/ros.png" alt="ROS 2 Tooling">
    <div class="body">
      <h4>ROS 2 Tooling</h4>
      <p>ros2-serial-fpga (UART ↔ FPGA bridge in VHDL), dobot-mgc-ros2-pkg, and fastdds_config_files.</p>
    </div>
  </a>
</div>

# IEEE

<div class="project-grid">
  <a class="project-card" href="https://ieeecimatec.github.io/project-mao_espelhada/">
    <img class="thumb" src="../assets/img/blog/mirrodhand/cad.png" alt="Mirrored robotic hand">
    <div class="body">
      <h4>Mirrored Hand</h4>
      <p>Computer-vision-driven mirrored robotic hand to assist people with physical disabilities.</p>
    </div>
  </a>
  <a class="project-card" href="https://ieeecimatec.github.io/rasweekend/">
    <img class="thumb" src="../assets/img/blog/rasweek/onshape.png" alt="IEEE RAS Weekend">
    <div class="body">
      <h4>IEEE RAS Weekend</h4>
      <p>IEEE RAS CIMATEC student branch event.</p>
    </div>
  </a>
</div>

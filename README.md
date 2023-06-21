
<h1 align="center"> Awesome Reinforcement Learning <br>for Cyber Security </h1>

<p align="center">
  <img src="https://awesome.re/badge.svg">
  <a href="https://github.com/Limmen/awesome-rl-for-cybersecurity">
    <img src="https://img.shields.io/badge/Awesome-AwesomeRLForCyber-orange">
  </a>
  <a href="https://github.com/Limmen/awesome-rl-for-cybersecurity/stargazers">
    <img src="https://img.shields.io/github/stars/Limmen/awesome-rl-for-cybersecurity">
  </a>
  <a href="https://github.com/Limmen/awesome-rl-for-cybersecurity/network/members">
    <img src="https://img.shields.io/github/forks/Limmen/awesome-rl-for-cybersecurity">
  </a>
  <a href="https://github.com/Limmen/awesome-rl-for-cybersecurity">
    <img src="https://img.shields.io/github/issues/Limmen/awesome-rl-for-cybersecurity">
  </a>
<a href="https://github.com/Limmen/awesome-rl-for-cybersecurity#contributors-"><img src="https://img.shields.io/badge/all_contributors-3-orange.svg"></a>
</p>


A curated list of resources dedicated to reinforcement learning applied to cyber security.
Note that the list includes only work that uses reinforcement learning, general machine learning methods applied to cyber security are not included in this list.

For other related curated lists, see :

* [Awesome Machine Learning for Cyber Security](https://github.com/jivoi/awesome-ml-for-cybersecurity)
* [Awesome Adversarial Machine Learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning)

<p align="center">
<img src="imgs/network_chess.png" width="50%", height="50%">
</p>

## Table of Contents

 - [RL-Environments](#-environments)
 - [Papers](#-papers)
 - [Books](#-books)
 - [Blogposts](#-miscellaneous)
 - [Talks](#-talks)
 - [Miscellaneous](#-miscellaneous)

## [↑](#table-of-contents) Environments

### `AutoPentest-DRL`
<table>
  <tbody>
    <tr>
      <td width='50%' align='center'>
        <img src='https://raw.githubusercontent.com/crond-jaist/AutoPentest-DRL/master/Figures/framework_overview.png' />
      </td>
      <td width='50%'>
        <a href='https://github.com/crond-jaist/AutoPentest-DRL'>AutoPentest-DRL: Automated Penetration Testing Using Deep Reinforcement Learning</a>
        <ul>
          <li>
            AutoPentest-DRL is an automated penetration testing framework based on Deep Reinforcement Learning (DRL) techniques. AutoPentest-DRL can determine the most appropriate attack path for a given logical network, and can also be used to execute a penetration testing attack on a real network via tools such as Nmap and Metasploit. This framework is intended for educational purposes, so that users can study the penetration testing attack mechanisms. AutoPentest-DRL is being developed by the Cyber Range Organization and Design (<a href="https://www.jaist.ac.jp/misc/crond/index-en.html">CROND</a>) NEC-endowed chair at the Japan Advanced Institute of Science and Technology (<a href="https://www.jaist.ac.jp/english/">JAIST</a>) in Ishikawa,Japan.
          </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

### `NASimEmu`
<table>
  <tbody>
    <tr>
      <td width='50%' align='center'>
        <img src='imgs/nasimemu.svg' width=300 />
      </td>
      <td width='50%'>
        <a href='https://github.com/jaromiru/NASimEmu'>NASimEmu</a>
        <ul>
          <li>
            NASimEmu is a framework for training deep RL agents in offensive penetration-testing scenarios. It includes both a simulator and an emulator so that a simulation-trained agent can be seamlessly deployed in emulation. Additionally, it includes a random generator that can create scenario instances varying in network configuration and size while fixing certain features, such as exploits and privilege escalations. Furthermore, agents can be trained and tested in multiple scenarios simultaneously.<br/><br/>
            Paper: <a href="https://arxiv.org/abs/2305.17246">(2023) NASimEmu: Network Attack Simulator & Emulator for Training Agents Generalizing to Novel Scenarios</a><br/>
            Framework: <a href="https://github.com/jaromiru/NASimEmu">NASimEmu</a><br/>




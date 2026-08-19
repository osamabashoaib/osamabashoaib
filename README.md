Today 3:29 PM
rapport projet 19 mai MELBECK BA SHOAIB(1).docx
Document
présentation projet 19 mai MELBECK BA SHOAIB.odp
File
Aruco_detection.py
Python
présentation pratical robotics BA SHOAIB.odp
File
présentation_pratical_robotics_BA SHOAIB_Osama(1).pptx
Presentation
Code_Final_BA_SHOAIB.ino
File
final projet asservissement PV_ (2).pdf
PDF
FR_Master-1_BA_SHOAIB_Osama_JB-signed(3).pdf
PDF

ABMI-software/mycobot_320pi_R6AR6A

my projet 320 PI
https://github.com/ABMI-software/mycobot_320pi_R6A/tree/feature/pick-and-place-osamaama

Opérateur de production industrielle

VARICOR · Stage

mai 2023 · 1 mois

Wisches, Grand Est, France · Sur site

    Diagnostic, dépannage et remise en service de systèmes mécaniques, électriques et
    équipements automatisés (perçage, taraudage, lamage, soudage).

    Démontage et réutilisation de matériaux afin de réduire les déchets.… plus

Gestion du temps, Problématiques environnementales et 5 compétences de plus

sur mon git hub créer de profile et intéressant osamabashoaib

 1 follower · 0 following

Achievements
Organizations

You unlocked new Achievements with private contributions! Show them off by including private contributions in your Profile in settings.
Popular repositoriesLoading
You don't have any public repositories yet.
12 contributions in the last year

Oui. Pour rendre ton GitHub beaucoup plus intéressant pour les recruteurs en robotique / logiciel embarqué, je te conseille de faire de osamabashoaib un vrai portfolio technique, pas seulement une liste de contributions.

J’ai préparé pour toi un README de profil GitHub complet prêt à utiliser :

J’ai basé le contenu sur tes vrais projets. Par exemple, ton projet Practical Robotics utilise un robot différentiel avec Raspberry Pi + Arduino, caméra, encodeurs et capteurs IR/ultrasons, avec exploration autonome, évitement d’obstacles, FSM, cartographie et retour au point de départ. Ton projet TurtleBot3 couvre aussi ROS2, SLAM, navigation autonome et évitement d’obstacles. Et ton système ArUco utilise OpenCV/PiCamera2 sur Raspberry Pi avec communication série vers Arduino.

Pour ton ancien projet solaire, j’ai aussi intégré le contrôle Arduino + servomoteurs + RTC et le suivi automatique de la position solaire.
Structure que je te recommande

Ton profil doit commencer très simplement :

# Hi, I'm Osama Ba Shoaib 👋

### Robotics • Computer Vision • Embedded Systems • ROS 2

Master 2 student in Mechatronics, Energy and Intelligent Systems (MESI),
currently working on robotics and computer vision at ABMI Groupe.

Puis surtout mettre ton projet actuel en premier :

## 🤖 Current Project — MyCobot 320 Pi

### Vision-Guided Robotics & Pick-and-Place

ROS 2 • Python • C++ • OpenCV • DREAM • YOLO • Gazebo • Raspberry Pi

- ROS 2 integration and TCP communication
- Digital twin in Gazebo Harmonic
- Multi-camera calibration
- DREAM/VGG-19 keypoint detection
- 6-DoF pose estimation
- Pick-and-place and automated sorting
- Simulation and real-robot validation

C’est beaucoup plus puissant pour un recruteur que de commencer par VARICOR. VARICOR peut rester plus bas dans une section Industrial Experience, parce que ton identité professionnelle aujourd’hui est plutôt :

Robotics Software / Computer Vision / Embedded Systems Engineer

Je mettrais ensuite seulement 3 projets principaux :

1. MyCobot 320 Pi — ABMI
Ton projet le plus important.

2. TurtleBot3 Autonomous Mobile Robot
ROS2, SLAM, Nav2, Gazebo, RViz, LiDAR.

3. Autonomous Maze Robot
Raspberry Pi, Arduino, FSM, ArUco, odometry, sensors.

Ton projet solaire peut apparaître ensuite comme projet embarqué secondaire.
Pour l’afficher directement sur ton profil

GitHub demande un repository spécial qui porte exactement ton username :

osamabashoaib/osamabashoaib

Il n’existe pas encore sur ton compte GitHub actuellement. J’ai vérifié : le repository osamabashoaib/osamabashoaib n’est pas encore créé.

Dans GitHub :

New repository
↓
Repository name:
osamabashoaib

☑ Public
☑ Add a README file
↓
Create repository

Ensuite tu remplaces son README.md avec celui que je viens de préparer.
Et surtout : tes repositories

Actuellement, ton profil paraît relativement vide parce que ton travail principal MyCobot est dans :

ABMI-software/mycobot_320pi_R6A

et dans ta branche :

feature/pick-and-place-osama

Donc je créerais également sur ton compte personnel des repos portfolio comme :

osamabashoaib/
├── mycobot-vision-guided-robotics
├── autonomous-mobile-robot-ros2
├── raspberry-pi-autonomous-robot
├── solar-tracking-embedded-system
└── fpga-real-time-embedded-system

Attention pour ABMI : ne copie pas le code propriétaire vers ton compte personnel sans autorisation. Ton repo personnel MyCobot peut simplement contenir une présentation technique publique, architecture, captures de Gazebo, technologies utilisées et lien vers la branche ABMI si l'entreprise autorise cette visibilité.

Le README que je t’ai créé est déjà une bonne première version :

Je peux aussi te préparer une version beaucoup plus “premium”, avec badges Python/C++/ROS2/Linux, cartes GitHub, section Featured Projects avec images/GIF du MyCobot et un design comparable aux profils d’ingénieurs robotique professionnels.

87161cc7-a9ff-4746-9d43-4d09799ce460.pdf
PDF
Pour ABMI publie juste seulement ça et le bras robotique

Oui, c’est mieux pour ABMI : on ne publie que ce qui est déjà public dans l’offre, plus le fait qu’il s’agit d’un bras robotique 6-DoF. Je retire donc les résultats internes, DREAM/YOLO, datasets, performances et autres détails qui pourraient être confidentiels.

L’offre publique mentionne bien l’intégration du bras dans ROS2, URDF/MoveIt2, le Digital Twin sous Gazebo, ArUco/ChArUco + solvePnP, tracking/filtrage/estimation de pose, vision-in-the-loop et pick-and-place.

J’ai modifié ton README dans ce sens :

La partie ABMI ressemble maintenant à ceci :

## 🤖 Current Project — 6-DoF Robotic Vision Demonstrator

### ABMI Groupe — Robotics / Computer Vision Internship

Working on the development and integration of a **6-DoF robotic arm demonstrator** for vision-guided robotics.

- Integration of the robotic arm in a **ROS 2** architecture (`URDF`, `MoveIt 2`, controllers)
- Development of a **Digital Twin with Gazebo**
- Camera and sensor calibration, including **eye-to-hand / eye-in-hand** configurations
- Visual perception pipeline using **ArUco / ChArUco** and **solvePnP**
- Tracking, filtering and **pose estimation**
- Implementation of **vision-in-the-loop** control
- Development of a vision-guided **pick-and-place** function
- Experimental validation of system **reliability, precision and robustness**

C’est la bonne approche pour un GitHub public : assez technique pour impressionner un recruteur, sans dévoiler le travail interne d’ABMI.


وحط
اكمل

dans overview il affiche tout

rapport projet 19 mai MELBECK BA SHOAIB(1).docx
Document
présentation projet 19 mai MELBECK BA SHOAIB.odp
File
Aruco_detection.py
Python
présentation pratical robotics BA SHOAIB.odp
File
présentation_pratical_robotics_BA SHOAIB_Osama(1).pptx
Presentation
Code_Final_BA_SHOAIB.ino
File
final projet asservissement PV_ (2).pdf
PDF
FR_Master-1_BA_SHOAIB_Osama_JB-signed(3).pdf
PDF
https\://github.com/ABMI-software/mycobot\_320pi\_R6A



my projet 320 PIhttps\://github.com/ABMI-software/mycobot\_320pi\_R6A/tree/feature/pick-and-place-osama





Opérateur de production industrielle

je t'envoie tout

VARICOR · Stage

mai 2023 · 1 mois

Wisches, Grand Est, France · Sur site

1. Diagnostic, dépannage et remise en service de systèmes mécaniques, électriques et 
équipements automatisés (perçage, taraudage, lamage, soudage).

2. Démontage et réutilisation de matériaux afin de réduire les déchets.… plus

 Gestion du temps, Problématiques environnementales et 5 compétences de plus







sur mon git hub créer de profile et intéressant osamabashoaib

[ ](https://github.com/osamabashoaib?tab=followers)[**1**](https://github.com/osamabashoaib?tab=followers)[ follower ](https://github.com/osamabashoaib?tab=followers)· [**0**](https://github.com/osamabashoaib?tab=following)[ following](https://github.com/osamabashoaib?tab=following)

-

## [Achievements](https://github.com/osamabashoaib?tab=achievements)

## Organizations

You unlocked new Achievements with private contributions! Show them off by including private contributions in your Profile in [settings](https://github.com/settings/profile#contributions-activity-heading).

## Popular repositoriesLoading

## You don't have any public repositories yet.

## 12 contributions in the last year

J’ai continué et j’ai préparé une version nettement plus professionnelle, structurée comme un vrai portfolio d’ingénieur robotique, avec :

    une intro courte et propre ;

    ABMI mis en avant avec seulement le périmètre public ;

    un bouton direct vers ta branche pick-and-place-osama ;

    TurtleBot3 ;

    ton robot autonome Raspberry Pi / Arduino / ArUco ;

    le projet de suivi solaire ;

    un tableau clair de compétences ;

    VARICOR ;

    GitHub stats ;

    une identité plus “Robotics Software Engineer”.

Les éléments techniques viennent bien de tes projets : le TurtleBot3 porte sur ROS2, cartographie et navigation autonome. Ton robot pratique utilise Raspberry Pi, Arduino, caméra, encodeurs et capteurs IR/ultrasons avec FSM et retour au point de départ. Ton script ArUco utilise aussi OpenCV, PiCamera2 et une liaison série vers Arduino.

J’ai essayé de modifier directement ton README.md, mais GitHub renvoie actuellement 403 “Resource not accessible by integration” pour les écritures. Je peux lire ton repo, mais la connexion GitHub ne m’autorise pas à publier/modifier les fichiers pour le moment.

Le plus simple maintenant : ouvre ton README.md → Edit → remplace tout par la version professionnelle que je viens de préparer dans le message précédent, puis Commit changes.

Pour la photo que tu m’as envoyée, je veux aussi l’intégrer proprement, mais il faut d’abord l’uploader dans ton repo, par exemple :

assets/profile.png

Ensuite on pourra l’afficher avec :

<p align="center">
  <img src="./assets/profile.png" width="160" style="border-radius:50%" />
</p>

Ton profil sera alors plus propre que celui de ton ami, tout en gardant une identité différente : plus robotique, plus technique, plus orientée projets réels.


Generated image: Polished Professional Avatar Portrait

ok fait le s. Je commencerais par 4 vrais repositories documentés, puis on ajoute progressivement les autres. Pour synchroniser exactement tous les projets de ton LinkedIn, envoie-moi simplement une capture de ta section Projects / Projets LinkedIn ; je pourrai alors reprendre chaque projet sans en oublier un.

Osama Bashoaib

il n'est pas bien ..tu vois totalement comme l'autre de mon ami ali
https://github.com/AliHassan-019


plus avancé

Oui — cette fois je l’ai refait beaucoup plus proche du niveau visuel du profil d’Ali, mais avec une identité clairement robotique et plus structurée.

Son profil utilise notamment un header animé, un texte typing, des badges, analytics, une section philosophie et un footer. J’ai repris ce niveau de finition, sans copier son contenu.
Ta nouvelle version contient

    Header animé Osama Ba Shoaib

    Robotics Software | Computer Vision | Embedded Systems

    texte animé :

        ROS 2 + Computer Vision + Embedded Linux

        From Camera Calibration to Robot Control

        Perception → Planning → Action

    About Me

    What I Build

    bloc spécial ABMI

    4 cartes de projets cliquables

    logos Python / C++ / Linux / Raspberry Pi / Arduino…

    badges ROS2 / OpenCV / Gazebo / MoveIt2 / Nav2 / SLAM / FPGA

    Technology Matrix

    Focus Areas

    GitHub Analytics

    GitHub streak

    Top Languages

    Engineering Philosophy

    LinkedIn + GitHub

    footer animé

Et surtout, comme tu voulais : sur le profil on voit seulement un petit résumé du projet. Quand on clique sur le projet, une page séparée s’ouvre avec son explication et les logiciels utilisés.
Fichiers

Par exemple :

🗺️ TurtleBot3 Autonomous Navigation → clic → page dédiée avec ROS2, SLAM, Nav2, Gazebo, RViz, LiDAR. Ces éléments correspondent bien à ton projet réel.

🚗 Autonomous Maze Robot → clic → Raspberry Pi, Arduino, OpenCV, ArUco, FSM, odometry.

☀️ Solar Tracking → clic → Arduino, RTC, servomotors, elevation/azimuth.

Cette version est celle que je choisirais pour ton GitHub. Elle est beaucoup plus proche d’un portfolio d’ingénieur, pas simplement d’un CV copié dans README.

tu peux faire par toi meme j'ai le permet

Oui, j’ai essayé directement avec ta permission, mais GitHub bloque toujours l’écriture via l’intégration actuelle avec une erreur 403.

Donc je peux :

    lire ton repo ;

    vérifier le contenu ;

    préparer les fichiers exactement ;

    mais pas faire le commit depuis ici tant que GitHub n’accorde pas l’autorisation d’écriture à cette intégration.

La version avancée est prête ici :

Si tu veux, je peux maintenant te guider clic par clic pour l’installer en 2–3 minutes sur ton compte, sans rien casser.


<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,55:0f4c75,100:38bdf8&height=235&section=header&text=Osama%20Ba%20Shoaib&fontSize=54&fontColor=ffffff&animation=fadeIn&fontAlignY=37&desc=Robotics%20Software%20%7C%20Computer%20Vision%20%7C%20Embedded%20Systems&descAlignY=59&descSize=19" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2400&pause=850&color=38BDF8&center=true&vCenter=true&width=850&lines=ROS+2+%2B+Computer+Vision+%2B+Embedded+Linux;From+Camera+Calibration+to+Robot+Control;Building+Perception+%E2%86%92+Planning+%E2%86%92+Action+Pipelines" />

</div>
👋 About Me

I’m Osama Ba Shoaib, a Master 2 student in Mechatronics, Energy and Intelligent Systems (MESI) focused on building complete robotic systems across perception, simulation, control and embedded software.

I enjoy connecting the full robotics chain:

<div align="center">
Sensors → Perception → Pose Estimation → Planning → Control → Real Robot

</div>

Currently, I am working on a 6-DoF vision-guided robotic arm demonstrator at ABMI Groupe, combining ROS 2, computer vision and real-world robotic validation.
🚀 What I Build

    Robotics software with ROS 2, MoveIt 2, Nav2, Gazebo and RViz

    Computer vision pipelines with OpenCV, ArUco / ChArUco and pose estimation

    Embedded systems using Raspberry Pi, Arduino and FPGA platforms

    Autonomous navigation with SLAM, LiDAR and obstacle avoidance

    Vision-guided manipulation from camera calibration to pick-and-place

    Real-time systems using timers, interrupts and hardware / software integration

🤖 Current Engineering Focus

<table> <tr> <td width="68%" valign="top">
6-DoF Robotic Vision Demonstrator — ABMI Groupe

Working on the integration and validation of a vision-guided robotic arm demonstrator.

Public technical scope: ROS 2 integration, robot modelling, simulation, camera calibration, visual pose estimation, tracking, vision-in-the-loop control and robotic manipulation.

</td> <td width="32%" valign="top">
Main Stack

ROS 2
Python
C++
OpenCV
Gazebo
MoveIt 2
URDF
Linux

<br/>

View project →

</td> </tr> </table>
🌟 Featured Projects

<table> <tr> <td width="50%" valign="top">
🗺️ TurtleBot3 Autonomous Navigation

ROS 2 SLAM Nav2 LiDAR

Autonomous mapping, navigation and obstacle avoidance on TurtleBot3.

Open project →

</td> <td width="50%" valign="top">
🚗 Autonomous Maze Robot

Raspberry Pi Arduino OpenCV FSM

Autonomous exploration, wall-following, ArUco detection and return-to-start logic.

Open project →

</td> </tr>

<tr> <td width="50%" valign="top">
💻 FPGA Real-Time Embedded System

DE10-Lite Nios II C Interrupts

FPGA-based real-time embedded system using timers, GPIO and interrupt-driven C.

Open project →

</td> <td width="50%" valign="top">
☀️ Automated Solar Tracking System

Arduino UNO RTC Servomotors

Embedded control system for automatic photovoltaic panel orientation.

Open project →

</td> </tr> </table>
🛠 Core Skills

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,c,linux,git,github,vscode,raspberrypi,arduino" />

<br/><br/>

<img src="https://img.shields.io/badge/ROS%202-22314E?style=for-the-badge&logo=ros&logoColor=white" /> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" /> <img src="https://img.shields.io/badge/Gazebo-0E7C7B?style=for-the-badge" /> <img src="https://img.shields.io/badge/MoveIt%202-1E293B?style=for-the-badge" /> <img src="https://img.shields.io/badge/Nav2-0F766E?style=for-the-badge" /> <img src="https://img.shields.io/badge/SLAM-7C3AED?style=for-the-badge" /> <img src="https://img.shields.io/badge/FPGA-2563EB?style=for-the-badge" /> <img src="https://img.shields.io/badge/Embedded%20Linux-EA580C?style=for-the-badge" />

</div>
🧩 Technology Matrix
Area	Tools & Technologies
Robotics	ROS 2, MoveIt 2, Gazebo, RViz, Nav2, SLAM, URDF
Computer Vision	OpenCV, ArUco, ChArUco, solvePnP, camera calibration, pose estimation
Programming	Python, C, C++, Bash
Embedded Systems	Raspberry Pi, Arduino, FPGA, UART, I²C, PWM, GPIO
Real-Time	Timers, interrupts, Nios II, hardware / software integration
Development	Linux, Git, GitHub, TCP/IP
🎯 Focus Areas

    Robot perception and computer vision

    Autonomous mobile robotics

    Vision-guided manipulation

    Embedded Linux and sensor integration

    Real-time embedded systems

    Simulation-to-real validation

    Hardware / software integration

📊 GitHub Analytics

<div align="center">

<img width="48%" src="https://github-readme-stats.vercel.app/api?username=osamabashoaib&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&icon_color=38BDF8" /> <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=osamabashoaib&theme=tokyonight&hide_border=true&background=0D1117&ring=38BDF8&fire=38BDF8&currStreakLabel=38BDF8" />

<br/><br/>

<img width="45%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=osamabashoaib&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8" />

</div>
🧠 Engineering Philosophy

<div align="center">

<i>"A robotic system becomes useful when perception turns into reliable action."</i>

</div>
🤝 Connect

<div align="center">

<a href="https://www.linkedin.com/in/osama-bashoaib/" target="_blank"> <img src="https://skillicons.dev/icons?i=linkedin" width="45" /> </a> &nbsp;&nbsp;&nbsp;&nbsp; <a href="https://github.com/osamabashoaib" target="_blank"> <img src="https://skillicons.dev/icons?i=github" width="45" /> </a>

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38bdf8,55:0f4c75,100:0f172a&height=125&section=footer" />

</div>

# FuturHand Robotics

🏢 **[futurhandrobotics.com](https://futurhandrobotics.com/)** · 📋 **[Software Kanban](https://github.com/orgs/FuturHandRobotics/projects/1/)**

### Start here

| | |
| --- | --- |
| 🧩 **[futurhand](https://github.com/FuturHandRobotics/futurhand)** | The monorepo: all ROS 2 packages (arm control, behavior tree, hands, vision, msgs, utils, dashboard), scene configs, Docker images, CI and docs. Replaces FuturHub and its per-package repos |
| 📚 **[futur-wiki](https://github.com/FuturHandRobotics/futur-wiki)** | Engineering wiki: systems, decisions (ADRs), test reports and guides |
| 🛠️ **[futur-infra](https://github.com/FuturHandRobotics/futur-infra)** | Infrastructure: shared stations, Tailscale access policy, onboarding, tooling |
| 🤖 **[futur-agent-skills-marketplace](https://github.com/FuturHandRobotics/futur-agent-skills-marketplace)** | Claude Code plugins and skills for FuturHand work |

### Hand design and hardware

| | |
| --- | --- |
| ✋ **[futur_hand_gen](https://github.com/FuturHandRobotics/futur_hand_gen)** | Automated hand design: parametric Onshape hands from a URDF |
| 🖐️ **[futur_hand_design_pipe](https://github.com/FuturHandRobotics/futur_hand_design_pipe)** | Tendon-driven hand designs from motion capture |
| 📟 **[fhrsense](https://github.com/FuturHandRobotics/fhrsense)** | FHRSense load-cell board: KiCad hardware, STM32 firmware, host tools |
| 🔌 **[PCB-Designs](https://github.com/FuturHandRobotics/PCB-Designs)** | PCB designs |
| ⚙️ **[futurCAT](https://github.com/FuturHandRobotics/futurCAT)** | EtherCAT motor driver |

### Projects and analysis

| | |
| --- | --- |
| 📊 **[elc-bottle-picking-analysis](https://github.com/FuturHandRobotics/elc-bottle-picking-analysis)** | ELC bottle-picking tests: replay pages and metrics from `futur_log` sessions |
| 🦾 **[yam_ros2_control](https://github.com/FuturHandRobotics/yam_ros2_control)** · **[i2rt](https://github.com/FuturHandRobotics/i2rt)** · **[i2rt_ros2_jazzy](https://github.com/FuturHandRobotics/i2rt_ros2_jazzy)** | YAM arms: ros2_control, MoveIt and teleop; I2RT API and ROS 2 workspace |
| 🩺 **[futur_medic_card](https://github.com/FuturHandRobotics/futur_medic_card)** · **[futur_medic_record](https://github.com/FuturHandRobotics/futur_medic_record)** | TCCC card pipeline (audio to DD 1380); synced multi-camera recording over ROS 2 |

### Forks we maintain

Pinned as submodules or subtrees of `futurhand`; change them in their own repository, then bump the pin.
[kassow_kord_driver](https://github.com/FuturHandRobotics/kassow_kord_driver) ·
[zivid-ros](https://github.com/FuturHandRobotics/zivid-ros) ·
[fanuc_driver](https://github.com/FuturHandRobotics/fanuc_driver) ·
[fanuc_description](https://github.com/FuturHandRobotics/fanuc_description) ·
[ros-netft](https://github.com/FuturHandRobotics/ros-netft) ·
[warehouse_ros_sqlite](https://github.com/FuturHandRobotics/warehouse_ros_sqlite) ·
[3DObjectTracking](https://github.com/FuturHandRobotics/3DObjectTracking)

<sub>FuturHub, futur_docker and the per-package repos (futur_arm_control, futur_behavior_tree, futur_hands, futur_msgs, futur_utils, futur_vision, futur_scenes, futur_optimization, futur_iolink) now live in <code>futurhand</code>; their repositories are kept for history only.</sub>

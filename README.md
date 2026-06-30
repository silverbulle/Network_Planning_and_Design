# 网络规划与设计学习项目 (Network Planning & Design Study Project)

本项目是针对**软考高级 - 网络规划设计师**以及企业级网络规划与设计理论的学习指南，基于“summer课堂”系列核心课件整理而成。

## 📂 学习进度与目录导航 (Study Roadmap)

| 序号 | 章节主题 | 核心学习内容概要 | 建议学时 | 进度状态 |
| :--- | :--- | :--- | :--- | :--- |
| 01 | [01_network_planning_basics.md](./01_network_planning_basics.md) | 网络生命周期模型（四、五、六阶段）、核心设计原则 | 2小时 | ✅ 已完成 |
| 02 | [02_three_layer_and_large_two_layer.md](./02_three_layer_and_large_two_layer.md) | 传统三层架构设计与大二层扁平化架构对比 | 3小时 | ✅ 已完成 |
| 03 | [03_requirement_analysis.md](./03_requirement_analysis.md) | 业务需求与网络性能指标分析（带宽/时延/抖动/丢包率） | 2小时 | ✅ 已完成 |
| 04 | [04_communication_specification.md](./04_communication_specification.md) | 通信模式分类与边界分析（P2P, C/S, B/S, 分布式计算） | 2小时 | ✅ 已完成 |
| 05 | [05_logical_network_design.md](./05_logical_network_design.md) | 拓扑架构设计（环网ERPS）、IP规划与网络冗余技术（MPU/SFU/LPU） | 4小时 | ✅ 已完成 |
| 06 | [06_physical_network_design.md](./06_physical_network_design.md) | 综合布线系统六大子系统、机房物理环境设计规范 | 2小时 | ✅ 已完成 |
| 07 | [07_network_testing_and_maintenance.md](./07_network_testing_and_maintenance.md) | 主动测试与被动测试方法与工具（SNMP/MIB、Ping/Sniffer） | 2小时 | ✅ 已完成 |
| 08 | [08_network_troubleshooting.md](./08_network_troubleshooting.md) | 故障排查七步通用模型、系统诊断命令与管理运维工具 | 3小时 | ✅ 已完成 |
| 09 | [09_network_performance_management.md](./09_network_performance_management.md) | 网络性能测试类型（负载/压力/强度/容量/稳定性/基准测试） | 2小时 | ✅ 已完成 |

---

## ☁️ 云数据中心基础设施模块 (Cloud Datacenter)

本模块对应"summer课堂"**10-x 系列课件**，聚焦数据中心服务器、存储、虚拟化、容灾等基础设施技术。详见 [cloud-datacenter/README.md](./cloud-datacenter/README.md)。

| 序号 | 章节主题 | 核心学习内容概要 | 建议学时 | 进度状态 |
| :--- | :--- | :--- | :--- | :--- |
| 10 | [cloud-datacenter/10_servers.md](./cloud-datacenter/10_servers.md) | 服务器架构与选型（机架式/塔式/刀片、CPU/内存/IO子系统） | 2小时 | ✅ 已完成 |
| 11 | [cloud-datacenter/11_disks_and_tapes.md](./cloud-datacenter/11_disks_and_tapes.md) | 硬盘接口技术与磁带归档存储 | 1小时 | ✅ 已完成 |
| 12 | [cloud-datacenter/12_raid_technology.md](./cloud-datacenter/12_raid_technology.md) | RAID 级别原理与磁盘阵列选型计算 | 2小时 | ✅ 已完成 |
| 13 | [cloud-datacenter/13_network_storage.md](./cloud-datacenter/13_network_storage.md) | DAS/NAS/SAN 架构与 FC/iSCSI/FCoE 协议 | 3小时 | ✅ 已完成 |
| 14 | [cloud-datacenter/14_cloud_computing_virtualization.md](./cloud-datacenter/14_cloud_computing_virtualization.md) | 虚拟化技术与云服务模型(IaaS/PaaS/SaaS) | 3小时 | ✅ 已完成 |
| 15 | [cloud-datacenter/15_backup_and_disaster_recovery.md](./cloud-datacenter/15_backup_and_disaster_recovery.md) | 备份策略与容灾等级(RPO/RTO) | 2小时 | ✅ 已完成 |
| 16 | [cloud-datacenter/16_video_conferencing.md](./cloud-datacenter/16_video_conferencing.md) | 视频会议协议(H.323/SIP)与组网 | 1小时 | ✅ 已完成 |

---

## 🔒 网络安全模块 (Network Security)

本模块对应"summer课堂"**11-x 系列课件**，聚焦网络安全体系、攻击防御、防火墙、IDS/IPS、VPN、密码学等，是**重点考核模块**（上午 5-8 分 + 案例试题三 25 分，可出论文）。详见 [network-security/README.md](./network-security/README.md)。

| 序号 | 章节主题 | 核心学习内容概要 | 建议学时 | 进度状态 |
| :--- | :--- | :--- | :--- | :--- |
| 17 | [network-security/17_security_architecture.md](./network-security/17_security_architecture.md) | OSI安全体系三维、5服务8机制、信息保障模型 | 2小时 | ✅ 已完成 |
| 18 | [network-security/18_attacks_and_defense.md](./network-security/18_attacks_and_defense.md) | 主动/被动攻击与防御、DDoS、SQL注入 | 2小时 | ✅ 已完成 |
| 19 | [network-security/19_firewall_and_acl.md](./network-security/19_firewall_and_acl.md) | 防火墙技术(包过滤/状态检测/应用网关)、ACL | 2小时 | ✅ 已完成 |
| 20 | [network-security/20_ids_and_ips.md](./network-security/20_ids_and_ips.md) | IDS旁路检测 vs IPS串联阻断 | 2小时 | ⬜ 未开始 |
| 21 | [network-security/21_vpn_technology.md](./network-security/21_vpn_technology.md) | IPSec(AH/ESP/IKE)、SSL VPN | 3小时 | ⬜ 未开始 |
| 22 | [network-security/22_cryptography.md](./network-security/22_cryptography.md) | 对称/非对称加密、哈希、数字签名、PKI、SM系列 | 3小时 | ⬜ 未开始 |
| 23 | [network-security/23_security_applications.md](./network-security/23_security_applications.md) | HTTPS/SSL/TLS、邮件安全、Web安全 | 2小时 | ⬜ 未开始 |
| 24 | [network-security/24_security_audit.md](./network-security/24_security_audit.md) | 安全审计、日志留存、合规 | 1小时 | ⬜ 未开始 |

---
*注：进度状态标记：⬜ 未开始 | 🟡 进行中 | ✅ 已完成*

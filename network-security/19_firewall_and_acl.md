# 第十九章：防火墙与访问控制

> 对应课件：`11-3 防火墙与访问控制.pdf`（共 18 页）
> 本章聚焦防火墙技术（包过滤/状态检测/应用网关）、ACL 访问控制。
> ⚠️ 骨架占位，内容待对照 PDF 补充。

## 1. 核心考点脑图 (Mindmap)

```mermaid
flowchart TD
    A["防火墙与访问控制"] --> B["防火墙技术"]
    A --> C["部署区域<br>DMZ/Trust/Untrust"]
    A --> D["ACL访问控制"]

    B --> B1["包过滤<br>检查包头(五元组)"]
    B --> B2["状态检测<br>跟踪会话状态"]
    B --> B3["应用网关<br>代理,检查应用层"]

    style A fill:#e1f5fe,stroke:#0288d1,stroke-width:2px
    style B fill:#fff3e0,stroke:#ef6c00,stroke-width:2px
    style C fill:#fff3e0,stroke:#ef6c00,stroke-width:2px
    style D fill:#fff3e0,stroke:#ef6c00,stroke-width:2px
    style B1 fill:#f5f5f5,stroke:#9e9e9e
    style B2 fill:#f5f5f5,stroke:#9e9e9e
    style B3 fill:#f5f5f5,stroke:#9e9e9e
```

---

## 2. 深度理论解析 (Theory & Concepts)

> 待补充：防火墙三种技术原理对比、安全区域划分、ACL 规则匹配顺序。

## 3. 横向对比与易错辨析 (Comparisons & Pitfalls)

> 待补充：防火墙技术对比表、DMZ 部署辨析。

## 4. 历年真题与解析 (Exam Questions)

> 待补充：真实历年真题，标注出处年份。

## 5. 备考建议 (Exam Tips)

> 待补充：高频考点回顾、记忆口诀、易错提醒。

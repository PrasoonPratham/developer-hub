---
sidebar_position: 1
sidebar_label: 'Ethereum Finality'
---

# Ethereum's Finality

:::info

For context of the Sacred Timeline, see [here](https://www.tumblr.com/rekaspbrak/661582984296775680/adorablelokie-how-does-the-sacred-timeline-and)

:::

## Ethereum: The Sacred Timeline of Finality

![image (31)](https://github.com/user-attachments/assets/7fb13a23-d185-4b85-b277-5c04ecf949fc)

Ethereum's rollup-centric roadmap aims to scale the usability of its decentralized and secure blockspace. While this approach enhances security and inclusivity (like solo stakers), it encounters a **finality problem**.

### Finality of Ordering
Ethereum operates on a probabilistic model where transactions aren't fully confirmed until after two epochs — approximately 13 minutes under normal network conditions. Until this finality is reached:

![image (21)](https://github.com/user-attachments/assets/66ca59e3-377f-4bb8-a7db-512bf56526f5)

- **Forks May Occur**: Ethereum can have different forks based on the transactions included in a block, leading to diverging views (vertical relationship to finality).
- **Delayed Confirmations**: It can take significant time to finalize transactions (horizontal relationship to finality).

The primary settlement layer for rollups is not "settled" until it reaches finality, which takes approximately 13 minutes, raising the question: **How do rollups ensure they align with the correct (canonical) Ethereum timeline?**


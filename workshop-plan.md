# Graph Neural Networks Workshop — One-Day Plan

**Date:** Friday, 2026-10-23
**Organizer's group:** Central Beijing (research group)
**Host venue:** Tongji University, Siping Road Campus, Shanghai

---

## 1. Venue

### Tongji University Siping Road Campus (同济大学四平路校区)

| Item | Detail |
|---|---|
| Street address (main gate) | **1239 Siping Road (四平路1239号), Yangpu District, Shanghai 200092, China** |
| Alternate campus address (north side) | 50 Chifeng Road (赤峰路50号), Yangpu District, Shanghai 200092, China |
| Coordinates | **31.283136 N, 121.500834 E** |
| Phone | 021 6598 3643 |
| Website | https://www.tongji.edu.cn/ |

### From Shanghai Hongqiao Railway Station (上海虹桥) to the venue — by car

- **Distance: 27.2 km**
- **Driving time: approx. 36 minutes** (mainly via the Middle Ring Road / 中环路, then 中山北二路 → 密云路 → Chifeng Road)

### Lunch recommendation (walking distance)

**Tongji University Xueyuan Diet Square (同济大学学苑饮食广场)** — the campus dining hall / food court on Siping Road, Yangpu District, Shanghai 200092 (plus code 7GJ3+X8C).

- Rating: 4.3 / 5; phone 021 6598 2200
- **Walking distance from the campus: ~0.3 km / ~4 minutes** — perfect for a mid-workshop group lunch without leaving the area.

---

## 2. Travel (Friday, 2026-10-23)

### 2.1 Morning: central Beijing → Beijing South Railway Station (北京南)

- **Driving time from central Beijing (Zhengyi Road / Tiananmen area): approx. 21 minutes, 8.8 km** (via 崇文门外大街 → 天坛路 → 南二环 → 永外大街).
- Recommend leaving central Beijing **around 07:00–07:10** to arrive comfortably before the 07:52 departure.

### 2.2 Outbound: Beijing South → Shanghai Hongqiao (high-speed G, morning)

**Recommended train: G37**

| Item | Detail |
|---|---|
| Train | **G37** (high-speed, air-conditioned) |
| Departure | **Beijing South (北京南) 07:52** |
| Arrival | **Shanghai Hongqiao (上海虹桥) 12:35** |
| Duration | 4 h 43 m |

**Stops of G37 along the way (for our journey):**

| # | Station | Arrive | Depart |
|---|---|---|---|
| 1 | 北京南 Beijing South | — | 07:52 |
| 2 | 济南西 Jinan West | 09:14 | 09:18 |
| 3 | 南京南 Nanjing South | 11:15 | 11:18 |
| 4 | 镇江南 Zhenjiang South | 11:36 | 11:47 |
| 5 | 上海虹桥 Shanghai Hongqiao | 12:35 | (terminus for us) |

G37 then continues to 嘉兴南 Jiaxing South (13:04/13:07) and 杭州东 Hangzhou East (13:31).

**Why G37:** it is the fastest morning G service on the Beijing South → Shanghai Hongqiao run that still has tickets for a group (as of writing: business class 15 tickets left ¥2,315, first class 3 left ¥1,058, second class available ¥661). The trains that are a few minutes faster on paper — G9 (10:00→14:35, 4:35), G11 (10:03→14:39, 4:36), G7 (09:00→13:37, 4:37) — are sold out in all seated classes (standing tickets only). If you prefer the earliest possible arrival instead, **G1** (06:30 → 11:24, 4:54) had all classes available.

*Other morning G options seen: G531 06:08→12:04 (5:56), G547 06:18→12:11 (5:53), G1 06:30→11:24 (4:54), G565 07:07→13:12 (6:05), G549 07:13→13:03 (5:50), G597 07:42→13:49 (6:07), G37 07:52→12:35 (4:43), G599 08:15→14:14 (5:59), G633 08:37→15:01 (6:24), G7 09:00→13:37 (4:37), G669 09:07→14:59 (5:52), G643 09:18→15:20 (6:02), G693 09:47→15:56 (6:09), G9 10:00→14:35 (4:35), G11 10:03→14:39 (4:36), G23 11:00→15:37 (4:37).*

### 2.3 Return: Shanghai Hongqiao → Beijing South (evening)

**Recommended train: G30**

| Item | Detail |
|---|---|
| Train | **G30** |
| Departure | **Shanghai Hongqiao (上海虹桥) 18:52** |
| Arrival | **Beijing South (北京南) 23:21** |
| Duration | 4 h 29 m |

**Why G30:** it is the fastest evening service back (4:29) and gives the group the full workshop day at Tongji, arriving back in Beijing at 23:21. Note that as of writing only standing tickets remain on G30 — book immediately, or use the alternatives below.

*Evening alternatives from Shanghai Hongqiao: G26 17:00→21:32 (4:32, standing only), G726 17:16→23:02 (5:46, all classes available), G808 17:25→23:16 (5:51), G810 17:46→23:42 (5:56). If seats in every class are essential, G726 was the only evening option with full availability.*

### 2.4 On arrival in Shanghai

Taxi/car from Shanghai Hongqiao to the campus: **27.2 km, ~36 minutes**, so the group reaches the venue around **13:15–13:30** after the 12:35 arrival — leaving time to settle in before the afternoon sessions, with lunch at the Xueyuan Diet Square next door.

---

## 3. Pre-reads: Graph Neural Networks reading list (arXiv)

> Note: the arXiv search API was rate-limited during preparation, so these papers were verified by retrieving them directly from arXiv (titles and authors confirmed from the retrieved texts). Five papers are listed — more than the three requested.

1. **Semi-Supervised Classification with Graph Convolutional Networks** — Thomas N. Kipf, Max Welling. *arXiv:1609.02907*. The original GCN paper: a scalable, first-order approximation of spectral graph convolutions for semi-supervised node classification. (The essential starting point.)

2. **Inductive Representation Learning on Large Graphs (GraphSAGE)** — William L. Hamilton, Rex Ying, Jure Leskovec. *arXiv:1706.02216*. Inductive node embeddings via neighborhood sampling and aggregation — how GNNs generalize to unseen nodes and graphs.

3. **Graph Attention Networks** — Petar Veličković, Guillem Cucurull, Arantxa Casanova, Adriana Romero, Pietro Liò, Yoshua Bengio. *arXiv:1710.10903*. Masked self-attentional layers that weight neighbors adaptively; inductive and transductive benchmarks (Cora, Citeseer, Pubmed, PPI).

4. **How Powerful are Graph Neural Networks?** — Keyulu Xu, Weihua Hu, Jure Leskovec, Stefanie Jegelka. *arXiv:1810.00826*. The theoretical framework tying GNN expressiveness to the Weisfeiler–Lehman test, and the Graph Isomorphism Network (GIN).

5. **A Comprehensive Survey on Graph Neural Networks** — Zonghan Wu, Shirui Pan, Fengwen Chen, Guodong Long. *arXiv:1901.00596*. A broad taxonomy (recurrent, convolutional, graph autoencoder, spatial-temporal GNNs) plus applications, benchmarks and open-source resources — useful background for everyone.

---

## 4. Quick reference — the day at a glance

| Time | Item |
|---|---|
| ~07:00 | Leave central Beijing by car (~21 min drive, 8.8 km) |
| 07:52 | **G37 departs Beijing South** (stops: Jinan West, Nanjing South, Zhenjiang South) |
| 12:35 | Arrive Shanghai Hongqiao |
| ~13:15 | Arrive Tongji Siping campus (27.2 km, ~36 min by car) |
| Midday | Lunch at Xueyuan Diet Square (4-min walk) |
| Afternoon | Workshop sessions |
| 18:52 | **G30 departs Shanghai Hongqiao** |
| 23:21 | Arrive Beijing South |

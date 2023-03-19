---
title: Assignment 1
subtitle: Computer performance, reliability, and scalability calculation
author: Yousof Rahimian
---

## 1.2 

#### a. Data Sizes

| Data Item                                  | Size per Item | 
|--------------------------------------------|--------------:|
| 128 character message.                     |           128 |
| 1024x768 PNG image                         |      0.031985 |
| 1024x768 RAW image                         |          1.57 | 
| HD (1080p) HEVC Video (15 minutes)         |         878.9 |
| HD (1080p) Uncompressed Video (15 minutes) |     160180.66 |
| 4K UHD HEVC Video (15 minutes)             |        5062.5 |
| 4k UHD Uncompressed Video (15 minutes)     |         40500 |
| Human Genome (Uncompressed)                |           0.8 |

#### b. Scaling

|                                           |  Size | # HD | 
|-------------------------------------------|------:|-----:|
| Daily Twitter Tweets (Uncompressed)       |    64 |    1 |
| Daily Twitter Tweets (Snappy Compressed)  | 42.67 |    1 |
| Daily Instagram Photos                    |  2.40 |    1 |
| Daily YouTube Videos                      | 42.19 |   13 |
| Yearly Twitter Tweets (Uncompressed)      | 23.36 |    8 |
| Yearly Twitter Tweets (Snappy Compressed) | 15.57 |    5 |
| Yearly Instagram Photos                   |   876 |      |
| Yearly YouTube Videos                     | 15399 |      |

#### c. Reliability
|                                    | # HD | # Failures |
|------------------------------------|-----:|-----------:|
| Twitter Tweets (Uncompressed)      |    8 |       ~  1 |
| Twitter Tweets (Snappy Compressed) |    5 |       ~  1 |
| Instagram Photos                   |  263 |       ~  5 |
| YouTube Videos                     | 1540 |       ~ 26 |

#### d. Latency

|                           | One Way Latency |
|---------------------------|----------------:|
| Los Angeles to Amsterdam  |        44.67 ms |
| Low Earth Orbit Satellite |          4.5 ms |
| Geostationary Satellite   |       178.93 ms |
| Earth to the Moon         |         1922 ms |
| Earth to Mars             |    6.94 minutes | 

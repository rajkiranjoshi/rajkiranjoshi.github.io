---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my (more up-to-date) publications on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

* LinkGuardian: Mitigating the impact of packet corruption loss with link-local retransmission [APNet '22]  
  **Raj Joshi**, Qi Guo, Nishant Budhdev, Ayush Mishra, Mun Choon Chan, Ben Leong  
  \[[paper]({{ base_path }}/files/papers/apnet22-linkguardian.pdf)\]  \[[slides]({{ base_path }}/files/slides/apnet22-linkguardian-slides.pptx)\]

* Hop-On Hop-Off Routing [APNet '22]  
  Jialong Li, Yiming Lei, Federico De Marchi, **Raj Joshi**, Balakrishnan Chandrasekaran, Yiting Xia  
  \[[paper]({{ base_path }}/files/papers/apnet22-hoho.pdf)\]
  \[[slides]({{ base_path }}/files/slides/apnet22-hoho-slides.pdf)\]

* FSA: Fronthaul Slicing Architecture for 5G using dataplane programmable switches [MOBICOM '22]  
  Nishant Budhdev, **Raj Joshi**, Pravein Govindan Kannan, Mun Choon Chan, Tulika Mitra  
  \[[paper](https://dl.acm.org/doi/10.1145/3447993.3483247?cid=82658740957)\]

* Debugging Transient Faults in Data Centers using Synchronized Network-wide Packet Histories [NSDI '21]  
  Pravein Govindan Kannan, Nishant Budhdev\*, **Raj Joshi**\*, Mun Choon Chan  
  (* equal contribution)  
  \[[paper](https://www.usenix.org/system/files/nsdi21-kannan.pdf)\]
  \[[slides]({{ base_path }}/files/slides/nsdi21-syndb-slides.pdf)\]
  \[[simulator source code](https://github.com/rajkiranjoshi/syndb-sim)\]

* Slicing 5G fronthaul networks using programmable switches [CoNEXT '20, Posters & Demos]  
  Nishant Budhdev, **Raj Joshi**, Pravein Govindan Kannan, Mun Choon Chan, Tulika Mitra  
  \[[extended abstract]({{ base_path }}/files/papers/conext21-fsa.pdf)\]

* The Great Internet TCP Congestion Control Census [SIGMETRICS '20]  
  Ayush Mishra, Xiangpeng Sun, Atishya Jain, Sameer Pande, **Raj Joshi**, and Ben Leong  
  \[[paper]({{ base_path }}/files/papers/sigmetrics20-gordon.pdf)\] \[[slides]({{ base_path }}/files/slides/sigmetrics19-gordon-slides.pdf)\]

* SQR: In-network Packet Loss Recovery from Link Failures for Highly Reliable Datacenter Networks [ICNP '19]  
  Ting Qu, **Raj Joshi**, Mun Choon Chan, Ben Leong, Deke Guo, Zhong Liu  
  ![image]({{ base_path }}/images/trophy.png) ***Best Paper Award!***  
  \[[paper]({{ base_path }}/files/papers/icnp2019-sqr.pdf)\] \[[slides]({{ base_path }}/files/slides/icnp19-sqr-slides.pdf)\]

* TimerTasks: Towards Time-driven Execution in Programmable Dataplanes [SIGCOMM '19, Posters & Demos]  
  **Raj Joshi**, Ben Leong, Mun Choon Chan  
  \[[extended abstract]({{ base_path }}/files/papers/sigcomm19-timertasks.pdf)\]  \[[poster]({{ base_path }}/files/slides/sigcomm19-timertasks-poster.pdf)\]

* P4TrafficTool: Automated Code Generation for P4 Traffic Generators and Analyzers [SOSR '19, Posters & Demos]  
  Deepanshu Jindal, **Raj Joshi**, Ben Leong  
  \[[extended abstract]({{ base_path }}/files/papers/sosr19-p4trafficTool.pdf)\]  \[[poster]({{ base_path }}/files/slides/sosr19-p4traffictool-poster.pdf)\]

* Precise Time-synchronization in the Data-Plane using Programmable Switching ASICs [SOSR '19]  
  Pravein Govindan Kannan, **Raj Joshi**, Mun Choon Chan  
  ![image]({{ base_path }}/images/trophy.png) ***Best Paper Award!***  
  \[[paper]({{ base_path }}/files/papers/sosr19-dptp.pdf)\]

* BurstRadar: Practical Real-time Microburst Monitoring for Datacenter Networks [APSys '18]  
  **Raj Joshi**, Ting Qu, Mun Choon Chan, Ben Leong, Boon Thau Loo  
  \[[paper]({{ base_path }}/files/papers/apsys18-burstradar.pdf)\]
  \[[slides]({{ base_path }}/files/slides/apsys18-burstradar-slides.pdf)\]

* EleTrack: Ultra-Low-Power Retrofitted Monitoring for Elevators [EWSN '18]  
  Mobashir Mohammad, **Raj Joshi**, Mun Choon Chan  
  \[[paper]({{ base_path }}/files/papers/ewsn18-eletrack.pdf)\]
  \[[slides]({{ base_path }}/files/slides/ewsn18-eletrack-slides.pptx)\]

* HaptiColor: Interpolating Color Information as Haptic Feedback to Assist the Colorblind [ACM CHI '16]  
  Marta G. Carcedo, Soon Hau Chua, Simon Perrault, Pawel Wozniak, **Raj Joshi***, Mohammad Obaid, Morten Fjeld, Shengdong Zhao  
  (\* I contributed to this work during my brief stint with the wonderful people at the [NUS-HCI](https://www.nus-hci.org/) Lab)  
  \[[paper]({{ base_path }}/files/papers/chi16-hapticolor.pdf)\]

* Feasibility Study of Mobile Phone WiFi Detection in Aerial Search and Rescue Operations [ACM APSys '13]  
  Wei Wang, **Raj Joshi**, Aditya Kulkarni, Wai Kay Leong and Ben Leong  
  \[[paper]({{ base_path }}/files/papers/apsys13-sos.pdf)\]
  \[[slides]({{ base_path }}/files/slides/apsys13-sos-slides.pdf)\]

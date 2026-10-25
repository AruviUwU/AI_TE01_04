# Gambaran Umum

Repositori ini mengimplementasikan beberapa algoritma perencanaan jalur (*path planning*) yang umum digunakan dalam bidang robotika, termasuk algoritma berbasis pencarian (*Search-based Algorithms*) dan algoritma berbasis pengambilan sampel (*Sampling-based Algorithms*).

Setiap algoritma dilengkapi dengan animasi untuk memperlihatkan proses eksekusinya. Makalah ilmiah yang berkaitan dengan algoritma-algoritma tersebut dapat dilihat pada bagian [Papers](https://github.com/zhm-real/PathPlanning#papers).

## Struktur Direktori

```text
.
├── Search-based Planning
│   ├── Breadth-First Searching (BFS)
│   ├── Depth-First Searching (DFS)
│   ├── Best-First Searching
│   ├── Dijkstra's
│   ├── A*
│   ├── Bidirectional A*
│   ├── Anytime Repairing A*
│   ├── Learning Real-time A* (LRTA*)
│   ├── Real-time Adaptive A* (RTAA*)
│   ├── Lifelong Planning A* (LPA*)
│   ├── Dynamic A* (D*)
│   ├── D* Lite
│   └── Anytime D*
├── Sampling-based Planning
│   ├── RRT
│   ├── RRT-Connect
│   ├── Extended-RRT
│   ├── Dynamic-RRT
│   ├── RRT*
│   ├── Informed RRT*
│   ├── RRT* Smart
│   ├── Anytime RRT*
│   ├── Closed-Loop RRT*
│   ├── Spline-RRT*
│   ├── Fast Marching Trees (FMT*)
│   └── Batch Informed Trees (BIT*)
└── Papers
```

## Animasi Algoritma Berbasis Pencarian (Search-Based)

### Best-First dan Dijkstra

<div align="right">
<table>
  <tr>
    <td><img src="https://github.com/zhm-real/path-planning-algorithms/blob/master/Search_based_Planning/gif/BF.gif" alt="Best-First Search" width="400"/></td>
    <td><img src="https://github.com/zhm-real/path-planning-algorithms/blob/master/Search_based_Planning/gif/Dijkstra.gif" alt="Algoritma Dijkstra" width="400"/></td>
  </tr>
</table>
</div>

### A* dan Variasinya

<div align="right">
<table>
  <tr>
    <td><img src="https://github.com/zhm-real/path-planning-algorithms/blob/master/Search_based_Planning/gif/Astar.gif" alt="Algoritma A*" width="400"/></td>
    <td><img src="https://github.com/zhm-real/path-planning-algorithms/blob/master/Search_based_Planning/gif/Bi-Astar.gif" alt="Bidirectional A*" width="400"/></td>
  </tr>
</table>
<table>
  <tr>
    <td><img src="https://github.com/zhm-real/path-planning-algorithms/blob/master/Search_based_Planning/gif/RepeatedA_star.gif" alt="Repeated A*" width="400"/></td>
    <td><img src="https://github.com/zhm-real/path-planning-algorithms/blob/master/Search_based_Planning/gif/ARA_star.gif" alt="Anytime Repairing A*" width="400"/></td>
  </tr>
</table>
<table>
  <tr>
    <td><img src="https://github.com/zhm-real/path-planning-algorithms/blob/master/Search_based_Planning/gif/LRTA_star.gif" alt="Learning Real-Time A*" width="400"/></td>
    <td><img src="https://github.com/zhm-real/path-planning-algorithms/blob/master/Search_based_Planning/gif/RTAA_star.gif" alt="Real-Time Adaptive A*" width="400"/></td>
  </tr>
</table>
<table>
  <tr>
    <td><img src="https://github.com/zhm-real/path-planning-algorithms/blob/master/Search_based_Planning/gif/D_star.gif" alt="Dynamic A*" width="400"/></td>
    <td><img src="https://github.com/zhm-real/path-planning-algorithms/blob/master/Search_based_Planning/gif/LPAstar.gif" alt="Lifelong Planning A*" width="400"/></td>
  </tr>
</table>
<table>
  <tr>
    <td><img src="https://github.com/zhm-real/path-planning-algorithms/blob/master/Search_based_Planning/gif/ADstar_small.gif" alt="Anytime D*" width="400"/></td>
    <td><img src="https://github.com/zhm-real/path-planning-algorithms/blob/master/Search_based_Planning/gif/ADstar_sig.gif" alt="Anytime D* - Variasi" width="400"/></td>
  </tr>
</table>
</div>

## Animasi Algoritma Berbasis Pengambilan Sampel (Sampling-Based)

### RRT dan Variasinya

<div align="right">
<table>
  <tr>
    <td><img src="https://github.com/zhm-real/PathPlanning/blob/master/Sampling_based_Planning/gif/RRT_2D.gif" alt="RRT 2D" width="400"/></td>
    <td><img src="https://github.com/zhm-real/PathPlanning/blob/master/Sampling_based_Planning/gif/Goal_biasd_RRT_2D.gif" alt="Goal-Biased RRT 2D" width="400"/></td>
  </tr>
</table>
<table>
  <tr>
    <td><img src="https://github.com/zhm-real/PathPlanning/blob/master/Sampling_based_Planning/gif/RRT_CONNECT_2D.gif" alt="RRT-Connect 2D" width="400"/></td>
    <td><img src="https://github.com/zhm-real/PathPlanning/blob/master/Sampling_based_Planning/gif/Extended_RRT_2D.gif" alt="Extended RRT 2D" width="400"/></td>
  </tr>
</table>
<table>
  <tr>
    <td><img src="https://github.com/zhm-real/PathPlanning/blob/master/Sampling_based_Planning/gif/Dynamic_RRT_2D.gif" alt="Dynamic RRT 2D" width="400"/></td>
    <td><img src="https://github.com/zhm-real/PathPlanning/blob/master/Sampling_based_Planning/gif/RRT_STAR2_2D.gif" alt="RRT* 2D" width="400"/></td>
  </tr>
</table>
<table>
  <tr>
    <td><img src="https://github.com/zhm-real/PathPlanning/blob/master/Sampling_based_Planning/gif/RRT_STAR_SMART_2D.gif" alt="RRT*-Smart 2D" width="400"/></td>
    <td><img src="https://github.com/zhm-real/PathPlanning/blob/master/Sampling_based_Planning/gif/FMT.gif" alt="Fast Marching Trees" width="400"/></td>
  </tr>
</table>
<table>
  <tr>
    <td><img src="https://github.com/zhm-real/PathPlanning/blob/master/Sampling_based_Planning/gif/INFORMED_RRT_STAR_2D3.gif" alt="Informed RRT*" width="400"/></td>
    <td><img src="https://github.com/zhm-real/PathPlanning/blob/master/Sampling_based_Planning/gif/BIT2.gif" alt="Batch Informed Trees" width="400"/></td>
  </tr>
</table>
</div>

## Makalah Ilmiah (Papers)

### Perencanaan Berbasis Pencarian (Search-Based Planning)

- [A*](https://ieeexplore.ieee.org/document/4082128): *A Formal Basis for the Heuristic Determination of Minimum Cost Paths*
- [Learning Real-Time A*](https://arxiv.org/pdf/1110.4076.pdf): *Learning in Real-Time Search: A Unifying Framework*
- [Real-Time Adaptive A*](http://idm-lab.org/bib/abstracts/papers/aamas06.pdf): *Real-Time Adaptive A**
- [Lifelong Planning A*](https://www.cs.cmu.edu/~maxim/files/aij04.pdf): *Lifelong Planning A**
- [Anytime Repairing A*](https://papers.nips.cc/paper/2382-ara-anytime-a-with-provable-bounds-on-sub-optimality.pdf): *ARA*: Anytime A* with Provable Bounds on Sub-Optimality*
- [D*](http://web.mit.edu/16.412j/www/html/papers/original_dstar_icra94.pdf): *Optimal and Efficient Path Planning for Partially-Known Environments*
- [D* Lite](http://idm-lab.org/bib/abstracts/papers/aaai02b.pdf): *D* Lite*
- [Field D*](http://robots.stanford.edu/isrr-papers/draft/stentz.pdf): *Field D*: An Interpolation-Based Path Planner and Replanner*
- [Anytime D*](http://www.cs.cmu.edu/~ggordon/likhachev-etal.anytime-dstar.pdf): *Anytime Dynamic A*: An Anytime, Replanning Algorithm*
- [Focused D*](http://robotics.caltech.edu/~jwb/courses/ME132/handouts/Dstar_ijcai95.pdf): *The Focused D* Algorithm for Real-Time Replanning*
- [Potential Field](https://journals.sagepub.com/doi/abs/10.1177/027836498600500106), [materi presentasi (PPT)](https://www.cs.cmu.edu/~motionplanning/lecture/Chap4-Potential-Field_howie.pdf): *Real-Time Obstacle Avoidance for Manipulators and Mobile Robots*
- [Hybrid A*](https://ai.stanford.edu/~ddolgov/papers/dolgov_gpp_stair08.pdf): *Practical Search Techniques in Path Planning for Autonomous Driving*

### Perencanaan Berbasis Pengambilan Sampel (Sampling-Based Planning)

- [RRT](http://msl.cs.uiuc.edu/~lavalle/papers/Lav98c.pdf): *Rapidly-Exploring Random Trees: A New Tool for Path Planning*
- [RRT-Connect](http://www-cgi.cs.cmu.edu/afs/cs/academic/class/15494-s12/readings/kuffner_icra2000.pdf): *RRT-Connect: An Efficient Approach to Single-Query Path Planning*
- [Extended-RRT](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1.7617&rep=rep1&type=pdf): *Real-Time Randomized Path Planning for Robot Navigation*
- [Dynamic-RRT](https://www.ri.cmu.edu/pub_files/pub4/ferguson_david_2006_2/ferguson_david_2006_2.pdf): *Replanning with RRTs*
- [RRT*](https://journals.sagepub.com/doi/abs/10.1177/0278364911406761): *Sampling-Based Algorithms for Optimal Motion Planning*
- [Anytime-RRT*](https://dspace.mit.edu/handle/1721.1/63170): *Anytime Motion Planning Using the RRT**
- [Closed-Loop RRT* (CL-RRT*)](http://acl.mit.edu/papers/KuwataTCST09.pdf): *Real-Time Motion Planning with Applications to Autonomous Urban Driving*
- [Spline-RRT*](https://ieeexplore.ieee.org/abstract/document/6987895?casa_token=B9GUwVDbbncAAAAA:DWscGFLIa97ptgH7NpUQUL0A2ModiiBDBGklk1z7aDjI11Kyfzo8rpuFstdYcjOofJfCjR-mNw): *Optimal Path Planning Based on Spline-RRT* for Fixed-Wing UAVs Operating in Three-Dimensional Environments*
- [LQR-RRT*](https://lis.csail.mit.edu/pubs/perez-icra12.pdf): *Optimal Sampling-Based Motion Planning with Automatically Derived Extension Heuristics*
- [RRT#](http://dcsl.gatech.edu/papers/icra13.pdf): *Use of Relaxation Methods in Sampling-Based Algorithms for Optimal Motion Planning*
- [RRT*-Smart](http://save.seecs.nust.edu.pk/pubs/ICMA2012.pdf): *Rapid Convergence Implementation of RRT* Towards Optimal Solution*
- [Informed RRT*](https://arxiv.org/abs/1404.2334): *Optimal Sampling-Based Path Planning Focused via Direct Sampling of an Admissible Ellipsoidal Heuristic*
- [Fast Marching Trees (FMT*)](https://arxiv.org/abs/1306.3532): *A Fast Marching Sampling-Based Method for Optimal Motion Planning in Many Dimensions*
- [Motion Planning Using Lower Bounds (MPLB)](https://ieeexplore.ieee.org/document/7139773): *Asymptotically-Optimal Motion Planning Using Lower Bounds on Cost*
- [Batch Informed Trees (BIT*)](https://arxiv.org/abs/1405.5848): *Sampling-Based Optimal Planning via the Heuristically Guided Search of Implicit Random Geometric Graphs*
- [Advanced Batch Informed Trees (ABIT*)](https://arxiv.org/abs/2002.06589): *Sampling-Based Planning with Advanced Graph-Search Techniques (ICRA 2020)*
- [Adaptively Informed Trees (AIT*)](https://arxiv.org/abs/2002.06599): *Fast Asymptotically Optimal Path Planning Through Adaptive Heuristics (ICRA 2020)*

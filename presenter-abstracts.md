# Thursday, February 3rd, 2022


## <a id="ko">Kunle Olukoton - _The Future of AI Systems - Let the Data Flow!_</a>

<img alt="Kunle Olukoton Headshot" src="https://github.com/gt-crnch/crnch-summit-2022/blob/main/presenter_slides/Thursday_02_03_22/headshots/ko_headshot.jpg" width="200" height="200">

<a id="ko_ab"></a>**Abstract:** As the benefits from Moore’s Law diminish, future computing performance improvements must
rely on specialized accelerators for applications in high performance computing, artificial
intelligence, and traditional data processing. These challenging applications are characterized
by terabyte sized models, data sparsity and irregular control flow. In this talk, we explain how
Reconfigurable Dataflow Accelerators (RDAs) can be used to accelerate a broad set of dataintensive
applications with these characteristics. SambaNova Systems is using RDA technology
contained in Reconfigurable Dataflow Units (RDUs) to achieve record‐setting performance on
challenging machine learning tasks. We will describe how RDAs can also be used to accelerate
database and HPC applications with irregular control and data flow using a new execution
model called Dataflow threads.


<a id="ko_bio"></a>**Biography:** Kunle Olukotun is the Cadence Design Professor of Electrical Engineering and
Computer Science at Stanford University. Olukotun is a pioneer in multi-core processor
design and the leader of the Stanford Hydra chip multiprocessor (CMP) research
project.

In 2017 Olukotun co-founded SambaNova Systems, a Machine Learning and Artificial
Intelligence company, and continues to lead as their Chief Technologist. Prior to
SambaNova Systems, Olukotun founded Afara Websystems to develop highthroughput,
low-power multi-core processors for server systems. The Afara multi-core
processor, called Niagara, was acquired by Sun Microsystems and now powers
Oracle’s SPARC-based servers.

Olukotun is the Director of the Pervasive Parallel Lab and a member of the Data Analytics for What’s Next (DAWN) Lab, developing infrastructure for usable machine learning. Olukotun is also an ACM Fellow and IEEE Fellow for contributions to multiprocessors on a chip and multi-threaded processor design. He recently won the IEEE Computer Society’s Harry H. Goode Memorial Award and was also elected to the National Academy of Engineering. Kunle received his Ph.D. in Computer Engineering from The University of Michigan.

## <a id="rg"> Roberto Gioiosa - _Re‐Imagining HW/SW Co‐Design: a Flexible, Composable, and Agile approach_</a>

<img alt="Roberto Gioiosa Headshot" src="https://github.com/gt-crnch/crnch-summit-2022/blob/main/presenter_slides/Thursday_02_03_22/headshots/rg_headshot.jpg" width="300" height="250">

<a id="rg_ab"></a>**Abstract:** The need of processing and analyzing extremely large amount of data with real‐time and power/energy constraints has motivated the development of many highly‐specialized and energy  efficient  architectural  concepts.  This  trend  is  evident  in  embedded  systems,  such  as  mobile  phones  or  smart  sensors,  where  systems  contain  a  myriad  of  small,  specialized  ASIC processors. Large‐scale, HPC systems have also embraced heterogeneous devices to speed up computation while maintaining a strict power budget. Looking forward, one can imagine that more application‐specific accelerators will be incorporated into SoC designs, which will contain general‐purpose,  programmable  processing  elements,  such  as  CPU  and  GPU  cores,  fixed,  application‐specific  accelerators  (e.g.,  FFT  or  GEMM),  and  semi‐programmable  CGRA  devices. Designing such increasingly complex device become and incredibly difficult task.  

In the AI space, this revolution is already happening, with many custom hardware designs already available. The Center for co‐design of ARtificial Intelligence focused Architectures and Algorithms (ARIAA)  is  a  DOE/ASCR  project  lead  by  Pacific  Northwest  National  Laboratory  (PNNL)  in  collaboration with Sandia National Laboratory (SNL), Georgia Tech (GT), NVIDIA, and Qualcomm. ARIAA’s  objectives  are  to  co‐design  novel  architectures,  algorithms,  and  programming  abstractions to enable AI‐based DOE applications and support sparse, explainable, and domain‐informed AI models. Ultimately, ARIAA aims at understanding how AI‐focused architectures can accelerate traditional, emerging, and AI DOE workloads, identifying computational kernels that can  be  effectively  replaced  by  accurate  AI/ML  methods,  identifying  opportunities  to  leverage  AI/ML methods to support computation and data analytics, and understanding and designing AI accelerators for future explainable and domain‐aware AI methods. This talk will describe ARIAA’s novel approach to co‐design of AI/HPC accelerators, programming abstractions, and algorithms and how various technologies are integrated to form and end‐to‐end solution. 

<a id="rg_bio"></a>**Bio:** Dr. Roberto Gioiosa is a senior research scientist at the Pacific Northwest National Laboratory (PNNL) in the High‐Performance Computing Group and team lead of the Scalable and Emerging Technology  Team  (SET).  His  research  interests  include  operating  systems  and  runtimes,  high‐performance  computer  architectures,  memory,  and  networks,  parallel  and  distributed programming models, resilience, performance and power modeling and analysis, and embedded systems.  

Dr. Gioiosa earned his Ph.D. in 2006 from the University of Rome "Tor Vergara", Rome Italy. He has  worked  at  the  Los  Alamos  National  Laboratory  (LANL)  (2004‐2005),  the  Barcelona  Supercomputing Center (BSC) (2006‐2008 and 2009‐2012), the IBM T.J. Watson Research Center (2008‐2009) where he contributed to the development of the Compute Node Kernel for BG/Q systems, and Oak Ridge National Laboratory (ORNL) (2017‐2018).

Currently, his projects include the development of system software for extremely heterogeneous systems, system software for scalable distributed systems, DSSoC design, evaluation of emerging architecture  and  technologies  for  exascale  systems  and  applications,  and  development  of  operating systems for exascale systems. Dr. Gioiosa leads the DOE/ASCR Center for co‐design of ARtificial Intelligence focused Architectures and Algorithms (ARIAA). He is a member of the ACM and IEEE Computer Society.  

## <a id="ch"> Callie Ho - _GenGNN: A Generic FPGA Framework for Graph Neural Network Acceleration_</a>

<img alt="Callie Ho Headshot" src="https://github.com/gt-crnch/crnch-summit-2022/blob/main/presenter_slides/Thursday_02_03_22/headshots/ch_headshot.jpg" width="280" height="350">

<a id="ch_ab"></a>**Abstract:** Graph neural networks (GNNs) have recently exploded in popularity thanks to their broad applicability to ubiquitous graph‐related problems such as quantum chemistry, drug discovery, and high energy physics. However, meeting demand for novel GNN models and fast inference simultaneously is challenging because of the gap between the difficulty in developing efficient FPGA accelerators and the rapid pace of the creation of new GNN models. Prior art focuses on the acceleration of specific classes of GNNs but lacks the generality to work across existing models or to extend to new and emerging GNN models. In this work, we propose a generic GNN acceleration framework using High‐Level Synthesis (HLS), named GenGNN, with two‐fold goals. First, we aim to deliver ultra‐fast GNN inference without any graph pre‐processing for real‐time requirements. Second, we aim to support a diverse set of GNN models with the extensibility to flexibly adapt to new models. The framework features an optimized message‐passing structure applicable to all models, combined with a rich library of model‐specific components. We verify our implementation on‐board on the Xilinx Alveo U50 FPGA and observe a speed‐up of up to 25x against CPU (6226R) baseline and 13x against GPU (A6000) baseline. 

<a id="ch_bio"></a> **Bio:** Cong (Callie) Hao is an assistant professor in ECE at Georgia Tech, where she currently holds the Sutterfield Family Early Career Professorship. She was a postdoctoral fellow in the School from 2020-2021 and also worked as a postdoctoral researcher in ECE at the University of Illinois at Urbana-Champaign from 2018-2020. She received the Ph.D. degree in Electrical Engineering from Waseda University in 2017, and the M.S. and B.S. degrees in Computer Science
and Engineering from Shanghai Jiao Tong University. Her primary research interests lie in the joint area of efficient hardware design and machine learning
algorithms, as well as reconfigurable and high-efficiency computing and electronic design automation.

## <a id="ag"> Ada Gavrilovska - _Domain‐specific Management of Complex Memory Fabrics_</a>

<img alt="Ada Gavrilovska Headshot" src="https://github.com/gt-crnch/crnch-summit-2022/blob/main/presenter_slides/Thursday_02_03_22/headshots/ag_headshot.jpg" width="250" height="350">

<a id="ag_ab"></a>**Abstract:** The continued need for scaling of performance, capacity, and cost efficiency for data‐intensive applications, is giving rise to new system designs combining heterogeneous memory components, accelerators and accelerator‐near memory, interconnected with programmable high‐performance interconnects. Maximizing the benefits of the resulting complex memory fabrics requires new methods for coordinating decisions concerning data placement, movement, accesses and transformations. This talk will discuss opportunities for new data‐driven and domain‐specific resource management methods, using graph analytics as an example.

<a id="ag_bio"></a> **Bio:** Ada Gavrilovska is Associate Professor in the School of Computer Science at Georgia Tech. She directs the Kernel research group, which focuses on designing systems for emerging technologies, and on developing new systems software solutions in response to new hardware, applications, and use cases. Her recent research is driven by two major trends rooted in the exponential growth in demand for data and for ever‐faster insights from such data – the proliferation of new memory system designs, and the shift to edge computing. Gavrilovska’s research is supported by the NSF, the Department of Energy, the SRC/DARPA JUMP program, and by multiple industry awards. She has served as program chair for ACM HPDC’22, USENIX ATC’20, and as an Associate Editor for the IEEE Transactions on Cloud Computing. 

## <a id="si"> Subramanian "Subu" Iyer - _Chips, Dies, Chiplets and Dielets and Other Crunchy stuff_

<img alt="Subu Iyer Headshot" src="https://github.com/gt-crnch/crnch-summit-2022/blob/main/presenter_slides/Thursday_02_03_22/headshots/si_headshot.jpg" width="200" height="200">
  
<a id="si_ab"></a>**Abstract:** Packaging is undergoing a major paradigm shift and promises to take up the lag caused by the slowing down of CMOS scaling. In this paper, we examine these shifts that have been driven by the scaling of key packaging metrics such as bump pitch, trace pitch, inter-die spacing and alignment. The goal of advanced packaging is to enable the same benefits that Moore/Dennard scaling has accomplished for CMOS viz. density, performance, power, and cost. The vehicles that advanced packaging employs are somewhat different: dielets/chiplets, advanced assembly techniques, simplified inter-chip communication protocols and cost optimization via the use of optimized heterogeneous technologies. Another important aspect of advanced packaging is the adoption and adaptation of silicon technology methods to packaging. In this talk we will discuss these technologies and some instantiation examples that we have developed at UCLA. 
  
<a id="si_bio"></a> **Bio:** Subramanian S. Iyer (Subu) is Distinguished Professor and holds the Charles P. Reames Endowed Chair in the Electrical  Engineering  Department  and  a  joint  appointment  in  the  Materials  Science  and  Engineering  Department  at  the  University  of  California  at  Los  Angeles.  He  is  Director  of  the  Center  for  Heterogeneous Integration  and  Performance  Scaling  (UCLA  CHIPS).  Prior  to  that  he  was  an  IBM  Fellow.  His  key  technical  contributions  have  been  the  development  of  the  world’s  first  SiGe  base  HBT,  Salicide,  electrical  fuses, embedded  DRAM and 45nm technology node used to make the first generation of truly low power portable  devices as well as the first commercial interposer and 3D integrated products. He also was among the first to commercialize bonded SOI for CMOS applications through a start‐up called SiBond LLC. More recently, he has been exploring new packaging paradigms and device innovations that may enable wafer‐scale architectures, in‐memory analog compute and medical engineering applications. He has published over 300 papers and holds over 75 patents. He has received several outstanding technical achievements and corporate awards at IBM. He is an  IEEE Fellow, an APS Fellow, an iMAPS Fellow and a Distinguished Lecturer of the IEEE EDS and EPS and a  member of the Board of Governors of IEEE EPS. He is also a Fellow of the National Academy of Inventors. He is a Distinguished Alumnus of IIT Bombay and received the IEEE Daniel Noble Medal for emerging technologies in 2012 and the 2020 iMAPS Daniel C. Hughes Jr Memorial award and the iMAPS distinguished educator award in 2021. 

## <a id="ms"> Madhavan Swaminathan - _Dielet Integration and High Performance Computing_

<img alt="Madhavan Swaminathan Headshot" src="https://github.com/gt-crnch/crnch-summit-2022/blob/main/presenter_slides/Thursday_02_03_22/headshots/ms_headshot.jpg" width="250" height="400">
  
<a id="ms_ab"></a>**Abstract:** With a move into the post Moore era, the semiconductor industry is looking into
heterogeneous integration (HI) as a means for achieving system scaling. This involves
creating dense connectivity between smaller dies (called dielets) to achieve power,
performance, area, and cost (PPAC) metrics. With AI applications emerging, there is
increasing focus on the dis-aggregation of larger dies into smaller dies, with high density
connectivity between them. The ability to connect smaller dies on a larger platform such
as an interposer (or package) to create a super chips can provide compelling opportunities
for creating new architectures for computing.
  
In this presentation we will cover the landscape on the state of the art for HI and focus on
some new technologies being developed at the Packaging Research Center @ Georgia Tech
in the area of high performance computing.

<a id="ms_bio"></a>**Bio:** Madhavan Swaminathan is the John Pippin Chair in Microsystems
Packaging & Electromagnetics in the School of Electrical and
Computer Engineering (ECE), Professor in ECE with a joint
appointment in the School of Materials Science and Engineering
(MSE), and Director of the 3D Systems Packaging Research
Center (PRC), Georgia Tech (GT) (http://www.prc.gatech.edu).
He also serves as the Site Director for the NSF Center for
Advanced Electronics through Machine Learning (CAEML:
https://publish.illinois.edu/advancedelectronics/) and Leads the
Heterogeneous Integration area, at the SRC JUMP ASCENT
Center (https://ascent.nd.edu/). Prior to joining GT, he was with
IBM working on packaging for supercomputers.
He is the author of 530+ refereed technical publications and holds 31 patents. He is the
primary author and co-editor of 3 books and 5 book chapters, founder and co-founder of
two start-up companies, and founder of the IEEE Conference on Electrical Design of
Advanced Packaging and Systems (EDAPS), a premier conference sponsored by the IEEE
Electronics Packaging Society (EPS). He is an IEEE Fellow and has served as the
Distinguished Lecturer for the IEEE Electromagnetic Compatibility (EMC) society.

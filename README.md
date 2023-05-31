# proyecto_comunicacio_cientifica_asignatura
## Code_publication_Lab1
Alba Valero Viñals | u198684 | 251517
## TFG: Improvement and development of SurgicAR: an intraoperatory AugmentedReality application for Hospital del Mar by Maria Prieto
[tfg_sem2.pdf](https://github.com/avalerov/Code_publication_Lab1/files/11618533/tfg_sem2.pdf)

### State of art
AR and VR are increasingly being investigated for their applications to medical 
specialties as well as in medical training and education. As they are relatively new 
technologies, most applications are still under development, in addition, most of the 
studies of the literature research are observational in nature and were conducted on 
small cohorts of participants. Applications and research can be divided into five main
categories: educational and training, telemedicine, treatment performance, pre-operative 
and intra-operative use and others.

**Education and training**: In 1997 Mentice Medical developed the MIST-VR software 
for endoscopic training using early VR [19]. This company continued to improve this 
device until obtaining different versions nowadays. In 1999 Burdea et al. created a 
rectal examination simulation kit by allowing tactile feedback using PHANToM haptic 
device, this allowed trainees to experiment and exercise with a large amount of prostate 
image datasets and various clinical situations [20]. In 2010 Thomas et al. used an AR 
model for developing 3D brains for anatomical studies, while also adding a tactile 
component for interactive learning [21]. In 2014 MOVEO Foundation started using the
VR headset Oculus Rift to provide orthopaedic trainees with the virtual view of the 
operating surgeon, allowing a first-person view of the procedure being performed [18].
Since 2015 Case Western Reserve University and Cleveland Clinic use the AR headset 
Microsoft Hololens for teaching anatomy students [22]. In 2016 Ma et al. proposed 
using Microsoft Kinect for teaching anatomy by overlaying medical images over 
student’s bodies to increase anatomy understanding, they created an AR interactive 
‘digital mirror’ of the leaner [23]. In 2017 Rochlen et al. evaluated the training of 
medical students using AR with Epson Moverio headset, which created an anatomical 
layout of an internal venous system over a manikin that allowed the training for central 
venous catheterization insertion [24]. At the beginning of 2020, Imperial College 
London’s radiology students started using Microsoft Hololens2 to practice simulated 
medical procedures, as image-guided needle biopsies [25]. In addition, there are some 
devices already being commercialized allowing student’s training, as OSSOVR, a VR 
surgical simulation platform that offers realistic hand-based interactions, allowing 
training lessons by practicing with virtual tools that surgeons use for orthopedic and
spine surgeries [26]. In a similar way, FundamentalVR combines VR with tactile
simulators letting surgeons study and practice surgeries using realistic vibration 
patterns; haptic feedback gives doctors the feeling of holding actual tools [27]. 

**Telemedicine**: In 2010 VIPAR developed a support solution that allowed a remote 
surgeon to project their hands into the display of another surgeon wearing an AR 
headset [28]. In 2014 Davis et al. used an iPad AR-based tool to communicate from 
Alabama to Vietnam and provide both visual and verbal cues to assist with 
neurosurgical procedures [29]. Similarly, Ponce et al. used in 2016 the same tool to 
demonstrate effectiveness with orthopedic residents performing arthroscopic shoulder 
surgery in different cities [30]. In 2017 Wang et al. used the AR headset Microsoft 
Hololens to remotely train novices in procedures [31]. Currently, the company Proximie 
uses AR technology for performing remote surgical coaching by visualizing real-time or 
recorded operations performed by experts in other parts of the world [32].

**Treatment performance**: In 2006 AccuVein created a projector-like device that 
displays a map of the vasculature on the skin surface, which is useful to perform faster
blood drawings, for example [33]. In 2007 NeuroVR open source platform was tested to 
create different environments, such as a living room, a supermarket, or a park, aiming at 
behavioural rehabilitation of patients suffering from various phobias such as fear of 
flying, agoraphobia, acrophobia, and eating disorders [34]. In 2014 Hoffman et al.
tested the beneficial use of Oculus Rift VR headset as a distraction to reduce the level of 
pain experienced by a burns’ patient during occupational therapy [35]. 

**Surgery**: In 2009, Su et al. demonstrated the benefits of the use of intra-operative AR to 
guide robotic laparoscopic partial nephrectomies, by projecting 3D images onto the 
laparoscopic image to mark surgical incisions within the laparoscopic view [36]. In a 
similar way, in 2013 the Fraunhofer Research Institute (Germany) initiated the MEVIS 
project, which involved the use of an iPad-based AR application to support liver 
operations. It allowed pre-operative and intra-operative visualization of blood vessels 
overlaid into the patient’s organ [37]. In 2013 Cabrilo et al. used AR in neurosurgical 
procedures, by overlaying pre-operative images into the operator’s microscope to guide 
intra-operative dissections [38]. Since the approval in 2000 of the DaVinci robot 
(Intuitive Surgical Inc., Mountain View, USA) by the United States Food and Drug 
Administration (FDA), some experts such as Volonté et al. (2013) and Soler et al.
(2014) developed AR applications superimposing the preoperative 3D patient modeling 
onto the real intraoperative view of the patient using the master control system screen of 
the robot [39], [40]. In 2016 Dickey et al. performed a pilot study using ARAS, a novel 
AR surgical training tool that used Google Glass to aid in urologic minimally invasive 
surgeries. The study consisted on projecting a video footage of the sequential steps of 
the procedure onto the live view of the patient in real time. At the same time, they 
streamed live OR footage to a remote attending physician which could then interact 
with the surgical trainee by moving a cursor highlighting areas of interest to explain
details of the operation [41]. In 2017 Hospital Gregorio Marañón (Madrid) partnered 
with the medical company Exovite and started using the Microsoft HoloLens AR 
headset in orthopaedics and traumatology surgeries [42]. In 2018 St Mary’s Hospital 
and researchers at Imperial College London developed also an AR application 
combined with the Microsoft HoloLens headset that overlays images of CT scans onto 
the patient’s leg, enabling the surgeon to ‘see through’ the limb during surgery [43].
In addition, there are some devices being commercialized based on holographic images. 
An example is EchoPixel, an AR device that generates holographic-like images that 
doctors can rotate, resize or dissect to perform surgical planning [44]. Mevidis is 
another surgical AR application approved by the FDA that uses Microsoft Hololens, 
allowing visualization and navigation during a surgical intervention using holograms. 
The same company has developed an application that uses holograms with educational 
purposes, called AnatomyX [45]. Proprio also generates holograms in the surgical field 
[46] and is used in hospitals like Seattle Children’s and University of Washington 
Medicine (United States). SentiAR also generates real-time holographic images in the 
OR that the doctors can move with specific gestures [47]. TrueVision converts existing 
microscopes into digital surgery systems that can produce 3D images, this AR software 
has been used in ophthalmology, neurosurgery and microsurgeries. In addition, 
TrueVision partnered with the company Oculus and used the camera Pentacam-AXL to 
perform computer guidance in cataract and refractive eye procedures [48]. Finally, the 
company ImmersiveTouch creates VR solutions using the Oculus Rift headset for 
surgical planning, training and education [49]. This platform is currently used in Johns 
Hopkins, University of Chicago and University of Texas Hospitals. It is clear that 
holographic applications are becoming more popular in the surgical field, but in the last 
ten years, the generation of 3D printed models to aid in the preoperative planning and in 
intra-operative decisions making has grown in importance [37].

**Others**:In 2013 the application MedRef was developed, it enables hospital employees 
to retrieve medical records as blood results, medications or clinic notes, by patient facial 
recognition using AR Google Glasses [50]. In 2014 Crisalix developed a virtual 
aesthetics planning, based on demonstrate body changes in aesthetics such as breast 
enhancement [51]. In 2015 Carenzo et al. created an application that use the AR headset 
Google Glass in disaster triage using. They scanned geomarked quick-response codes 
(QR) to perform an electronic triaging of disaster patients [52]. In 2019 Follmann et al.
compared traditional triaging during a simulated mass casualty event to the triage using
HMD, they found that while traditional triaging was faster, triaging using interactive 
Smart Glasses was significantly more accurate [53]

### Limitations of the state of art
In this thesis she concluded that in order for the program to get better acquisitions with the marker. Not all the images were recognized by the program; they had to follow some requisites such as avoiding repetitive patterns, blurry aspects and symmetry, having high contrast (images with bright and dark regions work better), and containing elements with sharp edges and clearly defined shapes…

She finally chose a vector image with two-digit numbers and to print these markers, they looked for a material that was rigid, opaque, resistant to sterilization methods, and provided good color contrast. After considering various options, they found that plastic polymers like PLA were the best choice. PLA targets had excellent quality, were lightweight, easy to handle, and could be produced at a low cost. They also ensured ergonomic design for user comfort. Overall, PLA markers proved to be the preferred material for the markers.

The application initially faced compatibility problems when developed on an iOS laptop but successfully transitioned to a Windows laptop. The development process involved testing with different Unity versions, ultimately settling on Unity 2018 for seamless integration of the Vuforia SDK, a kit that allows augmented reality software development for mobile devices in order to generate augmented reality applications. Testing at home using the Unity "Game view" simulator and the Android application showcased accurate recognition of various targets, including paper printed, PLA, and virtual targets. There were no discernible differences in recognition between different fiducial markers or specific images. The application proved capable of displaying 2D medical images and videos, contributing to surgeons' confidence and anatomical understanding. Smartphones demonstrated efficient processing power without latency, and their cameras and screens provided high-quality visuals for precise target recognition and detailed segmentation.

Finally it overcame compatibility hurdles by transitioning to a Windows laptop and utilizing Unity 2018. Extensive testing validated accurate recognition of diverse targets on smartphones, while the application effectively presented 2D medical content. The smartphones exhibited optimal performance, ensuring smooth user experience with accurate segmentation and visualization.

This project has quite an interesting impact on how images are displayed as it allows and improves many of the applications it had before. Some applications of 3D models visualization would be that it facilitate anatomical understanding to plan and optimize surgical approaches, counseling with patients, medical students and residents’ education, surgical training, intraoperative navigation, implants generation, surgical guides and others.  

This application presented some limitations as the application only run in Android devices as mentioned before but it also faced many other challenges as that there is no Wi-Fi access in the OR zone, so an application that runs on this connection could not be used, smartphones and tablets cannot be sterilized (unless they are placed inside a sterile plastic bag, but this would affect the target recognition by the camera), lightning was also an issue for the application, as fro example laparoscopic surgeries take place with poor lightening and this difficulties the recognition of the marker by the sensors. Finally, the scanning, segmenting and building in order to generate the 3D model that the application processes are time consuming, meaning that this application could not be used in emergency situations.

To conclude, SurgicAR is a versatile application that can provide doctors with relevant patient information before and during surgery. It offers 3D segmentations, 2D patient scans, and videos, all within a single user-friendly interface. The designed fiducial markers are easy to print and ensure excellent tracking quality. The application runs on any Android smartphone, providing high-quality images. Its intuitive operation allows users to simply open the app, use a printed or virtual target object, and access the desired digital assets. It has great potential for various medical departments including urology, where it’s been already used, oncology, cardiology, and trauma surgery. It can also be used for medical education, preoperative counseling, and facilitating patient understanding through personalized 3D models. Overall, SurgicAR is a promising tool with a wide range of applications in clinical practice.


### How to improve it?
- SurgicAR should be tested in different hospital departments
- Should be tested in many surgeries in order to detect new posible flaws
- Should be implemente also for iOS devices
- Should add some other features and tool in the app
### References
[19] M. S. Wilson, A. Middlebrook, C. Sutton, R. Stone, and R. F. McCloy, “MIST 
VR: A virtual reality trainer for laparoscopic surgery assesses performance,” Ann. 
R. Coll. Surg. Engl., vol. 79, no. 6, pp. 403–404, 1997.

[20] G. Burdea, G. Patounakis, V. Popescu, and R. E. Weiss, “Virtual reality-based 
training for the diagnosis of prostate cancer,” IEEE Trans. Biomed. Eng., vol. 46, 
1999, doi: 10.1109/10.790503.

[21] R. G. Thomas, N. W. John, and J. M. Delieu, “Augmented reality for anatomical 
education,” J. Vis. Commun. Med., vol. 33, no. 1, pp. 6–15, 2010, doi: 
10.3109/17453050903557359.

[22] “CWRU takes the stage at Microsoft’s Build conference to show how HoloLens 
can transform learning,” Case Western Reserve University Research News, 2015. 
https://case.edu/hololens/ (accessed May 15, 2020).

[23] M. Ma et al., “Personalized augmented reality for anatomy education,” Clin. 
Anat., vol. 29, no. 4, pp. 446–453, 2016, doi: 10.1002/ca.22675.

[24] L. R. Rochlen, R. Levine, and A. R. Tait, “First-Person Point-of-ViewAugmented Reality for Central Line Insertion Training: A Usability and 
Feasibility Study,” Simul. Healthc., vol. 12, no. 1, pp. 57–62, 2017, doi: 
10.1097/SIH.0000000000000185.

[25] M. MacKay and T. Hurkxkens, “Holograms transform medical education and 
training at Imperial,” Imperial College London News, 2020. 
https://www.imperial.ac.uk/news/195093/holograms-transform-medicaleducation-training-imperial/ (accessed May 27, 2020).

[26] OSSO VR Company, “OSSO VR: the leading Virtual Reality surgical training & 
assessment platform.” https://ossovr.com (accessed May 10, 2020).

[27] “FundamentalVR: our work,” FundamentalVR website, 2018. 
http://www.fundamentalvr.com/our-work/ (accessed May 10, 2020).

[28] M. B. Shenai et al., “Virtual interactive presence and augmented reality (VIPAR) 
for remote surgical assistance,” Neurosurgery, vol. 68, pp. 200–207, 2011, doi: 
10.1227/NEU.0b013e3182077efd.

[29] M. C. Davis, D. D. Can, J. Pindrik, B. G. Rocque, and J. M. Johnston, “Virtual 
Interactive Presence in Global Surgical Education: International Collaboration 
Through Augmented Reality,” World Neurosurg., vol. 86, pp. 103–111, 2016, 
doi: 10.1016/j.wneu.2015.08.053.

[30] B. A. Ponce, J. K. Jennings, T. B. Clay, M. B. May, C. Huisingh, and E. D. 
Sheppard, “Telementoring: Use of augmented reality in orthopaedic education: 
AAOS exhibit selection,” J. Bone Jt. Surg., vol. 96, no. 10, 2014, doi: 
10.2106/JBJS.M.00928.

[31] S. Wang et al., “Augmented reality as a telemedicine platform for remote 
procedural training,” Sensors (Switzerland), vol. 17, no. 10, 2017, doi: 
10.3390/s17102294.

[32] “The Proximie solution,” Proximie website, 2020. 
https://www.proximie.com/our-solution/ (accessed May 10, 2020).

[33] R. K. Miyake et al., “Vein imaging: A new method of near infrared imaging, 
where a processed image is projected onto the skin for the enhancement of vein 
treatment,” Dermatologic Surg., vol. 32, pp. 1031–1038, 2006, doi: 
10.1111/j.1524-4725.2006.32226.x.

[34] G. Riva et al., “NeuroVR: An open source virtual reality platform for clinical 
psychology and behavioral neurosciences,” Stud. Health Technol. Inform., vol. 
125, pp. 394–399, 2007.

[35] H. G. Hoffman et al., “Feasibility of articulated arm mounted Oculus Rift Virtual 
Reality goggles for adjunctive pain control during occupational therapy in 
pediatric burn patients,” Cyberpsychol. Behav. Soc. Netw., vol. 17, pp. 397–401, 
2014, doi: 10.1089/cyber.2014.0058.

[36] L. M. Su, B. P. Vagvolgyi, R. Agarwal, C. E. Reiley, R. H. Taylor, and G. D. 
Hager, “Augmented Reality During Robot-assisted Laparoscopic Partial 
Nephrectomy: Toward Real-Time 3D-CT to Stereoscopic Video Registration,” 
Urology, vol. 73, pp. 896–900, 2009, doi: 10.1016/j.urology.2008.11.040.

[37] A. Hamacher et al., “Application of virtual, augmented, and mixed reality to 
urology,” Int. Neurourol. J., vol. 20, no. 3, pp. 172–181, 2016, doi: 
10.5213/inj.1632714.357.

[38] I. Cabrilo, P. Bijlenga, and K. Schaller, “Augmented Reality in the surgery of 
cerebral aneurysms: A technical report,” Neurosurgery, vol. 10, no. 2, pp. 252–
261, 2014, doi: 10.1227/NEU.0000000000000328.

[39] F. Volonté, N. C. Buchs, O. Ratib, and P. Morel, “Stereoscopic augmented reality 
for da Vincii robotic biliary surgery.,” Int. J. Surg. Case Rep., vol. 4, pp. 365–
367, 2013, doi: 10.1016/j.ijscr.2013.01.021.

[40] L. Soler, S. Nicolau, P. Pessaux, D. Mutter, and J. Marescaux, “Real-time 3D 
image reconstruction guidance in liver resection surgery.,” Hepatobiliary Surg. 
Nutr., vol. 3, no. 2, pp. 73–81, 2014, doi: 10.3978/j.issn.2304-3881.2014.02.03.

[41] R. M. Dickey, N. Srikishen, L. I. Lipshultz, P. E. Spiess, R. E. Carrion, and T. S. 
Hakky, “Augmented reality assisted surgery: A urologic training tool,” Asian J. 
Androl., vol. 18, no. 5, pp. 732–734, 2016, doi: 10.4103/1008-682X.166436.

[42] Microsoft Press, “El Hospital Gregorio Marañón desarrolla un proyecto pionero 
que permite hacer uso de la realidad mixta en una cirugía real,” Microsoft, 2017. 
https://news.microsoft.com/es-es/2017/10/20/el-hospital-gregorio-maranondesarrolla-un-proyecto-pionero-que-permite-hacer-uso-de-la-realidad-mixta-enuna-cirugia-real/ (accessed May 10, 2020).

[43] “CGI is helping surgeons to ‘see through’ tissue during reconstructive surgery at 
St Mary’s,” Imperial College London News, 2018. 
https://www.imperial.nhs.uk/about-us/news/cgi-in-surgery (accessed May 10, 
2020).

[44] “True 3D - A Technological Breakthrough,” echopixel website, 2020. 

[45] “MEDIVIS: Pushing the limits on what’s possible,” MEDIVIS website, 2020. 
https://www.medivis.com (accessed May 12, 2020).

[46] “Proprio: The new way of seeing,” Proprio website. 
https://www.propriovision.com/surgery (accessed May 12, 2020).

[47] “SentiAR: Transforming interventional procedures,” SentiAR website. 
https://sentiar.com (accessed May 12, 2020).

[48] “Heads up surgery TrueVision Visualization System Ophthalmology,” Leica 
mycrosystems website, 2020. https://www.leicamicrosystems.com/es/productos/microscopiosquirurgicos/detalles/product/show/Products/truevision-3d-visualization-systemophthalmology/ (accessed May 12, 2020).

[49] “ImmersiveTouch creates fully explorable 3D virtual reality models from a 
patient’s own CT and MR data,” ImmersiveTouch website. 
https://www.immersivetouch.com (accessed May 13, 2020).

[50] “Google Glasses app looks up medical records by face,” Biometric Technol. 
Today, no. 6, 2013, doi: 10.1016/s0969-4765(13)70101-2.

[51] C. H. J. Tzou et al., “Comparison of three-dimensional surface-imaging 
systems,” J. Plast. Reconstr. Aesthetic Surg., vol. 67, pp. 489–497, 2014, doi: 
10.1016/j.bjps.2014.01.003.

[52] L. Carenzo, F. L. Barra, P. L. Ingrassia, D. Colombo, A. Costa, and F. Della 
Corte, “Disaster medicine through Google Glass,” Eur. J. Emerg. Med., vol. 22, 
no. 3, pp. 222–225, 2015, doi: 10.1097/MEJ.0000000000000229.

[53] A. Follmann, M. Ohligs, N. Hochhausen, S. K. Beckers, R. Rossaint, and M. 
Czaplik, “Technical support by Smart Glasses during a mass casualty incident: A 
randomized controlled simulation trial on technically assisted triage and 
telemedical app use in disaster medicine,” J. Med. Internet Res., vol. 21, no. 1, 
2019, doi: 10.2196/11939

License Creative-Common (CC 4.0)

**Author contact**
Alba Valero
C\ Ramon Trias Fargas 25-27,
08005 Barcelona, Spain
alba.valero01@estudiant.upf.edu

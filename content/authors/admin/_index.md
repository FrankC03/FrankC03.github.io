---
# Display name
title: Cui Yifei

# Name pronunciation (optional)
name_pronunciation: 

# Full name (for SEO)
first_name: Yifei 
last_name: Cui

# Status emoji
status:
  icon: 📸

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Fourth-year Undergraduate in Electrical Engineering

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: University of Electronic Science and Technology of China 
    url: https://www.uestc.edu.cn/
  - name: University of Glasgow
    url: https://www.gla.ac.uk/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:2021190501008@std.uestc.edu.cn'
    label: E-mail Me(UESTC)
  - icon: at-symbol
    url: 'mailto:2720706c@student.gla.ac.uk'
    label: E-mail Me(UofG)
  - icon: brands/github
    url: https://github.com/FrankC03
  - icon: custom/phone-call
    label: +86 13855116835

edu:
  - area: BEng Electronic Information Engineering
    institution: |
      University of Electronic Science and Technology of China (UESTC)<br>
      Glasgow College, jointly held by the University of Glasgow
    date_start: 2021-09-01
    date_end: 2025-07-01
    summary: |
      GPA: 3.91/4.0&nbsp;&nbsp;&nbsp;&nbsp;Weighted Average: 89.87/100&nbsp;&nbsp;&nbsp;&nbsp;Ranking: 4/247(1.6%)

      Courses included:
      - Embedded Processors (99)
      - Electronic Devices (99)
      - Microelectronic Systems (99)
      - Circuit Analysis and Design (99)
      - Artificial Intelligence and Machine Learning (95)
      - Application and Design of Digital Logic (94)
  
      
research:
  - title: Neural Network based Surface Decoder for Scalable Quantum Error Correction
    position: Undergraduate Research Assistant, UESTC
    company_name: ''
    company_url: 'https://www.uestc.edu.cn/'
    company_logo: ''
    advisor:
      name: "Prof. Cheng Wang"
      url: "https://faculty.uestc.edu.cn/wangcheng/zh_CN/index/418338/list/index.htm"  # Replace with the actual URL
    date_start: 2023-08-01
    date_end: ''
    summary: |2-
      Quantum computing promises faster solutions to complex problems but is hindered by quantum noise. Surface code error correction, a leading approach for handling these errors, becomes computationally intensive for decoding as systems scale, making traditional decoders like Minimum Weight Perfect Matching (MWPM) less efficient.

      This project focuses on developing a neural network-based surface decoder to address the challenges of scalable quantum error correction. By utilizing machine learning techniques, the decoder aims to provide faster and more accurate error correction.
      
      Key responsibilities for this project include:
      - Noise Modeling and Simulation: Designed a quantum noise model covering measurement errors, data qubit idling, syndrome extraction errors, and qubit leakage. 

      - Noise Model Benchmarking: Compare our noise model against other common error models by evaluating the similarity between the error pair correlation matrices, which were derived from repetition code experiments and simulations. 
      
      - Neural Network Design: Based on the designed noise model, implement a neural network-based decoder aimed at improving upon traditional MWPM algorithm. (In Progress)
    button:
        text: Slides
        url: uploads/slides.pdf
    button2:
        text: Code (Coming soon)
        url: ''
  

# Skills
# Add your own SVG icons to `assets/media/icons/`
sks:
  - name: Technical Skills
    items:
      - name: Python
        description: ''
        percent: 80
        icon: devicon/python
      - name: Matlab
        description: ''
        percent: 60
        icon: custom/matlab
      - name: Cadence Virtuoso
        description: ''
        percent: 40
        icon: custom/ic
  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Sports
        description: ''
        percent: 100
        icon: custom/sports
      - name: Reading
        description: ''
        percent: 80
        icon: custom/book
      - name: Photography
        description: ''
        percent: 70
        icon: camera

languages:
  - name: Chinese
    percent: 100
  - name: English
    percent: 75



# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
projects:
  - title: Artificial Intelligence and Machine Learning – Computer Vision 
    img: 'icon_nus'
    url: ''
    date_start: '2022-01-01'
    date_end: '2022-02-01'
    awarder: National University of Singapore
    des: 'Instructor: Prof. Terence Sim'
    summary: |
      - Learned the principles and background of neural networks
      
      - Realized traffic sign recognition with 97% accuracy on real-world dataset, algorithm using the scikit-learn library and convolutional neural network in the python platform
    button:
        text: Download Certification
        url: uploads/Assessment report_CUI YIFEI.pdf
  - title: Intelligent Rover Design
    img: 'icon_uofg'
    date_start: '2024-02-01'
    date_end: '2024-06-01'
    awarder: UESTC, Glasgow College, Directed by UofG
    des: 'Role: Team Leader'
    summary: |
      - Completed the main program design using STM32CubeIDE, and realized the task execution and switching via polling and external environment interrupt

      - Realized visual algorithm with OpenMV and its IDE, adopted H-bridge to design the driver module PCB independently, and finished physical verification

      - Used STM32F446RE, McNamum wheel, Openmv Cam, ultrasonic module, DCDC power module, lithium battery and self-designed driven module to realize the hardware welding of the rover, and finally ensure the functions, including line patrol, direction sign and traffic light recognition, pedestrian and obstacle avoidance, wireless switch parking lever
  - title: 'Cross-coupled Cavity Filter Design'
    img: 'icon_uestc'
    date_start: '2024-02-01'
    date_end: '2024-06-01'
    awarder: UESTC, Glasgow College
    des: 'Electromagnetic Field and Microwave Technology Course Project'
    summary: |
      - Applied cross-coupling technology to increase bandwidth, enhance coupling, and provide additional attenuation

      - Determined the filter topology by simulating filter parameters with CoupleFil

      - Designed and simulated using HFSS, and adjusted iteratively according to the results until it meets the design requirements (center frequency: 1.5GHz; Bandwidth: 20MHz; Attenuation: >35dB@ (1520-1540) MHz; Insertion loss: <1dB return loss: >20dB)

awrds:
  - title: "National Scholarship (Top 4%)"
    date: "2024-11-01"
  - title: "First-class Scholarship for Outstanding Students of UESTC"
    date: "2024-10-01"
  - title: "First-class Scholarship for Outstanding Students of UESTC"
    date: "2023-10-01"
  - title: "First-class Scholarship for Outstanding Students of UESTC"
    date: "2022-10-01"
  - title: "Finalist Prize in the Mathematical Contest In Modeling & Interdisciplinary Contest In Modeling (Top 2%)"
    date: "2023-05-01"
  - title: "Academic Performance Scholarship, Glasgow College (Top 5%)"
    date: "2024-11-01"
  - title: "Academic Performance Scholarship, Glasgow College (Top 5%)"
    date: "2023-11-01"
  - title: "Academic Performance Scholarship, Glasgow College (Top 5%)"
    date: "2022-11-01"
  - title: "Watt Innovative Talent Scholarship"
    date: "2022-11-01"
  - title: "UESTC Outstanding Social Practice Individual"
    date: "2022-12-01" 

---

Electrical Engineering senior with research experience in quantum noise model design and verification under the supervision of Prof. Cheng Wang, actively pursuing a PhD position for 2025.

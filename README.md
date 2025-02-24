# 2024-205 Interactive Urban Floor Screen Installation: Dynamic Shape Adaptation to Human Interaction

Optional project of the [Streaming Data Analytics](http://emanueledellavalle.org/teaching/streaming-data-analytics-2023-24/) course provided by [Politecnico di Milano](https://www11.ceda.polimi.it/schedaincarico/schedaincarico/controller/scheda_pubblica/SchedaPublic.do?&evn_default=evento&c_classe=811164&polij_device_category=DESKTOP&__pj0=0&__pj1=d563c55e73c3035baf5b0bab2dda086b).

Student: **[To be assigned]**

## **Background**  
This project explores the intersection of urban design, interactive technology, and computer vision by creating a large, interactive floor screen that responds dynamically to human movement. For getting inspired check-out this [pinterest pin](https://kr.pinterest.com/pin/688206386830840412/). Utilizing overhead cameras, the installation detects when individuals step onto the screen, triggering a visual response that tracks their movement with geometric shapes.

## **Goals and Objectives** 
Developing a Web Application that, dynamically draws and adjust shapes around detected individuals, with the geometry changing based on the proximity and movement of people. 

Testing will involve simulating:

- Single and Multiple Interactions: Observing the system's response to individual and group movements, including the dynamic transformation of shapes.
- Complex Movement Patterns: Evaluating how well the system adapts to complex human interactions, such as merging and splitting groups.


## **Methodologies/Models to Apply** 
- Human Detection Component: implementing, using transfer learning from YOLO or other pre-trained Neural Networks, an advanced computer vision solution to accurately detect and track individuals on the screen. For a complete example, [see this repository](https://github.com/IxD-PoliMI/peopleCountingMobile)
- Stream Processing Component: Utilizing a stream processor to manage the flow of data between the cameras and the screen, ensuring real-time responsiveness to human interaction.

## **Evaluation Metrics:** 
- **Accuracy** of human detection and tracking.
- **Latency** of shape adaptation and movement on the screen.

##  **Deliverable**  
A report detailing the methodology, implemented code, and an evaluation of model performance.  

## Note for Students

* Clone the created repository offline;
* Add your name and surname into the Readme file;
* Make any changes to your repository, according to the specific assignment;
* Add a `requirement.txt` file for code reproducibility and instructions on how to replicate the results;
* Commit your changes to your local repository;
* Push your changes to your online repository.

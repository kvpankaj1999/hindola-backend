# hindola-backend
Backend system for managing DB and front-end in HInDoLA
This Annotation App is to manage the manuscripts annotations through an interactive GUI. Implemented in Flask, the App has useful features to annotate images from large manuscripts libraries.

### Prerequisites
Stated in requirements.txt in App folder

### To run on local system
1. Download the Repo and install the prerequisites
2. Go to the App folder, locate app.py
3. Run - ```python3 app.py ```

### Annotations
1. Open the page at the started local server
2. Sign-up and login
3. Request image through "Request" Button
4. Annotate with the regions provided - Freehand(single click to start and double click to finish), Polygon(Single click     to start, each click adds new vertex and double click to finish)
5. "Done" button to save the annotations, "Skip" button to skip the image 

### Database Handling
1. File - ```hindola-backend/Annotation_App/myproject/data.sqlite``` contains all information of tables used.

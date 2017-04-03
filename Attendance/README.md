# Attendance
The algorithm of this application records the attendance of the employees or students in a facility using data extracted from their faces and comparing it to an existing database of employees faces. 

The standard database used for face recognition was collected from [AT&T Laboratories Cambridge](http://www.cl.cam.ac.uk/research/dtg/attarchive/facedatabase.html "title"). The database contains a set of 40 distinct faces with 10 different images. The images were taken at different times, changing lighting slightly, various facial expressions and details. The size of each image is 92x112, 8-bit grey levels.

![Alt text](https://github.com/MhAlghamdi/FaceRecognition/blob/master/Attendance/Images/faces.gif "Optional title")

New employees can be added to the database and recorded easily through `Main.fig` interface. Webcam name most be inculded in `Main.m` to add persons to a database by taking 10 snapshots for each person at slightly different lighting conditions and different facial expressions then comparing them with the database. The GUI in the MATLAB was used to facilitate the input process of the images.

![Alt text](https://github.com/MhAlghamdi/FaceRecognition/blob/master/Attendance/Images/main.png "Main interface")

## References
1. Ali, H. B., & Powers, D. M. (2015). Face and Facial Expression Recognition - Fusion based Non Negative Matrix Factorization.Proceedings of the International Conference on Agents and Arti cial Intelligence.
2. Alam, Naveed et al. "Face Recognition Using Non-Negative Matrix Factorization (NMF) An Analysis Of Order Of Decomposition On Recognition Rate". Research Journal of Recent Sciences 4(4).2277-2502 (2015): n. pag. Print.

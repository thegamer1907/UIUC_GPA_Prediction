# UIUC_GPA_Prediction
Team Members:
Mukesh Naresh Chugani
Harshit Agarwal
Kshitij Phulare
Jonathan David Adamic

Problem:
The given dataset has the following features:
Year, Term, Subject, Number, Course Title, Sched Type, Grades (A+,...F / W), Primary instructor
From a bird’s eye view, the dataset contains the grade distributions of numerous courses taught by various instructors over a period of 12 years i.e. 2010 - 2021 at UIUC. This data can be leveraged to predict the future mean GPA for an upcoming term, given a (course, instructor) pair which may or may not be present in the dataset. As a further step, the future grade distribution could be predicted along with the mean GPA. Deep learning can also facilitate the study of GPA/Grade trends of a course/instructor over a span of multiple years.


Data Files:
uiuc-gpa-dataset.csv - Raw dataset
working_dataset.pkl - Pickled full dataset
debugging_dataset.pkl - Pickled partial dataset
X_Final.pkl - Pickled Preprocessed Input Data (Feed directly to network after splitting)
Y_Final.pkl - Pickled Corresponding Output Labels for X_Final.pkl

Notebooks:
G11 GPA_Milestone1.ipynb - Basic data formatting and pickling.
G11 GPA_Milestone2.ipynb - Contains basic data preprocessing and linear regression baseline.
G11 GPA_Milestone3.ipynb - Training, Validation, Testing separation and preprocessing. 2 Layer NN. Exploration of different optimizers, hyperparamters, and loss functions. (With Visualizations)
AdditionalExporation.ipynb - Construction of 6 Layer NN and exploration of optimizers, hyperparameters, and loss functions. (NO VISUALIZATIONS)



Full Project Definition: 

UIUC GPA

Dataset on UIUC GPA is available at
https://github.com/wadefagen/datasets/tree/master/gpa (“uiuc-gpa-dataset.csv”)

Most UIUC students are acquainted with Professor Ulmschneider’s historical grade distribution visualization tool. It can be very useful for determining which courses one wants to take. However, calling on historical data, is it possible to instead predict the GPA/grade distribution of UIUC courses in the future? This may be of relevance to those looking to hire new faculty for certain classes, faculty looking to change the structure of their course, and students looking to register early for or avoid altogether certain courses.

Label(s)
●	Overall GPA (Per Class/Class section)

Features:
●	Term (Given Data)
●	Year (Given Data)
●	Student pop. per class (Given Data)
●	Subject / Department (One-Hot) (Given Data)
●	Number (Given Data)
●	Grade (Each Column, “F” through “A+”) (Given Data)
●	Course Title (One-Hot) (Given Data)
●	Primary Instructor (One-Hot) (Given Data)

Project Curated by Jared Canty (Summer 2022 Blackwell Program)








MIT License

Copyright (c) [2022]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
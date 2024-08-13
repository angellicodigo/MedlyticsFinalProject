# Medlytics Final Project
For the final project of MIT Beaver Works Summer Institute course "Medlytics", we created a program that detected dyslexia through images of handwriting. This is useful for kindergarten teachers to scan images of students' worksheets and detect early signs of dyslexia. This project includes data argumentation and multiple ML models.

## Dataset
Images of handwriting into three categories: correct handwriting, normal hand writing, and reversal hadnwriting. Research shows that kids writing in reverse can be signs of dyslexia. 
https://www.kaggle.com/datasets/drizasazanitaisa/dyslexia-handwriting-dataset

![The dataset we used](https://github.com/angellicodigo/MedlyticsFinalProject/blob/main/Dataset.png)

## Presentation
Our dataset was undersampled, so we had equal number of images per category. We found that using transfer learning, the **VGG16 model** did the best with a **training accuracy of 0.879** and **validation accuracy of 0.894**. We hope to furter our research by collaborating with dyslexia centers to learn more about what they need and focusing on analyzing the spacing betwee letters in a word, rather than only focusing on the letters.

Here is a demonstration of a web browser using our model: https://youtu.be/qL-5fYlXstY?si=FSp3tmuLiK1hn19o

# COVID_Radiography_Final_Capstone

Can I use transfer learning to create a model to classify chest x-rays with 85% accuracy in the next 4 weeks?

Context <br>
It is estimated that 3.6 billion diagnostic x-ray examinations are performed every year in the world(1). The chest x-ray is the most performed diagnostic x-ray examination. A chest x-ray produces images of the heart, lungs, airways, blood vessels and the bones of the spine and chest. A chest x-ray is typically the first imaging test used to help diagnose symptoms such as:
•	breathing difficulties
•	a bad or persistent cough
•	chest pain or injury
•	fever(2)
Radiologists’ accuracy varies depending on what condition is being diagnosed. For example, pneumonia is accurately diagnosed from a chest x-ray around 85% of the time. Studies have also shown that there is disagreement in the interpretation of x-rays in up to 56% of cases(3).
With so much manpower being used to assess x-rays, around the world, each year, it would be beneficial to use a machine learning model to do the initial assessment and flag which x-rays have abnormalities. 

Criteria for success <br>
By July 11th 2021, the model will accurately classify at least 85% of the chest x-rays into 4 categories: COVID, viral pneumonia, lung infection (non-COVID), and normal. 
Scope of solution space 
The only diagnoses that will be considered by the model are related to problems in the lungs and they are: COVID, viral pneumonia, lung infection (non-COVID), and normal. Models could be trained to diagnose more problems from chest x-rays (like heart problems) but I will not be pulling images to do so.

Constraints <br>
The set of images were labeled using a combination of human labeling and natural language processing. The accuracy of the labels is most likely not 100% but will need to be taken as truth.
Stakeholders 
Medical care teams around the world.

Data sources <br>
The data set was taken from Kaggle – https://www.kaggle.com/tawsifurrahman/covid19-radiography-database – which was compiled from many different sets of data that can be viewed in the following links:
Kaggle References:
-M.E.H. Chowdhury, T. Rahman, A. Khandakar, R. Mazhar, M.A. Kadir, Z.B. Mahbub, K.R. Islam, M.S. Khan, A. Iqbal, N. Al-Emadi, M.B.I. Reaz, M. T. Islam, “Can AI help in screening Viral and COVID-19 pneumonia?” IEEE Access, Vol. 8, 2020, pp. 132665 - 132676.
-Rahman, T., Khandakar, A., Qiblawey, Y., Tahir, A., Kiranyaz, S., Kashem, S.B.A., Islam, M.T., Maadeed, S.A., Zughaier, S.M., Khan, M.S. and Chowdhury, M.E., 2020. Exploring the Effect of Image Enhancement Techniques on COVID-19 Detection using Chest X-ray Images. arXiv preprint arXiv:2012.02238. <br>
**Data Sources: <br>
[1]https://bimcv.cipf.es/bimcv-projects/bimcv-covid19/#1590858128006-9e640421-6711
[2]https://github.com/ml-workgroup/covid-19-image-repository/tree/master/png
[3]https://sirm.org/category/senza-categoria/covid-19/
[4]https://eurorad.org
[5]https://github.com/ieee8023/covid-chestxray-dataset
[6]https://figshare.com/articles/COVID-19_Chest_X-Ray_Image_Repository/12580328
[7]https://github.com/armiro/COVID-CXNet
[8]https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/data
[9] https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia


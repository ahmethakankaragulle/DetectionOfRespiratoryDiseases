# DetectionOfRespiratoryDiseases

The developed model is a Convolutional Neural Network (CNN) using Keras and Tensorflow infrastructure. Four Conv2D
A sequential model with a simple model architecture consisting of a convolutional layer was used.
The activation function used for the convolutional layers is ReLU. In the convolutional layers
a small Dropout value was used.
Each convolutional layer has an associated pooling layer of type MaxPooling2D and the last
The convolutional layer has the type GlobalAveragePooling2D. Pooling layers are used to
to shorten, reduce over-fitting and reduce the dimensionality of the model

*******

Geliştirilen model Keras ve Tensorflow altyapısını kullanan bir Evrişimsel Sinir Ağı (CNN). Dört Conv2D
konvolüsyonel katmanından oluşan basit bir model mimarisine sahip ardışık bir model kullanıldı.
Konvolüsyonel katmanlar için kullanılan aktivasyon fonksiyonu ReLU'dur. Evrişimsel katmanlarda %20'lik
küçük bir Dropout değeri kullanıldı.
Her bir evrişimsel katman, MaxPooling2D tipinde ilişkili bir havuzlama katmanına sahiptir ve son
evrişimsel katman GlobalAveragePooling2D tipine sahiptir. Havuzlama katmanları, eğitim süresini
kısaltmak, aşırı uyumu azaltmak ve modelin boyutluluğunu azaltmak içindir.

********

Dataset : https://www.kaggle.com/datasets/vbookshelf/respiratory-sound-database

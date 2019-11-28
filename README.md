# Face Recognition
Face recognition falls into 2 categories:
Face verification -
check if the person is the correct one (passport verification at the airport)
It is one-to-one mapping
Face Identification –
Who is the person? 
It is one-to-many mapping

Transfer Learning – 2 types of transfer learning:
Via Fine tuning
Replace a trained neural network’s fully connected layer head and then train
Need large amount of data compared to feature extraction
Via  feature extraction (best suited for face recognition)
Pre-trained neural network serves as a feature extractor
Allow the input to propagate forward and taking the output from specific layer

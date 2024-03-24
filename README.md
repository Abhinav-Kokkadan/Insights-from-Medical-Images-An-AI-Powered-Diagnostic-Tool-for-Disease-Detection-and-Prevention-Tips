# Insights-from-Medical-Images-An-AI-Powered-Diagnostic-Tool-for-Disease-Detection-and-Prevention-Tips
A tool which uses Image detection Model which gives high accuracy around 80% and classifies the three diseases(Parkinson, Alzheimer's , Diabetic Retinopathy) which uses MRI scans and Retinal Images as Input and after Classification the ouptut will show the detected disease, if any along with insights and prevention tips on real time using ChatGPT.

using vgg16, resnet50 and efficientB0, made a ensemble model but upon comparing with the latest approch, feature fusion(vgg16, resnet), it showed similar accuracy around 82%. Used 20 epoch as resources were limited. Used only the features which gives best out of a model and combined it. 80:20, training to testing ratio. 

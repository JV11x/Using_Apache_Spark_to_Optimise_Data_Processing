# Augmenting image processing task in TensorFlow with Apache Spark 

The project presents a means of augementing several image process steps using Apache Spark.
The projecct considers:
  - The optimium number of spark partitions for the workload.
  - The best compute configuration for the Dataproc cluster to achieve the fastsest results of the task.
  - Analysis of key varriable and how they impact resulting outputs 'batch size' 'dataset_size' 'program repetitions', and experiment repitions, impact the 'images per second' read speed. 

This project uses GCP services Dataproc and Colab.

The full code can be found in the following link: https://drive.google.com/file/d/1pT7TLdvCHU_vipxJ2LvYLywIf0rYTupT/view?usp=sharing 

Figure 1: Analysis of preprocessed Tfrecord files
![image](https://github.com/JV11x/Using_Apache_Spark_to_Optimise_Data_Processing/assets/114994769/a030faa9-9649-41cc-904d-755e9e0dbb9f)

Figure 2: Analysis of unprocessed images
![image](https://github.com/JV11x/Using_Apache_Spark_to_Optimise_Data_Processing/assets/114994769/50507490-7709-4286-b9ab-ef7e8eb933d1)

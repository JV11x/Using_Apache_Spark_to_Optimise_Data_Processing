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
![image](https://github.com/JV11x/Using_Apache_Spark_to_Optimise_Data_Processing/assets/114994769/ad30bbf2-c2b0-4d99-ad66-cec514fa976b)
![image](https://github.com/JV11x/Using_Apache_Spark_to_Optimise_Data_Processing/assets/114994769/38ef0a7f-23ba-47a5-8bb5-1968d549916b)
![image](https://github.com/JV11x/Using_Apache_Spark_to_Optimise_Data_Processing/assets/114994769/b7c878e6-0165-47fb-a946-7bf4d622cc1a)


Figure 2: Analysis of unprocessed images

![image](https://github.com/JV11x/Using_Apache_Spark_to_Optimise_Data_Processing/assets/114994769/50507490-7709-4286-b9ab-ef7e8eb933d1)
![image](https://github.com/JV11x/Using_Apache_Spark_to_Optimise_Data_Processing/assets/114994769/c9615a22-35d9-4be0-a4cc-2d17d9ae0e06)
![image](https://github.com/JV11x/Using_Apache_Spark_to_Optimise_Data_Processing/assets/114994769/6663f845-87e7-4260-8e8a-e7a14630e1a8)
![image](https://github.com/JV11x/Using_Apache_Spark_to_Optimise_Data_Processing/assets/114994769/955bef2c-c447-4eb8-9a9b-a0bab145b5fa)

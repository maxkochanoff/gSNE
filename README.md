# gSNE
gSNE is an extended version of the tSNE algorithm, offering enhanced capabilities for dimensionality reduction. The purpose of creating gSNE is to solve the crowding problem of the tSNE. This problem is relevant because the task of visualizing high-dimensional data is a crucial step in the preliminary analysis of almost any machine learning task.

It was my course project in the Master's program at Novosibirsk State University in 2022. The project necessitated a comprehensive examination of data visualization techniques, involving the exploration of a novel approach that extends the t-SNE method. This extension replaced the Student's distribution with a Generalized Normal Distribution and trained the distribution parameters using the t-SNE loss function for optimization. gSNE can effectively reduce the dimensionality of data while preserving its essential features.

The obtained results were presented at 60th International Student Scientific Conference ISSC-2022 and were awarded a first-degree diploma.

Info about ISSC-2022: https://conf.nsu.ru/en/issc_2022



MNIST gNSE projection:
![photo_2023-11-12_11-53-28](https://github.com/maxkochanoff/gSNE/assets/122701199/678a8b7e-2d77-4bf4-8407-05ffceaa0535)

# LiDAR-Image-Learning
Deprivation, or the “the damaging lack of material benefits considered to be basic necessities in a
society”, is a major concern in modern societies. While many times confused with poverty, in reality,
it is a complex, multidimensional, social phenomenon that can severely impact the quality of life of
those who are deprived. For banking, Financial Inclusion, or the area of finance focused on giving
access to financial services to those who, mostly due to being deprived in different areas, is a key
focus of modern regulatory efforts. In this project, we will use our knowledge of deep learning
to better understand how living conditions in an area, as shown by LIDAR images, can impact
deprivation indexes. The seven deprivation indexes that are commonly measured for a geographical
area are:
• Income: Measures the proportion of the population experiencing deprivation relating to low
income.
• Employment: Measures the proportion of the working-age population in an area
involuntarily excluded from the labour market.
• Education: Measures the lack of attainment and skills in the local population.
• Health: Measures the risk of premature death and the impairment of quality of life through
poor physical or mental health.
• Crime: Measures the risk of personal and material victimization at the local level.
• Barriers to Housing: Measures the physical and financial accessibility of housing and local
services.
• Living Environment: Measures the quality of both the indoor and outdoor local
environment.
On the other hand, LiDAR1
is a technology that uses laser pulses to create 3D and elevations
renderings of objects and terrains, similar to how radar technology uses sound. Due to its low cost
and efficiency in representing elevations, several governments around the world have collected this
data and made it freely available for their citizens to use. As an interesting source of unstructured
data, in this coursework, we will explore its societal use to predict multidimensional deprivation. In
particular, the UK government has made available both borough-level data regarding
multidimensional deprivation and accurate elevation data at 1m spatial resolution for all of England.
You are given a dataset composed of the geographic information of a specific area covering parts of
London, UK. There are two parts of the data: images of the neighbourhood (unstructured data) and
embedding data, which contains the geographic information of each neighbourhood (structured
data). For the embedding data, please refer to the data description file. As for the image data, please
note that the format of the image name is “‘LIDAR’+’ID’+.’png’”. Under this format, you can connect
the image with specific geographic information contained in the embedding data.

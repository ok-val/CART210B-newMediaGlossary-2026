## Latent Space

![Virtual environment](/images/latentspace.png)

Latent space is a multidimensional numerical space used for efficiently storing and modeling data, essentially functioning as a map for data points. It uses a mathematical framework of vectors to represent data such as images, text, or measurements by reducing them to smaller, abstract points[^larson]. The AI model organizes this data into categories represented by vectors that are correlated with each other. For example, in image generation, generative AI breaks down an image into latent vectors capturing factors like age, race, hairstyle, and emotional expression numerically.
Generation is done through encoding and decoding data. First, models encode the data by capturing essential information in points while discarding less relevant details. This reduction in size increases the efficiency of the model. The model can then decode this information back into the original domain. Different points can be related to each other by moving along specific directions in the latent space, such as aging a face or changing an emotion while preserving other aspects of the data[^drapala]. 


Latent space is significant in new media because it allows AI to efficiently generate highly realistic images, text, and other outputs as abstract representations instead of relying solely on raw data. It provides a framework for creators and software to explore different concepts and personalize content in ways that were previously impossible or computationally demanding. By capturing the essential characteristics of data, latent space transforms how humans interact with machines[^drapala]. 


Generative AI relies on latent spaces, enabling AI art, storytelling, and interactive media to be customized and personalized according to various parameters. However, this method of grouping data can amplify biases and stereotypes. The data is often organized based on what is commonly available, which can reinforce existing social biases related to race, gender, and social roles. For example, a vector representing wealth may primarily map to white representations of elites. Asking AI to generate an image of a wealthy woman may combine latent vectors for wealth and woman, which could also map to whiteness, subservience, and marriage vectors, affecting the tone and content of the generated image or story[^sivalingam]. 


[^drapala]: Drapala, Jaroslaw. What is a latent space?. A concise explanation for the general… | by Jaroslaw Drapala | TDS archive | medium. Accessed February 22, 2026. https://medium.com/data-science/what-is-a-latent-space-065eb8e3f859.
[^larson]: Jacob Larson, James S. Denford, Niam Yaraghi, Nicol Turner Lee Regina Ta, Kennedy Satterfield Morgan Gray, and Aylin Caliskan Kyra Wilson. “Rendering Misrepresentation: Diversity Failures in AI Image Generation.” Brookings, April 18, 2024. https://www.brookings.edu/articles/rendering-misrepresentation-diversity-failures-in-ai-image-generation/.
[^sivalingam]: Sivalingam, Ampatishan. “Latent Space: The Most Important Place That Doesn’t Exist | by Ampatishan Sivalingam | Feb, 2026 | towards Ai.” Medium, February 16, 2026. https://pub.towardsai.net/latent-space-the-most-important-place-that-doesnt-exist-643a6497c208. 


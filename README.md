# Fire-Scene-Parsing
We introduce a novel application of using scene/ semantic image segmentation for emergency situation analysis. During an emergency state, it is imperative to analyse the situation thoroughly before planning a response. To analyse a fire emergency scene, we propose to identify and classify objects in a scene based on their build material and their vulnerability to catch fire. In this way, the direction of fire spread can be roughly determined. We also segment people and other living beings and fire, obviously. 

The dataset consists of 2065 images which are annotated on the basis of object material, fire and living beings. The fire emergency scene parsing dataset consists of nine categories (+1 for background), which are: Wood, Plastic, Cloth, Plants, Stone, Fire, Smoke, Person, Other.

To the best of our knowledge, this is the first scene parsing or segmentation dataset that is based on emergency analysis and segmenting objects based on build material. The dataset is imbalanced as the number of instances of each class vary a lot. Keeping this in mind, the frequency weighted mean intersection over union must also be calculated.

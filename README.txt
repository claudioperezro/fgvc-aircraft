About the data¶
This project used the Fine-Grained Visual Classification of Aircraft (FGVC-Aircraft) dataset. This dataset contains thousands of pictures of different aircraft models in different settings. This extensively labeled dataset was made possible by a number of airplane spotters for non-commercial research purposes only.

This dataset contains a total of 10,000 images of aircraft and is split in the following way:

3334 Training Images
3333 Validation Images
3333 Testing Images
The interesting thing about this Dataset is that it includes txt files containing different hierarchical levels of airplane labels. There are three levels in the hierarchy, organized from finer to coarser in the following way:

Variant: e.g. Boeing 737 - 700. As per the dataset page: “A variant collapses all the models that are visually indistinguishable into one class. The dataset comprises 102 different variants.”
Family: e.g Boeing 737. For example, all of the 737 variants (737-200, 737-300) would be grouped into the same family. The dataset comprises 70 different variants.
Manufacturer e.g. Boeing. The dataset comprises 41 different manufacturers.
This dataset was used as a part of the fine-grained recognition challenge “FGComp2013” and is considered a benchmark for FGVC.

Aircraft is one of the most interesting case uses in FGVC for many reasons. First, aircraft have been around for more than 100 years. In this span, aircraft design has evolved vastly, from structural changes to propulsion. All of these differences in propulsion, wing configuration, livery and purpose(Civil, Military) provide a very different range of challenges than the typical Fined Grained Classification subjects like cats or birds.

About to Fined Grained Classifiers
This project explores fine-grained classification, i.e. classification among categories which are are both visually and semantically very similar. This is a very difficult regime which is even challenging for humans without careful training, and is critical for establishing a more detailed understanding of the visual world.

Importance
Fined grained classification is a very exciting task, but it doesn't stop there. Identifying different subclasses of airplane might be extremely useful in a diverse range of environments.
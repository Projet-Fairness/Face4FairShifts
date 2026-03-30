---
license: afl-3.0
task_categories:
- feature-extraction
language:
- en
tags:
- code
pretty_name: LYM619/Face4FairShifts
size_categories:
- 10K<n<100K
---

# Face4FairShifts: A Large Image Benchmark for Fairness and Robust Learning across Visual Domains

By Tianjin University

For more information about the dataset, visit the project website:

  https://meviuslab.github.io/Face4FairShifts/

Please note that the use of this dataset is RESTRICTED to non-commercial research and educational purposes.


## File Information

- Face Images (Img/)
    100,000 original face images across four domains: 30,000 in Photo, 25,000 each in Art and Cartoon, and 20,000 in Sketch. See Face Images section below for more info.

- Attributes Annotations (Anno/)
    42 annotations within 15 attributes Encompassing sensitive attributes related to fairness, such as gender, race, and age, as well as detailed facial attributes including beard, glasses, eyes, mouth, smile, nose, chin, hair, braids, accessories, and others, along with subjective traits like attractiveness. See Attributes Annotations section below for more info.


## Face Images

- Photo.zip
- Art.zip
- Cartoon.zip
- Sketch.zip

Notes:
1. Please unzip these files together.



## Attributes Annotations

- photo_attr.json
- art_attr.json
- cartoon_attr.json
- sketch_attr.json

format:     
    {
        "id":c00102,
        "gender":2,
        "Asian":1,
        "Black":2,
        "Others":2,
        "teenager":1,
        "middle":2,
        "elderly":2,
        "wrinkles":2,
        "sideburns":2,
        "mouthtache/goatee":2,
        "beard":2,
        "clear_glasses":2,
        "sunglasses":2,
        "glasses":2,
        "open_eyes":1,
        "eyebrows":1,
        "open_mouth":1,
        "show_teeth":1,
        "smile_with_closed_lips":2,
        "smile_with_open_lips":1,
        "show_ears":1,
        "earring":2,
        "pointed_nose":2,
        "round_nose":2,
        "pointed_chin":1,
        "round_chin":2,
        "bald":2,
        "sparse_hair":2,
        "short_hair":2,
        "long_hair":1,
        "straight_hair":2,
        "curly_hair":1,
        "bangs":1,
        "one_braid":2,
        "≥2_braids":1,
        "braids":1,
        "hair_wear":1,
        "hat":2
        "appearance":1	 
    }


Notes:
1. For the "gender" attribute,  "1" represents male while "2" represents female.
2. For the "appearance" attribute,  "1" represents attractive, "2" represents average, and "3" represents unattractive.
3. For all other attributes, "1" represents positive, while "2" represents negative.



## Attributes Description

- Gender: This attribute includes male and female.
- Race: Race is divided into Asian, Black, and Others. The main criterion for determining race is appearance, specifically facial features, not hair color, skin color, or eye color, and certainly not based on the brightness or darkness of the image.
- Age: Age is diveded into teenager, middle and elderly. Teenagers include both young adults and children, covering all young age groups.
- Wrinkles: Wrinkles are closely related to age. If the image only shows nasolabial folds, it does not count as having wrinkles. Only when there are numerous wrinkles overall can it be considered as having wrinkles.
- Sideburns: Beard connecting the sides of the cheeks to the mouth is referred to as a sideburn beard.
- Moustache/goatee: Van dyke refers to facial hair located only above or below the lips.
- Beard: Beard includes both sideburns and van dykes.
- Clear_glasses: Colorless transparent lens.
- Sunglasses: Colored lens.
- Glasses: Glasses include clear glasses and sunglasses.
- Open_eyes: Open at least one eye.
- Eyebrows: The person's at least one eyebrow is visible.
- Open_mouth: The mouth is open.
- Show_teeth: The person's teeth are visible.
- Smile_with_closed_lips: This attribute represents a smile with a closed mouth.
- Smile_with_open_lips: This attribute represents a smile with an open mouth.
- Show_ears: The person's at least ear is visible.
- Earring: This attribute indicates that there are accessories on the ears.
- Pointed_nose: A pointed nose refers to a nose with a distinct tip that is relatively small and delicate.
- Round_nose: A round nose refers to a nose with no distinct tip, and it appears more rounded and fleshy.
- Pointed_chin: A pointed chin is a chin that is sharp and tapered, with a narrow, defined tip.
- Round_chin: A round chin is a chin that is smooth and curved, lacking sharp angles, with a soft, rounded shape at the tip. 
- Bald: Not a single hair on the head.
- Sparse_hair: Hair is rather sparse.
- Short_hair: The hair length does not exceed the chin.
- Long_hair: The hair length is below the chin.
- Straight_hair: The hair is straight.
- Curly_hair: The hair is curly.
- Bangs: The person in the image has bangs.
- One_braid: The person in the image has a braid.
- ≥2_braids: The person in the image has more than two braids.
- Braids: The person in the image has braids, regardless of the number. This attribute includes one braid and ≥2 braids.
- Hari_wear: All head accessories excluding hats.
- Hat: A headscarf is also considered a hat. It can cover part or all of the head.
- Appearance: A subjective annotation including attractive, average, and unattractive.


## Contact

Please contact Yumeng Lin (lym619@tju.edu.cn) for questions about the dataset.
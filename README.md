# 🌿 Plant Species Image Classification
### Using Google Teachable Machine — Aloe Species Edition

---

## A. Project Overview

This project presents an image classification model trained to identify **20 distinct Aloe species** using [Google Teachable Machine](https://teachablemachine.withgoogle.com/). Aloe plants belong to the family *Asphodelaceae* and are widely recognized for their ornamental beauty, medicinal properties, and ecological diversity. Despite their shared genus, individual Aloe species differ significantly in leaf shape, color, rosette pattern, size, and texture — making them an ideal and challenging subject for machine learning classification.

### Purpose
The primary goal of this model is to:
- Accurately distinguish between 20 visually similar Aloe species from image input
- Demonstrate how machine learning can be applied to botanical identification
- Provide a foundation for plant recognition tools useful in horticulture, conservation, and education

The model was trained on a dataset of **5,000+ images** (minimum 250 per species), covering varied angles, lighting conditions, and growth stages to ensure robust generalization.

---

## B. Plant Species

Below are the 20 Aloe species used in this classification project, each with a representative image and brief description.

---

### 1. Aloe AJR
![Aloe AJR](images/aloe_ajr.jpg)

| | |
|---|---|
| **Common Name** | Aloe AJR |
| **Scientific Name** | *Aloe* 'AJR' (Hybrid Cultivar) |

**Description:** Aloe AJR is a hybrid cultivar known for its compact rosette form and striking leaf patterning. The leaves are typically medium green with white spots or markings, and have serrated edges with soft teeth. It is a popular ornamental plant in succulent collections due to its manageable size and attractive appearance.

---

### 2. Aloe Arborescens
![Aloe Arborescens](images/aloe_arborescens.jpg)

| | |
|---|---|
| **Common Name** | Krantz Aloe / Candelabra Aloe |
| **Scientific Name** | *Aloe arborescens* Mill. |

**Description:** One of the most well-known and widely cultivated Aloe species, Aloe arborescens grows as a large, multi-stemmed shrub reaching up to 3 meters tall. It produces vivid red-orange tubular flowers in winter and is extensively used in traditional medicine, particularly in South Africa and Japan. Its succulent blue-green leaves are long, tapering, and armed with sharp marginal teeth.

---

### 3. Aloe Aristata
![Aloe Aristata](images/aloe_aristata.jpg)

| | |
|---|---|
| **Common Name** | Lace Aloe / Torch Plant |
| **Scientific Name** | *Aloe aristata* Haw. |

**Description:** Aloe aristata is a small, stemless succulent forming dense rosettes of dark green leaves covered in white tubercles and soft white spines, including a terminal bristle (arista) at the leaf tip. It thrives in cooler climates compared to most aloes and produces orange-red tubular flowers. A popular houseplant due to its compact size and ease of care.

---

### 4. Aloe Blizzard
![Aloe Blizzard](images/aloe_blizzard.jpg)

| | |
|---|---|
| **Common Name** | Aloe Blizzard |
| **Scientific Name** | *Aloe* 'Blizzard' (Hybrid Cultivar) |

**Description:** Aloe Blizzard is a hybrid cultivar prized for its heavily spotted and streaked leaves, which are covered in an abundance of white or cream-colored spots against a green base — giving it a "blizzard" appearance. It forms neat rosettes and is a low-maintenance ornamental plant suitable for containers and rock gardens.

---

### 5. Aloe Blue Boy
![Aloe Blue Boy](images/aloe_blue_boy.jpg)

| | |
|---|---|
| **Common Name** | Blue Boy Aloe |
| **Scientific Name** | *Aloe* 'Blue Boy' (Hybrid Cultivar) |

**Description:** Aloe Blue Boy is a hybrid cultivar distinguished by its distinctive blue-grey to silver-green foliage, which gives it a cool, silvery appearance unlike typical green aloes. The leaves form a compact rosette with finely toothed margins. It is widely used in ornamental landscaping for its unique color and drought tolerance.

---

### 6. Aloe Blue Elf
![Aloe Blue Elf](images/aloe_blue_elf.jpg)

| | |
|---|---|
| **Common Name** | Blue Elf Aloe |
| **Scientific Name** | *Aloe* 'Blue Elf' (Hybrid Cultivar) |

**Description:** A compact hybrid aloe, Blue Elf features narrow, upright blue-green leaves with orange-toothed margins. It is known for its prolific production of coral-orange flowers on tall stalks, blooming repeatedly throughout the year in warm climates. Widely popular in California and Mediterranean-climate gardens, it is highly drought-tolerant and attracts hummingbirds.

---

### 7. Aloe Brevifolia
![Aloe Brevifolia](images/aloe_brevifolia.jpg)

| | |
|---|---|
| **Common Name** | Short-leaved Aloe / Crocodile Aloe |
| **Scientific Name** | *Aloe brevifolia* Mill. |

**Description:** Native to the Western Cape of South Africa, Aloe brevifolia is a small clustering succulent with short, broad, blue-green leaves arranged in tight rosettes. The leaves have white marginal teeth and often develop reddish tones under stress. It produces red-orange flowers on branching stalks and is valued as a ground cover or container plant.

---

### 8. Aloe Broomii
![Aloe Broomii](images/aloe_broomii.jpg)

| | |
|---|---|
| **Common Name** | Mountain Aloe / Snake Aloe |
| **Scientific Name** | *Aloe broomii* Schönland |

**Description:** Aloe broomii is a striking, solitary aloe native to the rocky mountain slopes of South Africa and Lesotho. It is recognized by its dense rosette of broad, grayish-green leaves with distinctive brown-tipped teeth along the margins. The flower spike is unusual — tall and densely packed with pale yellow to white flowers enclosed in long reddish bracts.

---

### 9. Aloe Castillonaie
![Aloe Castillonaie](images/aloe_castillonaie.jpg)

| | |
|---|---|
| **Common Name** | Aloe Castillonaie |
| **Scientific Name** | *Aloe castillonaie* |

**Description:** Aloe castillonaie is a lesser-known species characterized by its rosette of green to grey-green succulent leaves with serrated margins. Like many aloes, it is adapted to arid and semi-arid environments and is cultivated primarily by succulent enthusiasts and collectors for its distinctive form and hardiness.

---

### 10. Aloe Dial Lights
![Aloe Dial Lights](images/aloe_dial_lights.jpg)

| | |
|---|---|
| **Common Name** | Dial Lights Aloe |
| **Scientific Name** | *Aloe* 'Dial Lights' (Hybrid Cultivar) |

**Description:** Aloe Dial Lights is an eye-catching hybrid cultivar featuring leaves with striking color variations, often displaying shades of red, orange, and green depending on sun exposure and stress. The rosette form and vibrant coloration make it a sought-after ornamental plant for gardens and containers. It is tolerant of heat and drought once established.

---

### 11. Aloe Jurassic Dino
![Aloe Jurassic Dino](images/aloe_jurassic_dino.jpg)

| | |
|---|---|
| **Common Name** | Jurassic Dino Aloe |
| **Scientific Name** | *Aloe* 'Jurassic Dino' (Hybrid Cultivar) |

**Description:** Aloe Jurassic Dino is a bold hybrid cultivar with thick, rugged leaves reminiscent of prehistoric textures. The leaves typically feature prominent ridges, bumps, or warty protrusions with contrasting colors, giving the plant a dinosaur-like appearance. It is a novelty plant popular among collectors and is well-suited to container gardening.

---

### 12. Aloe Krakatoa
![Aloe Krakatoa](images/aloe_krakatoa.jpg)

| | |
|---|---|
| **Common Name** | Krakatoa Aloe |
| **Scientific Name** | *Aloe* 'Krakatoa' (Hybrid Cultivar) |

**Description:** Named after the famous Indonesian volcano, Aloe Krakatoa is a hybrid cultivar known for its intensely red-orange leaves and fiery flower spikes. The dramatic coloration — which intensifies with bright sunlight — makes it a standout ornamental plant. It is compact, drought-resistant, and ideal for rockeries and low-water landscaping.

---

### 13. Aloe Krohniana
![Aloe Krohniana](images/aloe_krohniana.jpg)

| | |
|---|---|
| **Common Name** | Aloe Krohniana |
| **Scientific Name** | *Aloe krohniana* |

**Description:** Aloe krohniana is a rare and distinctive species known for its highly unusual leaf texture and markings. The leaves are often adorned with intricate patterns of spots or stripes, making each plant visually unique. It is primarily of interest to succulent collectors and botanical gardens due to its scarcity and ornamental appeal.

---

### 14. Aloe Nobilis
![Aloe Nobilis](images/aloe_nobilis.jpg)

| | |
|---|---|
| **Common Name** | Gold-tooth Aloe / Noble Aloe |
| **Scientific Name** | *Aloe nobilis* Haw. |

**Description:** Aloe nobilis is a clustering succulent native to South Africa, forming dense colonies of rosettes with narrow, dark green leaves edged with distinctive yellow-white teeth — hence the common name "Gold-tooth Aloe." It produces orange-red flowers on branching stalks and is an extremely popular and hardy garden plant, widely used in Mediterranean and drought-tolerant landscaping.

---

### 15. Aloe Peckii
![Aloe Peckii](images/aloe_peckii.jpg)

| | |
|---|---|
| **Common Name** | Peck's Aloe |
| **Scientific Name** | *Aloe peckii* Bally & Verdoorn |

**Description:** Native to Somalia, Aloe peckii is a small to medium-sized aloe featuring deep green leaves with attractive white spots arranged in irregular bands or rows. The leaves have reddish-brown marginal teeth and form an elegant rosette. It produces scarlet to orange-red tubular flowers and is valued both horticulturally and as a collector's plant.

---

### 16. Aloe Perfoliata
![Aloe Perfoliata](images/aloe_perfoliata.jpg)

| | |
|---|---|
| **Common Name** | Mitre Aloe / Rubble Aloe |
| **Scientific Name** | *Aloe perfoliata* L. |

**Description:** Aloe perfoliata is a compact, clustering aloe native to the Western Cape of South Africa. It features tightly packed rosettes of blue-green leaves with reddish-brown teeth, and the leaves clasp around the stem — a characteristic known as "perfoliate." It produces bright orange-red flowers and is highly adaptable to poor, rocky soils.

---

### 17. Aloe Polyphylla
![Aloe Polyphylla](images/aloe_polyphylla.jpg)

| | |
|---|---|
| **Common Name** | Spiral Aloe / Lesotho Aloe |
| **Scientific Name** | *Aloe polyphylla* Schönland ex Pillans |

**Description:** One of the most spectacular and iconic aloes in the world, Aloe polyphylla is endemic to the high mountain grasslands of Lesotho. It is instantly recognizable by its perfectly symmetrical spiral rosette of 75–150 grey-green leaves arranged in 5 distinct rows. Classified as a protected species, it is challenging to cultivate outside its native cold, alpine habitat. It produces salmon-pink to red flowers.

---

### 18. Aloe Karasbergensis
![Aloe Karasbergensis](images/aloe_karasbergensis.jpg)

| | |
|---|---|
| **Common Name** | Karasberg Aloe |
| **Scientific Name** | *Aloe karasbergensis* Pillans |

**Description:** Native to the Karasberg Mountains of southern Namibia and the Northern Cape of South Africa, Aloe karasbergensis is a medium-sized, clustering aloe. It features dull green to greyish leaves with pale spots and brownish marginal teeth. It is adapted to extremely arid, rocky environments and produces orange to yellow-orange flowers, making it valuable for desert landscaping.

---

### 19. Aloe Maculata
![Aloe Maculata](images/aloe_maculata.jpg)

| | |
|---|---|
| **Common Name** | Soap Aloe / Zebra Aloe |
| **Scientific Name** | *Aloe maculata* All. |

**Description:** Aloe maculata is one of the most widespread and commonly cultivated aloe species, native to southern Africa. It forms broad, flat rosettes of green leaves heavily marked with irregular white spots or H-shaped markings. The leaf sap produces a lather when rubbed with water — earning it the name "Soap Aloe." It produces bicolored flowers, typically red or orange tubes with yellow-green tips, and thrives in a wide variety of conditions.

---

### 20. Aloe Marlothii
![Aloe Marlothii](images/aloe_marlothii.jpg)

| | |
|---|---|
| **Common Name** | Mountain Aloe / Flat-flowered Aloe |
| **Scientific Name** | *Aloe marlothii* A.Berger |

**Description:** One of the largest and most majestic of all aloes, Aloe marlothii is a single-stemmed tree aloe native to southern Africa, capable of reaching 4–6 meters in height. It has enormous grey-green leaves covered in reddish-brown spines on both surfaces — a feature unique among large aloes. The horizontally branching flower stalks bear dense racemes of orange to red flowers, providing a vital winter food source for sunbirds and other wildlife.

---

*README continues with sections C (Model Training Details), D (Model Evaluation), and E (Model Testing)...*

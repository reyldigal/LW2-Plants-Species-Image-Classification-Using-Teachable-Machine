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
![Aloe AJR](screenshot/plant-species/Aloe_AJR.jpg)

| | |
|---|---|
| **Common Name** | Aloe AJR |
| **Scientific Name** | *Aloe* 'AJR' (Hybrid Cultivar) |

**Description:** Aloe AJR is a compact hybrid cultivar with medium green, white-spotted leaves and serrated edges, making it a popular choice in succulent collections.

---

### 2. Aloe Arborescens
![Aloe Arborescens](images/aloe_arborescens.jpg)

| | |
|---|---|
| **Common Name** | Krantz Aloe / Candelabra Aloe |
| **Scientific Name** | *Aloe arborescens* Mill. |

**Description:** A large, multi-stemmed shrub reaching up to 3 meters tall, Aloe arborescens bears vivid red-orange flowers in winter and is widely used in traditional medicine across South Africa and Japan.

---

### 3. Aloe Aristata
![Aloe Aristata](images/aloe_aristata.jpg)

| | |
|---|---|
| **Common Name** | Lace Aloe / Torch Plant |
| **Scientific Name** | *Aloe aristata* Haw. |

**Description:** Aloe aristata is a small, stemless succulent forming dense rosettes of dark green leaves covered in white tubercles and a terminal bristle at the tip, producing orange-red flowers and thriving in cooler climates.

---

### 4. Aloe Blizzard
![Aloe Blizzard](images/aloe_blizzard.jpg)

| | |
|---|---|
| **Common Name** | Aloe Blizzard |
| **Scientific Name** | *Aloe* 'Blizzard' (Hybrid Cultivar) |

**Description:** Aloe Blizzard is a hybrid cultivar prized for its neat rosettes of green leaves densely covered in white or cream-colored spots, giving it a distinctive snow-like appearance ideal for containers and rock gardens.

---

### 5. Aloe Blue Boy
![Aloe Blue Boy](images/aloe_blue_boy.jpg)

| | |
|---|---|
| **Common Name** | Blue Boy Aloe |
| **Scientific Name** | *Aloe* 'Blue Boy' (Hybrid Cultivar) |

**Description:** Aloe Blue Boy is a hybrid cultivar distinguished by its striking blue-grey to silver-green foliage forming a compact rosette with finely toothed margins, widely used in ornamental landscaping for its unique color and drought tolerance.

---

### 6. Aloe Blue Elf
![Aloe Blue Elf](images/aloe_blue_elf.jpg)

| | |
|---|---|
| **Common Name** | Blue Elf Aloe |
| **Scientific Name** | *Aloe* 'Blue Elf' (Hybrid Cultivar) |

**Description:** Aloe Blue Elf is a compact hybrid with narrow, upright blue-green leaves and orange-toothed margins that produces prolific coral-orange flowers year-round, making it a drought-tolerant favorite in Mediterranean-climate gardens.

---

### 7. Aloe Brevifolia
![Aloe Brevifolia](images/aloe_brevifolia.jpg)

| | |
|---|---|
| **Common Name** | Short-leaved Aloe / Crocodile Aloe |
| **Scientific Name** | *Aloe brevifolia* Mill. |

**Description:** Native to the Western Cape of South Africa, Aloe brevifolia is a small clustering succulent with short, broad, blue-green leaves in tight rosettes that often turn reddish under stress and produce red-orange flowers.

---

### 8. Aloe Broomii
![Aloe Broomii](images/aloe_broomii.jpg)

| | |
|---|---|
| **Common Name** | Mountain Aloe / Snake Aloe |
| **Scientific Name** | *Aloe broomii* Schönland |

**Description:** Aloe broomii is a solitary aloe from the rocky mountain slopes of South Africa, recognized by its dense rosette of broad, grayish-green leaves with brown-tipped teeth and a tall, unusual flower spike of pale yellow blooms enclosed in reddish bracts.

---

### 9. Aloe Castillonaie
![Aloe Castillonaie](images/aloe_castillonaie.jpg)

| | |
|---|---|
| **Common Name** | Aloe Castillonaie |
| **Scientific Name** | *Aloe castillonaie* |

**Description:** Aloe castillonaie is a lesser-known, arid-adapted species with rosettes of grey-green serrated leaves, cultivated primarily by succulent enthusiasts for its distinctive form and hardiness.

---

### 10. Aloe Dial Lights
![Aloe Dial Lights](images/aloe_dial_lights.jpg)

| | |
|---|---|
| **Common Name** | Dial Lights Aloe |
| **Scientific Name** | *Aloe* 'Dial Lights' (Hybrid Cultivar) |

**Description:** Aloe Dial Lights is a vibrant hybrid cultivar whose leaves shift through shades of red, orange, and green depending on sun exposure, making it a striking drought-tolerant ornamental for gardens and containers.

---

### 11. Aloe Jurassic Dino
![Aloe Jurassic Dino](images/aloe_jurassic_dino.jpg)

| | |
|---|---|
| **Common Name** | Jurassic Dino Aloe |
| **Scientific Name** | *Aloe* 'Jurassic Dino' (Hybrid Cultivar) |

**Description:** Aloe Jurassic Dino is a bold hybrid cultivar with thick, rugged leaves featuring prominent ridges, bumps, and contrasting colors that give it a prehistoric, dinosaur-like appearance popular among collectors.

---

### 12. Aloe Krakatoa
![Aloe Krakatoa](images/aloe_krakatoa.jpg)

| | |
|---|---|
| **Common Name** | Krakatoa Aloe |
| **Scientific Name** | *Aloe* 'Krakatoa' (Hybrid Cultivar) |

**Description:** Named after the famous Indonesian volcano, Aloe Krakatoa is a compact hybrid cultivar with intensely red-orange leaves and fiery flower spikes that deepen in color with bright sunlight, ideal for low-water landscaping.

---

### 13. Aloe Krohniana
![Aloe Krohniana](images/aloe_krohniana.jpg)

| | |
|---|---|
| **Common Name** | Aloe Krohniana |
| **Scientific Name** | *Aloe krohniana* |

**Description:** Aloe krohniana is a rare collector's species prized for its intricate patterns of spots or stripes on each leaf, making every individual plant visually unique.

---

### 14. Aloe Nobilis
![Aloe Nobilis](images/aloe_nobilis.jpg)

| | |
|---|---|
| **Common Name** | Gold-tooth Aloe / Noble Aloe |
| **Scientific Name** | *Aloe nobilis* Haw. |

**Description:** Aloe nobilis is a clustering succulent from South Africa with narrow, dark green leaves edged in distinctive yellow-white teeth and orange-red flowers, making it one of the most popular and hardy garden aloes worldwide.

---

### 15. Aloe Peckii
![Aloe Peckii](images/aloe_peckii.jpg)

| | |
|---|---|
| **Common Name** | Peck's Aloe |
| **Scientific Name** | *Aloe peckii* Bally & Verdoorn |

**Description:** Native to Somalia, Aloe peckii features deep green leaves with white spots in irregular rows, reddish-brown marginal teeth, and scarlet to orange-red tubular flowers, making it a prized plant among collectors.

---

### 16. Aloe Perfoliata
![Aloe Perfoliata](images/aloe_perfoliata.jpg)

| | |
|---|---|
| **Common Name** | Mitre Aloe / Rubble Aloe |
| **Scientific Name** | *Aloe perfoliata* L. |

**Description:** Aloe perfoliata is a compact clustering aloe from the Western Cape of South Africa, notable for its blue-green leaves that clasp around the stem and its bright orange-red flowers, adapting well to poor, rocky soils.

---

### 17. Aloe Polyphylla
![Aloe Polyphylla](images/aloe_polyphylla.jpg)

| | |
|---|---|
| **Common Name** | Spiral Aloe / Lesotho Aloe |
| **Scientific Name** | *Aloe polyphylla* Schönland ex Pillans |

**Description:** Aloe polyphylla, endemic to the mountain grasslands of Lesotho, is one of the world's most iconic succulents, instantly recognizable by its perfectly symmetrical spiral rosette of up to 150 grey-green leaves arranged in 5 distinct rows.

---

### 18. Aloe Karasbergensis
![Aloe Karasbergensis](images/aloe_karasbergensis.jpg)

| | |
|---|---|
| **Common Name** | Karasberg Aloe |
| **Scientific Name** | *Aloe karasbergensis* Pillans |

**Description:** Aloe karasbergensis is a medium-sized clustering aloe from the arid mountains of Namibia and South Africa, featuring greyish spotted leaves with brownish teeth and orange to yellow-orange flowers suited to desert landscaping.

---

### 19. Aloe Maculata
![Aloe Maculata](images/aloe_maculata.jpg)

| | |
|---|---|
| **Common Name** | Soap Aloe / Zebra Aloe |
| **Scientific Name** | *Aloe maculata* All. |

**Description:** Aloe maculata is a widespread South African species forming broad, flat rosettes of green leaves heavily marked with white spots whose sap lathers with water — earning it the name "Soap Aloe" — and producing bicolored orange and yellow-green flowers.

---

### 20. Aloe Marlothii
![Aloe Marlothii](images/aloe_marlothii.jpg)

| | |
|---|---|
| **Common Name** | Mountain Aloe / Flat-flowered Aloe |
| **Scientific Name** | *Aloe marlothii* A.Berger |

**Description:** Aloe marlothii is one of the largest aloes, a single-stemmed tree reaching up to 6 meters tall with enormous grey-green leaves covered in reddish-brown spines on both surfaces and horizontally branching flower stalks that serve as a vital winter food source for wildlife.

---

*README continues with sections C (Model Training Details), D (Model Evaluation), and E (Model Testing)...*

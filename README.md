# ACK Field Observation Image Repository

This repository serves as the central file storage for field observation photographs collected by **Action for Cheetahs in Kenya (ACK)**. Photos are automatically fetched from field records, deduplicated via MD5 hashing, and committed to this repository directly through Google Apps Script and the GitHub Contents REST API.

---

## 📁 Repository Structure

Images are dynamically organized into subdirectories based on species group and observation type:

```text
photos/
├── Carnivore/
│   ├── Cheetah/
│   │   └── Carnivore_sighting_Cheetah_20260918_120000.jpg
│   ├── Cheetah_Track/
│   │   └── Carnivore_track_Cheetah_20260918_121500.jpg
│   └── Leopard_Scat/
│       └── Carnivore_scat_Leopard_20260918_130000.jpg
├── Herbivore/
│   └── Elephant/
│       └── Herbivore_sighting_Elephant_20260918_143000.jpg
└── Domestic/
    └── Cattle/
        └── Domestic_sighting_Cattle_20260918_150000.jpg
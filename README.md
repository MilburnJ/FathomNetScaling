
# FathomNetScaling: Scaling Performance Evaluation on FathomNet

This project explores the scalability of deep learning models applied to the [FathomNet](https://fathomnet.org/) dataset, which contains labeled underwater imagery for marine life classification and detection. Using PyTorch and the FathomNet API, the notebook investigates how model performance and system resources scale with dataset size, class variety, and annotation density.

## Features
- Connects to the FathomNet API to fetch bounding boxes and class metadata
- Filters marine life classes by keywords (e.g., corals, sponges, fish)
- Counts and analyzes bounding box annotations per class
- Evaluates how different dataset sizes impact training performance
- Implements visualization and logging of class distributions

### Prerequisites
Install required libraries:

pip install torch torchvision opencv-python matplotlib tqdm fathomnet pascal-voc-writer

### Setup
1. Get an API key from [FathomNet](https://fathomnet.org/)
2. Replace `x_api_key_token = ""` in the notebook with your API key
3. Run the notebook to fetch class metadata and scale performance tests

## Dataset Keywords
The notebook filters for the following marine taxa:
- Anthozoa (corals)
- Crinoidea (crinoids)
- Demospongiae, Hexactinellida, Calcarea, Homoscleromorpha (sponges)
- Agnatha, Chondrichthyes, Osteichthyes, Sarcopterygii, Actinopterygii (fish)

## Tools & Libraries
- Python
- PyTorch
- OpenCV
- FathomNet API
- Google Colab
- Matplotlib
- Pascal VOC Writer
- tqdm



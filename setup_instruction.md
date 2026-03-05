# Setup Instructions

## 1. Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

## 2. Install dependencies

```bash
pip install -r requirements.txt
```

## 3. Download SAM model checkpoints

Download the SAM model checkpoints from the following links and place them in the `src` directory:

- `vit_b (01ec64.pth)`: [https://dl.fbaipublicfiles.com/segment_anything/sam_vit_b_01ec64.pth](https://dl.fbaipublicfiles.com/segment_anything/sam_vit_b_01ec64.pth)
- `vit_h (8939.pth)`: [https://dl.fbaipublicfiles.com/segment_anything/sam_vit_h_4b8939.pth](https://dl.fbaipublicfiles.com/segment_anything/sam_vit_h_4b8939.pth)

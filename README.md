# Image Enhancement Tool

This Python program utilizes the `PIL` (Python Imaging Library) to process images by applying sharpening, converting them to greyscale, and adjusting contrast. It's a versatile tool for image enhancement that sharpens details, transforms images to greyscale, and improves contrast.

## How to Use

1. Make sure you have Python installed on your system.
2. Install the required library by running:
   ```bash
   pip install pillow
   ```

3. Place your images in the `imgs` directory within the same directory as the script.
4. Run the script:
   ```bash
   python image_enhancer.py
   ```
5. The program will process each image in the `imgs` directory, applying sharpening, greyscale conversion, and contrast adjustment.

6. The enhanced images will be saved in the `editedImgs` directory.

## Dependencies

- `PIL` (Pillow): A powerful Python Imaging Library to open, manipulate, and save many different image file formats.

## Image Processing Steps

1. **Sharpening:** The program applies a sharpening filter to enhance image details.
2. **Greyscale Conversion:** Images are converted to greyscale for a black-and-white effect.
3. **Contrast Adjustment:** Contrast is increased by a factor of 1.5, enhancing image visibility.

## Example

```bash
python image_enhancer.py
```

## Note

Ensure you comply with image usage rights and licenses while using this tool. The enhanced images are saved in the `editedImgs` directory.

Feel free to explore, contribute, and adapt this Image Enhancement Tool. If you have any questions or suggestions, please open an issue.

---

**Disclaimer:** Users are responsible for ensuring compliance with all relevant legal and ethical guidelines when using this image enhancement tool.

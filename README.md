
---

# JSON File Editing and Cloudinary Asset Upload Guide

This guide provides step-by-step instructions on how to **edit JSON files** and upload assets to **Cloudinary** for a seamless integration.

## Instructions

### 1. **Editing JSON Files**

The following fields need to be edited directly in the JSON files:

- **Description**: Directly edit the description text as per your requirement.
- **Title**: Directly edit the title text to reflect the appropriate title for the item.
- **img_url**: For images, use a **Cloudinary link** (see the Cloudinary upload instructions below).
- **link_url**: 
  - If the link is a **website**, add the direct URL.
  - If the link is for a **folder, PDF, image, or document**, upload the asset to Cloudinary (follow the steps below) and use the generated link.

### 2. **Cloudinary Link Upload Instructions**

To upload images, PDFs, videos, or any other assets to Cloudinary, follow these steps:

1. **Sign in to Cloudinary:**
   - Go to [Cloudinary Console](https://cloudinary.com/) and **sign in** with your email.

2. **Upload Asset:**
   - Navigate to the **Assets** section.
   - Find the **Desired Folder** where you want to upload the asset, or create a new folder if necessary.
   - Click **Upload** and select the image, PDF, video, or other assets you wish to upload.

3. **Copy Cloudinary Link:**
   - Once the file is uploaded, click on the **three dots** (options) next to the uploaded file.
   - Click **Copy URL** to get the Cloudinary URL of the uploaded asset.

### 3. **Image Size Requirements**

For images:
- **Image dimensions must be** `518px * 380px`.
- After uploading your image to Cloudinary, it will need to be resized to the correct dimensions. You can use **Microsoft Paint** or any image editing tool to resize the image to `518px` width and `380px` height.

### 4. **Final Steps**

Once you have edited the necessary fields in the JSON file:
- **Save** your changes.
- **Commit** and push the updated JSON file to your repository if needed.

---

## Example JSON Structure

Here's an example of how the JSON data should look after editing:

```json
{
  "title": "Item Title",
  "description": "This is a brief description of the item.",
  "img_url": "https://res.cloudinary.com/your-cloud-name/image/upload/v1610395950/example_image.jpg",
  "link_url": "https://example.com/your-link"
}
```

### Notes:
- Ensure that the **Cloudinary image links** are correctly copied.
- Always double-check the **image size** after editing in **Paint** to ensure it meets the required `518px * 380px` dimensions.
- Paste the Whole json to the ChatGpt to cross-verify the fomating of the json becuase a single coma `(,)` will effect the whole website and it will be crash.
- If still website crash and want to add a new feture contact on the mail [Enail-Id](mailto:rathoreatri@gmail.com). 

---

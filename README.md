# AI Image Generation & Social Media Publisher

Automated AI image creation and social media publishing workflow built with n8n.

## Features

- Generate AI images from text prompts
- Upload generated images to Cloudinary
- Automatically create social media captions using AI
- Publish posts to Facebook
- Publish posts to Instagram
- Update publishing status automatically

## Workflow Files

- sayan_image_creataion.json
- sayan_image_post.json

## Demo Video

- https://drive.google.com/file/d/15ZLztEr5rTkdWiCA4igdulD1QQs7AkrL/view?usp=sharing

## Technologies Used

- n8n
- Google Vertex AI
- Imagen API
- Cloudinary
- Facebook Graph API
- Instagram Graph API

## Workflow Overview

### Image Generation Workflow

1. Receive image generation prompt
2. Generate image using Google Imagen
3. Upload image to Cloudinary
4. Generate AI caption
5. Save draft

### Social Media Publishing Workflow

1. Receive draft content
2. Publish to Facebook
3. Publish to Instagram
4. Update publishing status

## How to Use

1. Import both workflows into n8n.
2. Configure Google Vertex AI credentials.
3. Configure Cloudinary credentials.
4. Configure Facebook Graph API credentials.
5. Configure Instagram Business Account.
6. Activate workflows.

## Author

Sayan Biswas

# Morovski Image & Packaging Generator

Simplified single-product tool.

## Features

- Upload one product image at a time.
- Enter product details manually.
- Generate Light ON image, Light OFF image, dimension marking image, QR code, product description, and Morovski label.
- Save generated product to batch.
- Batch Count: 0 / 10.
- Export combined vendor pack for up to 10 products.

## Removed from this version

- Bulk CSV upload
- Website upload pack
- Website CSV export

## Product fields

- Product Name
- Product Type
- Vendor Model No
- Product Size
- Holder Type
- Outer Box Size
- Colour
- MRP
- Quantity

## Deploy

Upload these to GitHub:

- app/
- public/
- package.json
- next.config.mjs
- vercel.json
- README.md

In Vercel, add environment variable:

OPENAI_API_KEY=your_openai_api_key_here


## New update: 3-image only option

This updated version adds a second generation flow:

- **Generate Only 3 Images**
  - Light ON image
  - Light OFF image
  - Dimension image

- **Generate Full Vendor Pack**
  - Light ON image
  - Light OFF image
  - Dimension image
  - QR code
  - Description
  - Morovski label

### New download options

- Download 3 Images ZIP
- Download Current Product Full ZIP

### Batch rule

Only **full vendor-pack results** can be saved to batch and exported in the combined vendor pack.

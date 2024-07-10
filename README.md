# Gridbuilder Custom Addons

Custom addons plugin for Gridbuilder, adding a new block for Product CTA Link with enhanced functionality optimized for Google Tag Manager integration.

## Installation

1. Download the latest release ZIP file.
2. Log in to your WordPress admin panel.
3. Navigate to Plugins > Add New > Upload Plugin.
4. Upload the downloaded ZIP file and click "Install Now".
5. Activate the plugin after installation.

## Usage

Once activated, the "Product CTA Link" block will be available in Gridbuilder:
- Add the block to your grid layout.
- Customize the block settings as needed.
- The block renders a button linked to the product's detail page, optimized already for Google Tag Manager with event tracking.

## Customization

You can customize the block further by editing `wpdd_prod_cta_block_render()` function in `gridbuilder-custom-addons.php` to modify HTML output or event tracking parameters.

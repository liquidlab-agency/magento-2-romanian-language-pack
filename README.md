# Magento 2 Romanian Language Pack

This package provides a comprehensive Romanian (România) language pack for Magento 2 stores.

## Overview

The Romanian Language Pack for Magento 2 allows you to translate your store into Romanian language. This translation covers the entire Magento 2 interface, including admin panel and storefront.

- **Language Code**: ro_RO
- **Compatibility**: Magento 2.x

## Installation

### Install via Composer (Recommended)

```bash
composer require liquidlab-agency/magento-2-romanian-language-pack
```

After installing the language pack, you need to deploy the static content for the Romanian locale:

```bash
php bin/magento setup:static-content:deploy ro_RO
```

Finally, clear the Magento cache:

```bash
php bin/magento cache:flush
```

### Manual Installation

1. Download the language pack
2. Extract the downloaded file
3. Create a directory structure in your Magento installation: `app/i18n/liquidlab-agency/magento-2-romanian-language-pack`
4. Copy all files from the extracted folder to the directory you created
5. Deploy the static content and flush cache as described above

## Configuration

1. Log in to your Magento Admin Panel
2. Navigate to **Stores > Configuration > General > Locale Options**
3. Set **Locale** to "Romanian (Romania)" in the dropdown menu
4. Save the configuration
5. Flush the Magento cache

## Contribution

If you find any issues or want to contribute to this translation, please feel free to submit pull requests or open issues on our repository.

## License

This language pack is licensed under:
- MIT

## Support

For any questions or support requests, please contact the authors or open an issue in the repository.
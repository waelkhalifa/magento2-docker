## Magento2 Docker in 3 simple steps (4 step is optional)

Please run the following commands:

```bash

// Download Magento
bin/download 2.4.5


// Setup your custom domain as an environment variable
export MAGENTO_BASE_URL=magento2.test


// Run docker composer up with other customizations like (adding to the domain hosts file)
bin/setup

// Run Custom Catalog via composer
bin/composer require wael/custom-catalog

```

Thanks

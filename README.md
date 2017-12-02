# Orange Cloud Foundry UI Component

This is a component for theming the Open Source Web-based UI(Console) for managing Cloud Foundry [Stratos UI](https://github.com/SUSE/stratos-ui). It follows the Orange graphic charter.

## Requirements 

You need to have already configured the `Stratos UI`. For more information check [Stratos UI Documentation](https://github.com/SUSE/stratos-ui).

## Quick Start

To set this up
1. Clone the project in a folder named orange-branding by running the following command:`$ git clone https://github.com/orange-cloudfoundry/orange-component-CF-UI.git orange-branding`
2. Move the folder `orange-branding` in the folder `stratos-ui/components/`
3. Open the file `stratos-ui/bower.json` and replace the line `"suse-branding": "./components/suse-branding"` into `"orange-branding": "./components/orange-branding"`

Once this is done your project is ready for deployement.
# Installation

Install the following packages:

    pnpm i --save-dev @eslint/js@^9.38.0 @robinbobin/eslint-config @stylistic/eslint-plugin@^5.5.0 @typescript-eslint/parser@^8.46.2 eslint@^9.38.0 eslint-import-resolver-typescript@^4.4.4 eslint-plugin-import-x@^4.16.1 eslint-plugin-promise@^7.2.1 eslint-plugin-simple-import-sort@^12.1.1 typescript-eslint@^8.46.2

# Config files

## <a name='config_eslint.config.js'></a>eslint.config.js

A script invoked during `postinstall` copies a sample ESLint config, named `eslint.config.js_<number>` to your project root dir. Don't forget to rename the file, deleting the `_<number>` part. You can copy this file manually if you don't want to let `postinstall` execute:

    cp node_modules/@robinbobin/eslint-config/eslint.config.js_<number> ./eslint.config.js

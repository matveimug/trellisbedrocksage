# trellisbedrocksage
trellis / bedrock / sage commands


```

// trellis

mkdir example.com
cd example.com
git clone --depth=1 git@github.com:roots/trellis.git && rm -rf trellis/.git
composer create-project roots/bedrock site

// bedrock

// change vars in:
# group_vars/development/wordpress_sites.yml
# group_vars/development/vault.yml

// sage

// cd to themes
composer create-project roots/sage your-theme-name
// if needed, install yarn - npm i -g yarn
cd your-theme-name
yarn
yarn build / yarn start

```

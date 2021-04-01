# strapi-provider-upload-aws-s3

https://github.com/strapi/strapi/tree/master/packages/strapi-provider-upload-aws-s3

./config/plugins.js

npm i -S strapi-provider-upload-aws-s3

В файле сделать изменения:
extensions/upload/services/image-manipulation.js


const DEFAULT_BREAKPOINTS = {
// large: 1000,
// medium: 750,
small: 500,
};

small - для показа маленьких картинок в Media Library - остальные убрать
Enable responsive friendly upload - оставить вулюченным

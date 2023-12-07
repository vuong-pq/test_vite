## env files

you can access env variables by: import.meta.env

## .env.development

contains variable used for development only

## .env.staging

contains variable used for staging only

## .env.production

contains variable used for production only

## .env

contains variable used for all environments

## run commands

## development

npm run build

## staging

npm run staging
npm run build -- --mode development

## production

npm run production

## custom env prefix

go to vite.config.ts to custom env prefix

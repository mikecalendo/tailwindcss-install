```
rm -rf package-lock.json yarn.lock node_modules/ && npm i && npm install -D tailwindcss@latest autoprefixer@latest postcss-import postcss@latest postcss-flexbugs-fixes postcss-preset-env precss postcss-import --save-dev && npx tailwind init -p

rm -rf package-lock.json yarn.lock node_modules/ && yarn && yarn add -D tailwindcss@latest autoprefixer@latest postcss@latest postcss-import postcss-flexbugs-fixes postcss-preset-env precss postcss-import --save-dev && npx tailwind init -p
```
npm install -D tailwindcss@latest \
  @tailwindcss/typography@latest \
  @tailwindcss/forms@latest \
  @tailwindcss/aspect-ratio@latest \
  @tailwindcss/line-clamp@latest \
  postcss@latest \
  autoprefixer@latest

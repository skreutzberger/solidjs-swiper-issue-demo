## Usage

This is a test repo with Solidjs and Swiperjs. It demonstrates the following error:

```
[ERROR] The JSX syntax extension is not currently enabled

    node_modules/swiper/solid/swiper-slide.js:71:4:
      71 │     <Dynamic
         ╵     ^

  The esbuild loader for this file is currently set to "js" but it must be set to "jsx" to be able
  to parse JSX syntax. You can use "loader: { '.js': 'jsx' }" to do that.

✘ [ERROR] The JSX syntax extension is not currently enabled

    node_modules/swiper/solid/swiper.js:210:4:
      210 │     <div
          ╵     ^

  The esbuild loader for this file is currently set to "js" but it must be set to "jsx" to be able
  to parse JSX syntax. You can use "loader: { '.js': 'jsx' }" to do that.

```

It seems to be an issue with Vite.

## Install & Run

```shell
yarn install
yarn dev
```

and then open [http://localhost:3000](http://localhost:3000)

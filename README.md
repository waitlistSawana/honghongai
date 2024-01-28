## HongHongAI

这是模仿DK的 [哄哄模拟器](https://hong.greatdk.com/) 做的开源免费版哄哄模拟器，大模型用的是 google 的 gemini，主打一个免费（每分钟60次调用），目前 gemini 还没有训练模型和微调（Fine-tuning），所以我用最原始的 prompt 来实现，主要参考 [宝玉老师](https://weibo.com/1727858283/ND9pOzB0K?refer_flag=1001030103_) 这版



## Tech Stack

HongHongChat is built on the following stack:

- [Next.js](https://nextjs.org/) – framework
- [Vercel AI SDK](https://sdk.vercel.ai/docs) – AI completions
- [Vercel](https://vercel.com) – deployments
- [TailwindCSS](https://tailwindcss.com/) – styles



## Environment Variables

You can control the website through environment variables.

| Name             | Description                                                  | Required |
| ---------------- | ------------------------------------------------------------ | -------- |
| `GEMINI_API_KEY` | Your API Key for GEMINI. You can get it from [here](https://makersuite.google.com/app/apikey). | **✔**    |
| `API_BASE_URL`   | Custom base url for GEMINI API. Click [here](https://github.com/babaohuang/GeminiProChat?tab=readme-ov-file#solution-for-user-location-is-not-supported-for-the-api-use) to see when to use this. | ❌        |

（sawana：第二个是必须的！点击链接会前往netlify创建一个中介站点，获取那个站点的地址！）
（另外，还能看到那个高达 3k stars 的开源项目）


## Contributing

Here's how you can contribute:

- [Open an issue](https://github.com/johanazhu/honghongai/issues) if you believe you've encountered a bug.
- Make a [pull request](https://github.com/johanazhu/honghongai/pull) to add new features/make quality-of-life improvements/fix bugs.

## License

Licensed under the [MIT license](https://github.com/johanazhu/honghongai/blob/main/LICENSE.md).

## Sawana fork

这里是sawana，如上所示这是fork了一位大佬的作品，并在其基础上进行了修改

记得前往作者的网页，那里有原本的版本。

同时，你可以查看他的主页那里有很多宝藏博客！

[哄哄模拟器开源版](https://hong.azhubaby.com/)

启动本地代码：

- `npm i`

- `npm run dev`

## Sawana 里程碑

- 2024/1/29 成功在本地启动项目！

  （遗产：一个netlify项目和对应的GitHub库、一个Github库honghongai）
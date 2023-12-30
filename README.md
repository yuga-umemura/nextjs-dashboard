## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Memo

- Tailwind antialiased(app/ui/layout.tsx)

  - フォントを滑らかにする

- ImageコンポーネントのclassNameの詳細

  - [TailwindCSS - Display](https://tailwindcss.com/docs/display)
  - classNameの解釈は「デフォルトでは非表示（hidden）であるが、mdサイズ以上の画面ではブロック要素として表示（md:block）する」である。

  ```Typescript
  <Image
    src="/hero-desktop.png"
    width={1000}
    height={760}
    className="hidden md:block"
    alt="Screenshots of the dashboard project showing desktop version"
  />
  ```

- page.tsxはReactコンポーネントをエクスポートする特別なNext.jsファイルで、ルートにアクセスするために必要。このファイルは'/'に関連づけられている。
- ネストされたルートを作成するためにはフォルダ同士をネストし、その中にpage.tsxを作成する。

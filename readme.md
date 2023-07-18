- 2023.07.18
- (c) Tomoya Onuki

# React + TypeScript Sample

## 環境構築
```
npx create-react-app --template typescript myapp
```

## 実行
- `npm start` : サーバーの起動
- `npm run build` : ビルド
- `npm test` : jestによるテスト


## App.tsxをクラスに書き換えるなら
```typescript
export default class App extends React.Component {
  public render(): React.ReactNode {
    return ('<div></div>');
  }
}
```
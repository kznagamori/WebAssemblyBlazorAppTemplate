# WebAssemblyBlazorAppTemplate
Blazor WebAssembly アプリを作成するためのテンプレート

## 使用法

### テンプレートの取得
[WASMBlazorApp.nupkg](https://github.com/kznagamori/WebAssemblyBlazorAppTemplate/releases/download/v1.0.0/kznagamori.WASMBlazorApp.1.0.0.nupkg)
をダウンロードします。

### テンプレートのインストール
ダウンロードしたnugetパッケージをインストールします。
```
dotnet new install kznagamori.WASMBlazorApp.1.0.0.nupkg
```

### Blazor WebAssembly アプリ プロジェクトの作成
```
dotnet new wasm-blazor.app -n <プロジェクト名>
```
**例:** `dotnet new wasm-blazor.app -n MyWasnBlazorApp`

### テンプレートのアンインストール
```
dotnet new  uninstall kznagamori.WASMBlazorApp
```

### ターゲット

net8.0のみをターゲットとしています。

### ビルド

```
dotnet build
```

### 動作確認
```
dotnet watch run
```

### kznagamori.WASMBlazorApp.X.X.X.nupkgの作成

```
nuget pack .\WebAssemblyBlazorAppTemplate.nuspec
```

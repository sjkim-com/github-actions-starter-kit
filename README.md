# github-actions-starter-kit

Github Actions starter kit to create actions in javascript.

tutorial example01

Github Actions simulator
````
GitHub Actionとは、GitHub上で実行できるカスタム自動化ツールです。actは、ローカル環境でGitHub ActionをテストするためのCLIツールです。

actを使用すると、ローカル環境でGitHub Actionのジョブを実行できます。これにより、GitHub上にプッシュする前に、変更したGitHub Actionの動作を確認できます。

actを使うと、ローカル環境に環境変数を設定したり、実行したいジョブを選択したりすることができます。また、Dockerイメージを使用して独自の実行環境を構築することもできます。

actは、GitHub Actionsのジョブを実行するために、GitHub Actionsランタイムを使用します。これにより、ローカル環境でGitHub Actionsと同じ方法でコマンドを実行できます。

actは、GitHub Actionsのテストや開発に役立つため、開発者にとって非常に便利なツールです。
$ brew install act

````
ncc　のINSTALL
```
nccは、Node.jsのアプリケーションやモジュールを単一のJavaScriptファイルにバンドルするためのツールです。nccは、Node.jsモジュールである@vercel/nccを使用して、複数のファイルを含むNode.jsアプリケーションやモジュールを単一のファイルにまとめます。

nccを使用することで、依存関係を持つNode.jsモジュールやアプリケーションを、1つのファイルにまとめることができます。これにより、単一のファイルを使用して、Node.jsアプリケーションやモジュールをより簡単に配布できるようになります。

また、nccを使用すると、Node.jsアプリケーションやモジュールのバンドルを最適化することもできます。nccは、Tree-shakingや最適化されたコード生成を行い、バンドルされたファイルのサイズを最小限に抑えることができます。

nccは、Node.jsのアプリケーションやモジュールをバンドルするための便利なツールであり、特にWebアプリケーションやサーバーレスアプリケーションのデプロイメントに役立ちます。
```

```
git clone https://github.com/sjkim-com/github-actions-starter-kit
cd github-actions-starter-kit
yarn 
```
Github Actions를 개발할 때, Github REST API를 사용하는 경우가 많기 때문에 아래의 패키지를 설치한다.

``` 
yarn add @actions/core --save
yarn add @actions/github --save
```


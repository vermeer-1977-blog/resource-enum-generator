# resource-enum-generator
annotation-processorを用いてリソースからEnumクラスを作成します。

## ResourceからEnumを作成する

### 概要
ResourceBundleでPropertiesファイルを参照して、その内容を元にEnumを作成します。

### 詳細
想定ケース：メッセージ定数を管理しているEnumを常に最新化する。
<P>
リソースを変更してコンパイルするだけでプログラムで使用するメッセージEnumクラスも更新するので、リソースとEnumクラスの同期漏れのリスクが軽減します。

### 関連プロジェクト
`annotation-processor`

### version 0.1.0
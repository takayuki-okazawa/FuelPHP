#FuelPHP

####インストール
$ curl get.fuelphp.com/oil | sh

####プロジェクト作成
$ oil create <project_name>

####依存ライブラリを動的に取得
$ php composer.phar self-update
$ php composer.phar update

####作成したプロジェクトの実行
Public以下が表示される。

* http://localhost:8888/fuel/public/

		/YUOR_PROJECT_HOME/public/index.php

* http://localhost:8888/fuel/public/hello/

		/YUOR_PROJECT_HOME/hoge/app/classes/controller/Welcome.php



####Model
HOME/app/classes/view/welcome/hoge.php

####View
HOME/app/views/welcome

####Controler
HOME/app/classes/controller/welcome.php
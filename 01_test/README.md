* 以下を順番に実行

    * Vagrantfileを作成
    ```sh
    vagrant init
    ```
    * VagrantfileのBOXの内容を書き替える
    ```rd
    config.vm.box = "ubuntu/bionic64"
    ```
    * VMの立ち上げ
    ```sh
    vagrant up
    ```
    * VMの状態確認
    ```sh
    vagrant status
    ```
    * ssh接続
    ```sh
    vagarnt ssh
    ```
    * VMの削除
    ```sh
    vagrant destroy
    ```



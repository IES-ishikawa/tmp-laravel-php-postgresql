## initialize_db フォルダの使用方法

Docker コンテナ上に PostgreSQL を構築する際に、実行する SQL を定義します。  
SQLは「UTF-8」で読まれます。  
ファイル名は「x\_〇〇〇.sql」としてください。  
「x」は半角数字としてください。  
「x」の値が小さい SQL ファイルから順に実行されます。  
コンテナの構築時に実行されます。  
コンテナの起動時には実行されず、起動時には前回のデータが残っています。  
コンテナの構築時に実行されるため、再度当フォルダの SQL を実行したい場合には DB コンテナを削除したうえで当リポジトリをコンテナで開くと DB コンテナの構築が始まり、SQL が実行されます。  
DB コンテナを削除した場合はレコードも削除されてしまいますので適時 Backup など取っておいてください。  


# Java

### わからないことまとめ

- 型の種類と使い分け
  - プリミティブ型と参照型  
    - プリミティブ型  
      - long
      - int
      - short
      - byte
      - double
      - float
      - boolean
      - char
    - 参照型
      - 上記以外
  
  
- static変数について  
  インスタンス化せずにその変数にアクセスすることができる変数。
 - 書き方  
   アクセス修飾子(publicなど) static 型名 変数名
 - 注意点  
 staticメソッドや変数は、ある箇所で変数の値を変更されたら他に参照しているところすべてに影響が出ることになるため。


- 継承の利用方法

- ポリフォーリズムとは

- シリアライザブルの効果

- コンストラクタの使い方

- 型による比較方法の差異

- Listの使い方

  - Listの考え方

  - Listへの要素追加、変更、削除
  - Listの並び替え（何順で表示するのか）
- Setの使い方  
Listと似ているが、重複する値を保有できない。

- Mapの使い方

  - Mapの考え方

  - Mapへの要素追加、変更、削除
  - Mapの並び替え（何順で表示するのか）

- Stream

  - Streamの考え方
  - Streamでできること
  - 中間操作
    - map  
      - 各要素を２倍にする操作  
      > List<Integer> newNums = nums.stream().map(num -> 2 * num).collect(Collectors.toList());
      - 置き換える操作
      > List<String> newStrs = strs.stream().map(str -> str.replace("BC", "Z")).collect(Collectors.toList());

- for文のパターンまとめ
- 


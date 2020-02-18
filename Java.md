# Java

### わからないことまとめ

- 型の種類と使い分け

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


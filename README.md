# Latin Ukrainian Alphabet
The nice Latin transliteration for Ukrainian language.

### What is this
The enhanced version of Ukrainian to Latin transliteration with some beautiful letters like "Ł", "Č", "Ż", "Š" and leaving "ї", "Ґ".

The text:
> В лісі щось загомоніло, струмок зашумував, забринів, і вкупі з його водами з лісу вибіг "Той, що греблі рве" — молодий, дуже білявий, синьоокий, з буйними і разом плавкими рухами; одежа на йому міниться барвами, від каламутно-жовтої до ясно-блакитної, і поблискує гострими злотистими іскрами. Кинувшися з потоку в озеро, він починає кружляти по плесі, хвилюючи його сонну воду; туман розбігається, вода синішає.

becomes:

> W lisi ščos zagomoniło, strumok zašumuwaw, zabryniw, i wkupi z jogo wodamy z lisu wybig "Toj, ščo grebli rwe" — mołodyj, duże bilawyj, syniookyj, z bujnymy i razom pławkymy ruhamy; odeża na jomu minytsia barwamy, wid kałamutno-żowtoї do jasno-błakytnoї, i pobłyskuje gostrymy złotystymy iskramy. Kynuwšysia z potoku w ozero, win počynaje krużlaty po płesi, hwylujučy jogo sonnu wodu; tuman rozbigajetsia, woda synišaje.

### Usage
```
./translit src.txt [output.txt]
```

### Disclaimer
The project is tested on just few texts and needs for further tuning by addition of rules.

### Customize language
Also you can translate words you like to get your customized language. Open the **translit_rules** file and add your words in the first section under the line ```# Word translation if you want```.

### Thanks
1. Eastern and Northern European countries for some letters.
2. https://en.wikipedia.org/wiki/Ukrainian_Latin_alphabet
3. https://en.wikipedia.org/wiki/Romanization_of_Ukrainian

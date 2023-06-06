<details><summary><b>1.Movzu:Bezi axdarislar..</b></summary><br/><br/>
<a href="https://stackoverflow.com/questions/449887/sending-e-mail-using-c-sharp">1.C# E-mail gondermek yolu !</a><br>
<a href="https://survey.stackoverflow.co/2022/#technology">2.Burada proqram dillerinin ilden ile inkisafina baxa bilerik !</a><br>
<a href="https://app.diagrams.net/#G1mSYKv9CSSXe6tr4bshxjfb5QuU_hI0kP">3.Alqoritim qurmaq ucun isdifade edilen sexemleri bize verir !</a><br>
<a href="https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/">4.C# da acar sozlere baxmaq !</a><br>
<a href="http://www.java2s.com/Tutorial/CSharp/CatalogCSharp.htm">5.C# ders sayiti !</a><br>
<a href="http://extraconversion.com/base-number">6.Say sisteminin cevrilisi!</a></details>

<details><summary><b>2.Movzu:Cmd ---- emirleri.</b></summary><br/><br/>
1.<b>cd bosluq enter</b> oldugun fayila aparir.<br/> 2.<b>cd bosluq ..</b> bir fayil geri cixir.<br/> 3.<b>cd bosluq fayilin adi</b> adi qeyd edilen fayila kecit edir.<br/> 4.<b>cls</b>acilmis butun melumatlari temizleyir.<br/> 5.<b>dir</b> fayilin icine daxil olur.<br/> 6.<b>mkdir</b> yeni fayil yaradir.<br/> 7.<b>prompt $$</b> yeni setri dollar isaresi ile basladir.<br/> 8.<b>dotnet run</b> emri ise kodu ise salir.<br/> 9.<b>code .</b> visual studio coda kecid emridir.<br/> 10.<b>echo "" >>.gitignore</b> -- burada yeni cmd ekraninda .gitignore fayili yarada bilerik bu emirle.<br/> 11.<b>rundll32.exe user32.dll,LockWorkStation</b> komputeri cmd ile kilidlemek ucun olan emir.<br/>
<b><i>(Solutions and project)</i></b><br/>
QEYD. Cmd --qara ekrandan istifade ederek biz yeni solutions ve preject yarada bilerik.Bunun ucun bir nece etablari kecmeliyik.Evvelce yeni fayil yaratmaliyiq. Fayili ise mkdir emri ile yarada bilerik bunu yuxarida qeyd etmisem . Yeni Solutions ve project yaradaq..

1.  ci mkdir emri ile fayil yaradiriq.
2.  ci dotnet new sln --name (solutions adi meselen: code)
3.  cu project yaratmaq ucun--> dotnet new console --framework net6.0 --use-program-main emrinden istifade edirik .Burada isdesek net6.0 fersiyani istesek deyise bilerik.
4.  cu ise solutions ve projecti elaqelendiririk-->> dotnet sln (solution adi yeni:code) add 5.project\csproj sonlugu ile biten fayil ve enter.<br/>

.<b>Axdaris yerine dotnet new sln --name MySolution</b>-yazdiqda asagidaki sekili tapmaq lazimdir.
<i>Sayita daxil olduqdan sonra bu (dotnet new sln --name MySolution) yazilisi tapib isdifade ede bilerik. </i><br/>

<p>
<img src="image\cs35.png" alt="Sekil silinib" title="Yeni solutions yaratmaq."/>
</p><br/> 13.<b>
<p> Axdaris yerine dotnet create new console app project yazzsaq yeni project yaratmaq ucun asagidaki sekil gelecekdir.
<img src="image\cs36.png" alt="Sekil silinib" title="Yeni project yaratmaq."/>
</p><br/> 14.<i> Yaratdigimiz solutions ve projecs elaqelendirmek ucun google axdarisa (dotnet add project solutions create) sayita daxil olduqdan sonra ise qarsimiza cixan (dotnet sln solution.sln add --solution-folder foo1\foo2\foo3 bar.csproj) yazilisdan istifade ederek elaqeni yaradiriq.</i><br/>
<p>
<img src="image\cs37.png" alt="Sekil silinib" title="Yeni solutions yaratmaq."/>
</p><br/>
</details>

<details><summary><b>3.Movzu:GITHUB ---->> Yaratmaq.</b></summary><br/><br/>
    QEYD. Github yaratmaq ucun profile daxil olub qeydiyatdan kecirik, daha sonra ise bir nece emirden isdifade ederek yeni repositories yarada bilerik .
    …or create a new repository on the command line

5.  git clone (linkimizi buraya yerlesdiririk).<br/>
6.  echo "dirnaq arasina ne isdesez yaza bilersiz">> README.md -------->>(readme fayili yaratmaq ucundur.)<br/>
7.  git init ---------->>>(git pafqasi yaratmaq ucundur )<br/>
8.  git add README.md ------->>(readmi fayilini testiq etmek ucun)<br/>
9.  git commit -m "first commit" -----(deyisikliye ad vermek ucun)<br/>
10. git branch -M main<br/>
11. git remote add origin https://github.com/xasiyevsamir/taskkkk.git<br/>
12. git push -u origin main<br/>
Bu emirlerden istifade etmekle yeni repositories yarada bilerik!!!
</details>
<details><summary><b>4.Movzu:Math sinifi.</b></summary><br/><br/>

13. **(Math.Pow(10,2))** ---> burada 10 kvadratini yazmisiq yeni (10\*10) .Bunu isdediyimiz kimi yaza bilerik yeni kub ve s. Meselen: Math.Pow(10,3) , (10,4).
14. **(Math.Log10)**---> ededin nece reqemli oldugunu tapir amma neticenin usdune mutleq 1 gelirik.
15. **(Math.sqrt)**----> koku tapmaq ucun istifada edilir.
16. **(Math.Round)**---> riyazi yuvarlasdirmaq ucun istifade edilir.
17. **(Math.Floor)**---> asagi yuvarlasdirmaq,yeni tam hisseye kimi atir.
18. **(Math.Ceiling)**---> yuxari yuvarlasdirmaq.
19. **(Math.PI)**---> pi deyeridir .hesabliyada isdifade ede bilerik.
20. **(Math.Abs)**--->Modulu tapmaq ucundur.
21. **(Math.Max)**--> ededin maksimumun tapir.
22. **(Math.Min)**--> ededin minumumun tapir.
</details>
<details><summary><b>5.Movzu:Vareybillar ve Tiplerin bir-birine cevrilmesi.</b></summary>
23. Vareybillar bizim kod yazarken adlandirdigimiz hissedir ,yeni aldigimiz melumati, deyeri neyin daxilinde saxliyiriqsa bunlara vareybillar deyilir.Mes : int a =10; string b="cofe", double c=12.3;
burada a,b, ve c vareybil adlanir.Vareybillari biz teyin edirik. Burada 10, 12.3, "cofe" ise data adlanir yeni melumat.Burada int, string ve double ise bizim datatype adlanir.Yeni datatype datanin hansi tipdan oldugunu bildirir, fincanda cofe dedikde burda cofe data b vareybil string ise datatype-dir.Yeni fincanin hansi materialdan oldugunu bildirir yeni saxsi ve ya suse.
<b>DateType-larin Novleri .</b>DateType 2 novu var <b>(Value ve Refarence)</b><br/><details><summary><b>Value</b></summary>Reqem tipli datalari saxlamaq ucundur Mes:<b>int,double,float,byte</b><br/><b>Reqem Tiplerin Cevrilmesi.</b> Bunun 2 izahi var.<br/> <b>1.Implicit ot auto conversion.</b><br/><i>Sekilde gorduyumuz kimi az tutumlu datetype cox tutumlu datetype uzerine atriq yeni onsuzda short ve int byte uzerine gotre bilir ve buna gorede bu cevirmeye avtomatic implicit deyilir.Yeni avtomatiq olaraq cevrir problemsiz.</i>
<a href="https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/builtin-types/integral-numeric-types">1.Reqem tiplere bax.</a><br/>
<a href="http://www.unitconversion.org/numbers/base-10-to-base-2-conversion.html">2.Say sistemlerine cevirmeler.</a><br/>
<p>
 <img src="image\cs1.png" width="300" height="200" alt="Sekil silinib" title="Cevirme avtomatic implicit"/>
 </p><br/>
 <b>2.Explicit conversion.</b><br/>
 <i>Sekilden gorduyumuz kimi int tipinden olan bir datani ondan kicik tipe int-e cevirmek isdemisik ve biz cevirerken (short) yazmaqla demisik ki problem yoxdu int tipinde olan datani short tipi qebul ede bilecek ve qebul ede bilmese mesuliyyeti uzerime gotrurem .Eger short gotre bilmerse hemin tipi dovur edir ve ozu gotre bileceyi datada dayanir.Eger biz problem oldugu halda bize melum olmagini isdesek <b>checked</b>-ile biz bu erroru gore bilerik.</i>
 <p>
 <img src="image\cs2.png" width="300" height="200" alt="Sekil silinib" title="Explicit conversion."/>
 <img src="image\cs3.png" width="300" height="200" alt="Sekil silinib" title="Checked erroru."/>
</p>
 </details>
<details><summary><b>Refarence</b></summary><br/>Metin tipli datalari saxlamaq ucundur Mes:<b>string, char, class,Method,Massiv ve s.</b><br/>
<b><i>1.Convert.ToInt32</i></b>----> <i>Butun tiplerden cevirme apara bilir Parse dan ferqli olaraq.</i><br/>
<b><i>2.Tipin adi.Parse</i></b> ----> </i>Yalniz reqem tipli stringleri cevire bilir. mes: "123". Yeni string olmayan neyise cevire bilmir</i>.<br/>
<b><i>3.Tipin adi.TryParse(date, out Tipin adi a)</b></i>---> <i>bu cevirme digerlerinden ferqlenir yeni geriye bool (ture,false) qaytarir yeni cevrile bilir ya cevrile bilmir .</i></details></details>
<details><summary><b>6.Movzu: Operatorlar.</b></summary>
Operatorlar bir nece yere ayrilirlar bunlar asagidakilardir.
<p>
 <img src="image\cs4.png" width="650" height="400" alt="Sekil silinib" title="Operatorlar."/>
 </p><br/>

 <details><summary><p><b>Sade operatorlar--></b>
 <img src="image\cs6.png" width="300"  alt="Sekil silinib" title=" Sade Operatorlar."/>
 </p></summary>
<p>
 <img src="image\cs5.png" width="30px" height="30px" alt="Sekil silinib" title=" Toplama Operatoru."/>
 __Toplama emeliyyatini yerine yetirmek ucundur.<b> int number=number1+number2</b><br/>
 <img src="image\cs7.png" width="30px" height="30px" alt="Sekil silinib" title=" Cixma Operatoru."/>
 __Cixma emeliyyatini yerine yetirmek ucundur.<b> int number=number1-number2</b><br/>
 <img src="image\cs8.png" width="30px" height="30px" alt="Sekil silinib" title="Vurma Operatoru."/>
 __Vurma emeliyyatini yerine yetirmek ucundur.<b> int number=number1*number2</b><br/>
 <img src="image\cs9.png" width="30px" height="30px" alt="Sekil silinib" title="Bolme Operatoru."/>
 __Bolme emeliyyatini yerine yetirmek ucundur.<b> int number=number1/number2</b><br/>
 <img src="image\cs10.png" width="30px" height="30px" alt="Sekil silinib" title="Qaliq Alma Operatoru."/>
 __Qaliq alma emeliyyatini yerine yetirmek ucundur.<b> int number=number1%number2</b><br/>
 <img src="image\cs11.png" width="30px" height="30px" alt="Sekil silinib" title="Bir artirma Operatoru."/>
 __Bir artirma emeliyyatini yerine yetirmek ucundur.<b> int number=5; number++;</b><br/>
 <img src="image\cs12.png" width="30px" height="30px" alt="Sekil silinib" title="Bir azaltma Operatoru."/>
 __Bir azaltma emeliyyatini yerine yetirmek ucundur.<b> int number=5; number--;</b><br/>
 </p></details>
 <details><summary><p><b> Mentiqsel operatorlar--></b>
 <img src="image\cs13.png" width="300"  alt="Sekil silinib" title="Mentiqsel operatorlar."/>
 </p></summary>
 <img src="image\cs14.png" width="30px" height="30px" alt="Sekil silinib" title="Beraberdir Operatoru."/>
 __Beraberdir sertini yoxlamaq ucun operatordur ve geriye <b><i>true, false</i></b> qaytarir.<b></b><br/>
 <img src="image\cs15.png" alt="Sekil silinib" title="If ile yoxlamaq."/><br/>
 <img src="image\16.png" width="30px" height="30px" alt="Sekil silinib" title=" Ferqli Beraberdir Operatoru."/>
 __ Ferqli Beraberdir sertini yoxlamaq ucun operatordur ve geriye <b><i>true, false</i></b> qaytarir.<b></b><br/>
 <img src="image\cs16.png" alt="Sekil silinib" title="If ile yoxlamaq."/><br/>
 <img src="image\cs17.png" width="30px" height="30px" alt="Sekil silinib" title="Boyukdur Kicikdir Operatoru."/>
 __ Boyuk ve ya Kicik olub olmadigini yoxlamaq ucun operatordur ve geriye <b><i>true, false</i></b> qaytarir.<br/>
 <img src="image\cs18.png" alt="Sekil silinib" title="If ile yoxlamaq."/><br/>
 <img src="image\cs19.png" width="30px" height="30px" alt="Sekil silinib" title="Boyuk beraberdir Kicik beraberdir Operatoru."/>
 __ Boyuk beraberdir ve ya Kicik beraberdir olub olmadigini yoxlamaq ucun operatordur ve geriye <b><i>true, false</i></b> qaytarir.<br/>
 <img src="image\cs20.png" alt="Sekil silinib" title="If ile yoxlamaq."/><br/>
 <p>
 </details>
<details><summary><p><b>Serti operatorlar--></b>
 <img src="image\cs21.png" width="300"  alt="Sekil silinib" title="Serti operatorlar."/>
 </p></summary>
 <p>
 <img src="image\cs22.png" width="30px" height="30px" alt="Sekil silinib" title="Ve Operatoru."/>
 __ Ve operatoru butun sertlerin dogru olub olmadigini yoxlamaq ucun operatordur ve geriye <b><i>true, false</i></b> qaytarir. Butun sertler mutleq dogru olmalidir.Qeyd edek ki VE operatoru butun sertlerin her birini yoxlayir ki belke sonuncu sert false oldu diye.<br/>
 <img src="image\cs23.png" alt="Sekil silinib" title="If ile yoxlamaq."/><br/>
 <img src="image\cs24.png" width="30px" height="30px" alt="Sekil silinib" title="Ve ya Operatoru."/>
 __ Ve ya operatoru sertlerin hec olmasa biri dogru olub olmadigini yoxlamaq ucun operatordur ve geriye <b><i>true, false</i></b> qaytarir.Sertlererin hec olmasa biri mutleq dogru olmalidir.Qeyd edek kiVE YA operatoru evvelki sertlerde true gorse diger sertleri yoxlamir cunki VE YA operatorununa bir ture serti de qanedir.<br/>
 <img src="image\cs25.png" alt="Sekil silinib" title="If ile yoxlamaq."/><br/>
 <img src="image\cs26.png" width="30px" height="30px" alt="Sekil silinib" title="Inkar Operatoru."/>
 __ Inkar operatoru eger sertde <i>ture</i> gelse onu <i>false</i>, <i>false</i> gelse ise <i>true </i>edecekdir.<br/>
 <img src="image\cs27.png" alt="Sekil silinib" title="If ile yoxlamaq."/><br/>
 </p></details>
 <details><summary><p><b>BitWise operatorlar--></b>
 <img src="image\cs28.png" width="300"  alt="Sekil silinib" title="BitWise operatorlar."/>
 </p></summary>
 <p>
 <b>Hazirlanmayib.</b>
 </p>
 <p></details>
<details><summary><p><b>Teyin operatorlar--></b>
 <img src="image\cs29.png" width="300"  alt="Sekil silinib" title="Teyin operatorlar."/>
 </p></summary>
 <p>
 <img src="image\cs30.png" width="30px" height="30px" alt="Sekil silinib" title="Data Cix menimsetme Operatoru."/>
 __ Bu operatoru qisa yazilisda isdifade edirik .Sekilde baxa bilersiz.<br/>
 <img src="image\cs32.png" width="300"  alt="Sekil silinib" title="Qisa yazilis izah."/><br/>
 <img src="image\cs33.png" width="30px" height="30px" alt="Sekil silinib" title="Data Topla menimsetme Operatoru."/>
 __ Bu operatoru qisa yazilisda isdifade edirik .Sekilde baxa bilersiz.<br/>
 <img src="image\cs31.png" width="300"  alt="Sekil silinib" title="Qisa yazilis izah."/>
 <h1>Eyni ile vurma bolme eynidir.</h1>
 </p>
</details>
<details><summary><p><b>Muxdelif emeliyyat operatorlar--></b>
 <img src="image\cs34.png" width="300"  alt="Sekil silinib" title="Muxdelif emeliyyat operatorlar"/>
 </p></summary>
<p>
<h1>Hazir deyil</h1>
</p>
</details>
<details><summary><b>7.Movzu:Console codlari.</b></summary>
1.<b></b>Console.Write();</b> ---> bu kod vasitesi ile biz ekranda her hansi bir melumati cap(yazdira) ede bilerik.Yazini cap edir ve nobeti yazini cap etdirende qarsisina alir yeni Console.Write("samir")
Console.Write("xasiyev") netice---> samirxasiyev olacaqdir. oldugu setirde qalir.<br/> 2.<b>Console.WriteLine();</b> ---> bu yuxaridaki emirle eynidir lakin bu emirde eyni setirde deyil novbeti setire kecid olunur.<b>Netice----> samir </b> --->> xasiyev olacaqdir.<br/> 5.<b>Console.Redkey();</b> yazilmis her hansi melumati oxumaq ucun ekranda gozluyer bir melumat daxil etdikde ise baglanar.<br/> 6.<b>var key=Console.ReadKey(), (key.Key==ConsoleKey.Enter)</b>bu yazilisla biz isdifadecinin hasi duymeni sabasini izah ede bilerik.<br/> 7.<b>Console.ReadLine();</b> istifadeciden melumat almaq ucun ekranda gozluyer melumati daxil edib enteri basdiqada melumati bize getrir.<br/> 8.<b>Console.CursorTop()</b> bu method ise kursorun hal hazirki durdugu yeri gosderir.<br/> 9.<b>Console.SetCursorPosition(0,Console.CursorTop)</b> bu method ile cursoru harda durmagindan asli olmayaraq hemin setrin ilk baslangicina getrir.burada sifir o demekdirki hemin setr olsun Console.CursorTop ise hemin setirde kursorun hal hazirki durdugu yer.<br/> 10.<b>Console.WindowWidth</b> bu ise console ekrani boyunca demekdir.<br/>
</details>

                                                   __(Datatypes.)__
      Datatayiplar 4 yere ayrilir .Metin, say, mentiqi, zaman,

**(metin tipli deyiskenler)**

1.  **(string)** --> Her hansi bir metin tipli melumatlari saxlamaq ucun istifade edilir.Mes: string[] name ="samir", "samir 123","1234", stringin uzunlugu **name.Lenght)** tapilir bu zaman bosluqlarda sayilir,mes: "samir 123" de uzunluq 9 dur.
2.  **(Char)** --> bu tipde string tipi kimi eynidir lakin bir metin yeni A,B daxil etdikde istifade edrik eyni zamanda string de istifade etmek dogrudur .
    **string ve char metotlari)**

- **(Join())** (qosmaq,birlesdirmek menasini verir) bu metot ile metinleri bir birine isdediyimiz sekilde birlesdire bilerik. Mes: **string name1=string.Join("\*",name))** -->Netice:samir*samir 123*1234 string[] ve char[] massivine ayitdir.
- **(ToCharArray())** bu method ile stringde olan metni herif herif Char[] masivine yazdira bilerik.
- **(Array.Reverse())** bu method masivlerin sonuncu ideksinden baslar sifirinci idekse atar sora axirdan 2ci ideksi birinci indekse atar ve s.
- **(Data.PadLeft(6,'0'))** bu metot sola isdenilen simvolu ve ya bolsulugu atmaq ucundur.Burda sola 6 sifir atdiq.
- **(Data.PadRight(6,'0'))** bu method saga isdelinen simvolu ve ya boslugu atmaq ucundur.Burda saga 6 sifir atdiq.
- **(Data.ToUpper())** bu method gelen ve ya elimizde olan datani hamisini boyuk heriflere cevirir.
- **(Data.ToLower())** bu method gelen ve ya elimizde olan datanin hamisini kicik herife cevirir.
- **(Data.Substring(0,4))** bu method datada necenci indeksden deyrikse ordan basliyir ve nece element gotur deyirikse o qederini gotrur, mes:burda 0-ci indeksden basliyir ve 4 element gotrur.
- **(Data.IndexOf)**(indeks menasina gelir)--> bu method ise massiv ve ya kolleksionun daxilinde her hansi data var sa onun indeksini geri int olaraq donur.mes: **(int indeks= A1.IndexOf("samir");)** sozu varsa gedib onun indeksini tapib getrir.Amma qeyd edek ki bu method qarsisina cixan birinci elementin indeksini gotrur ve emeliyyati bitrir ,yeni orda bir nece samir sozu olsa ilk qarsisina cixani goturecekdi. Qeyd: edeki eger axdardigimiz soz orada yoxdursa int olaraq geri donus **-1)** olacaqdir .Cunki sifir ozu mumkun indeksdir.
- **(Data.Replace("samir","valeh"))** bu method ise metinde olan isdenilen datani basqa data ile deyismeye imkan verir.Burada samir sozunu metinden cixarib valeh sozunu elave etdik.
- **(Data.Trim())** bu method sonda ve evvelde ki bosluqlari ve ya **Data.Trim('\*'))** sonu ve evelindeki ulduz ve ya diger simvollar olarsa olarida silecek.
- **(Data.TrimStart())** bu methodda trimden toreyib ve ondan ferqli olaraq datanin evvelindeki boslugu ve ya simvolu silir.
- **(Data.TrimEnd())** bu methodda trimden toreyib ve ondan ferqli olaraq datanin sonundaki boslugu ve ya simvollari silir.
- **(Data.LastIndexOf())** IndexOf ile eyni isi gorur sadece axdarisa sondan baslayir ve ilk dogru melumati tapan kimi onun indeksini int olaraq geri donur ve emeliyyatii bitirir.Qeyd: LastIndexOf sondan basliyaraq yoxlayir ve ilk uygun datanin ik elementinin indeksini geri qaytarir mes:(samir) axdarsaq s- herifinin indeksini bize geri donus edecek.
- **(Data.Insert(1,"salam"))** bu method ile isdenilen indekse isdediyimiz datani elave ede bilerik.burada 1ci indekse salam sozunu elave etdik.
- **(Data.Remove(1,2))** bu method ile isdenilen indeksden baslayib sile bilerik eyni zamanda silme araliginida biz veririk meselen biz burda 1 ci indeksden basla 2 element sil demisik.
- string s=new string('\*',3) --> bu o demekdir ki 3 dene \*\*\* yazdiracaq.Amma method deyil string obyektidir.

---

4.  **StringBuilder sb = new StringBuilder();)** bu da bir sinifdir ve metinlerle isleyir ve string tiplerinden daha cox suretlidi kolleksiondur demek olar ki. ve onun metodlari asagidakilardir.

- **sb.Append("samir"))** bu methodun komeyi ile datani stringbuilder e elave etmek olar.Bu methodun 25 overladi var ve demek olarki butun tipleri stringbuilder e elave etmek olur.
- **sb.AppendLine())** bu method ise datani elave edir ve novbeti datani bir asagi setre elave edir.BU methodun 3 overladi var yeni bezi tipleri stringe cevrib gondermeliyik.
- **sb.AppendFormat("{0}{1}",2,3))** bu method ile stringleri datalara uygun yaza bilerik.Burada 0 ci indekse 2 1ci indekse ise 3 atdi.
- **sb.AppendJoin())** bu method ise stringlerde oldugu kimi burdada datalari bir birine isdediyimiz kimi birlesdirir.
- **sb.Clear())** bu method ile datani sile bilerik.
- **sb.Lenngh)** bu ise method deyil sadece uzunlugunu tapa bilerik stringbuildin.
- **sb.Capacity)** bu da method deyil sadece ayirdigi yerdir .

5.  **(object)** bu tip uzerine butun tipleri ala bilir yeni inti, double, string ve s.Lakin uzerine aldigi tipi o tip kimi de cixarmalidir. int a=10; object b=a;(qutulama boxing) int c=(int)b;(qutudan cixartma unboxing). bunlari intin dauble kecidi ve double
    inte kecidi ile qarisdirmaq olma . Cox oxsasada coxda ferqlidirler. object tipin eslinde xaricden nese gelerse saxlanilmasi uc isdifade oluna biler. Cunki biz xaricden hansi tipin geleceyini bilmirik .
6.  **(var)**---> Var sagina baxaraq datanin hansi tipden oldugunu anliyir. var tip deyil .
7.  **(dynamic)** tipdir ve onun icindeki datalara baxa ve uzerinde emeliyat apara bilerik.sadece sehv nese daxil etdikde error bizden gizledir.
8.  **(as)** bu kivord obyekte geden tipin hansi tip oldugunu bilmek ucun ve as kivordu geriye null qaytarir. Null ola bileceyini demek isdiyirikse ? isaresinden istifade edirik mes: byte? a=b as byte?.
9.  **(is)** bu kivord de eyni ile as benzeyir yeni opject den gelen bayitdirmi int c =10; object v=c; (v is byte) ve ya (v is int)

---

0 **(DIL MEDENIYETI)**

1.  **(Console.OutputEncoding = Encoding.Unicode;)** biz elimizde olan datani cole yeni fronta gondererken bu codu yazmaliyiq ki bezi herifleri tanimir ve onlarida tanisin.
2.  **(Console.InputEncoding = Encoding.Unicode;)** biz colde olan datani yeni frontda olan datani iceri back e gonderirikse bu codu yazmaliyiq ki duzgun olaraq daxil etsin.
3.  **(CultureInfo ce = new CultureInfo("az-Latn-AZ"); Thread.CurrentThread.CurrentCulture = ce;)** bunu yazdiqda ise proqram sirf azerbaycan dilinde isleyecek **Culture-(medeniyet), Thread-(Movzu), Current-(Cari, indiki), --menasina gelir)**.
4.  **(System.Threading.Thread.Sleep(1000);)** bu ise gozlemedi yeni saniye seklinde 1000-1 saniyedir. **Sleep()-yatmaq ,qalmaq, gozlemek, menasina gelir)**.
5.  **Stopwatch stopwatch = new Stopwatch();)** bu da bir sinifdir lakinbu melumat saxlamaq ucun deyil sadece yazdigimiz codlarin nece saniye erzinde isliyib basa catdigini bilerik. Bunun da methodlari vardir.

- **stopwatch.Start())** bu methodu ise baslamamisdan evvel ise salmaq ucundur.
- **stopwatch.Stop())** bu method ise is bitenden sonra isdifade edilir ki it bitene qeder olcsun.

---

**(Say tipli datatayplar)**

1.  **(byte)** ---> tutumu {0,255} dir mes: byte say1=10;
2.  **(sbyte)**--> 255 iki hisseye ayrilir ve (-128-->127 kimi).
3.  **(int)** ----> tutumu {biraz coxdur} mes: int say2=1234345;
4.  **(uint)**--> minusdari pilusdarinin uzerine gelir ve buda tutumunu artirir.
5.  **(double)** --->tutumu {coxdur} mes: double say3=1234565432; bunda elave kesir ededleride ozunde saxliya bilir.
6.  **(float)** ----> tutumu {coxdur} mes: float say4=123432F; kesir ededleri saxliya bilir sonuna mutleq F herifi qoymaliyiq.
7.  **(decimal)** ---->tutumu {coxdur} mes: decimal say4=1233212321 M; kesir ededleri saxliya bilir sonuna mutleq M herifi qoymaliyiq.
8.  **(long)** --->tutumu {coxdur} mes: long say5=23234543232;
9.  **(ulong)**--> minusdari pilusdarinin uzerine gelir ve buda tutumunu artirir.
10. **(short)** ---> tutumu {32767}
11. **(ushort)**---> minusdari pilusdarinin uzerine gelir ve buda tutumunu artirir.

**(sizeof())** ile tipin nece bayit yer tutduguna baxa bilerik.meselen sizeof(int)

## 1 **(dec>lon>doub>int>short>byte)**

**(mentiqi deyisken)**

1.  **(bool)** mentiqi deyiskendir yoxlanis edir dogru olub olmadigini yoxluyur ve geriye **(true)** **(false)** qaytarir.

---

**(zaman tipli deyisken)** 2. **(DateTime)** --> tarix ve zamani ozunde saxiliyir DataTIme vaxd=(**DataTime.Now.Year)** !!

---

                                                    ACAR SOZLER.

1.  **(checked)** ---> asmalarin qarsisini alir ,yeni mes : int maksiumum kecdikde xeberdarliq edir.
2.  **(break)** ---> Acar sozu qirmaq demekdir ve sert daxilinde emeliyati dayandirar ve koddan cixar.
3.  **(countine)**---> Acar sozdur davam et demekdir yeni break kimi emeliyati saxlamaz yalniz gormezden gelib davam eder.
4.  **(return)**---> geri donus geri qaytar demekdir ve gelen datani cagrilan metoda gonderer.
5.  **(out)** bu geri donus demekdir ve out a colde qiymet versekde olar vermesekde ama iceride mutleq qiymet vermeliyik.mes: TryParsda out var, orda oldugu kimi out-a qiymet vermirik sadece **int b;)** ve ya **(out int b)** kimi yaziriq , ama qiymet versek de olar.
6.  **(ref)** bu da geri donus demekdir lakin out dan ferqli olaraq ref-e colde mutleq qiymet verilmelidir.Iceride ise versekde olar vermesekde.Umumiyetle metotlarda geri donus **return)** ile olur .Bize methodun bir nece geri donusunu isdiyirikse onda **ref ve ya out)** dan isdifade edirik .**return)** yalniz bir deyer geri donus ede bilir.
7.  **(in)** bu da geri donusdur ferqi ise colde daxil edilen nedirse iceridede o olaraq qalir hec vaxd deyismir sehven deyisdirmek yeni bolmek azaltmaq fln etsek de deyismir nece methoda daxil olubsa ele de cixir.

---

                                                  Masivler ve Kolleksionlar.

1. **(int[] number=new int[3])** --> burada biz int vassivi yaratdiq .Massivler muxdelif tiplerden ola biler.Burada int[3] 3 reqemi masivvin nece elementli olmasini yeni nece int tipinden data saxlamasini gosderir.Burada 3 indeksli yeni 3 data saxlanilir.Lakin komputer sayarken 0 dan saymaga baslayir.Yeni (0,1,2) burda saysaq 3 data saxlamaq olar yeni 0 ci indeksde bir data ve digerlerinde eynisi.Massivlerin mehtodlari var ve biz bu methodlari istifade etmek ucun **Array)** klasindan isdifade edirik .Yeni massiv ucun hansi methodu cagirsaq Array. deyirik.BU methodlar asagidakilardir.

- **Array.Resize(ref massiv, a))** bu method ile biz masssivin nece elementli oldugunu bilmediyimiz halda isdifade ederek her defe massivin uzunlugunu artira bilerik ve ref massiv ve int a datalarini qebul edir.
- **(Array.IndexOf())**(indeks menasina gelir)--> mena olaraq eyni isi gorur ferqi odur ki massivlerde **Array.)** diye cagrilir stringlerde ise **data.)** cagrilir.
- **(Array.Reverse())** bu method masivlerin sonuncu ideksinden baslar sifirinci idekse atar sora axirdan 2ci ideksi birinci indekse atar ve s. mena olaraq eyni isi gorur ferqi odur ki massivlerde **Array.)** diye cagrilir stringlerde ise **data.)** cagrilir.
- **(Sort())**(menasi A-Z e duzmek,siralamaqdir)-> A-Z e siraliyir metinleri ve reqemleri ise kicikden boyuye. mena olaraq eyni isi gorur ferqi odur ki massivlerde **Array.)** diye cagrilir stringlerde ise **data.)** cagrilir.
- **Array.Clear())** bu method ile massivin butun indekslerindeki elementleri hamisini sifir edir.
- **Array.Exists(array, a => a == 10); int[] array = { 1, 5, 3, 4, 5, 4, 7, 8, 11, 10, 11, },)** bu method ise massivin icinde bize lazim olan eded var yoxsa yoxdur diye bize cavab verir ve geri donus ture ve false doner. Burada => boyukdur lamda isaresi adlanir ve yoxluyur ve cavab qaytarir , gorunduyu kimi biz burada massivde 10 reqemin olub olmamisini yoxlamisiq ve bize ture cavabini donecekdir.
- **Array.FindAll(array, a => a == 5))** bu method da Array.Exists ile eyni isi gorur yeni axdardigimizi tapir ferqli olaraq ture,false deyil tapdigi datanin ozunu geri doner.
- **Array.Copy(array,Newarray , 2, 5))** bu method ile bir massivdeki datani diger massive kopyaliya bilerik ve bunun ucun hansi massivden gotureceyikse onu qeyd edirik yeni massiv hansi olacaqsa onu qeyd edirik ve necenci indeksden baslasin kopyalamaga onu ve sonda nece element kopyalanacaq onu qeyd edirik.

---

2. **Random random = new Random())** (Random-tesadufu demekdir) Random bir klasdir ve bu klass bize tesadufu reqemler vere bilir ve methodu var onlar asagidakilardir.

- **int data=random.Next(1,10))** bu method bize texmini reqem verir.Maksium int qeder ola bilir ve her zaman biz araliq verende yeni burda 1 ile 10 arasinda tesadufu reqemler ver dedikde 1 daxil 10 ise daxil olmur 1 ile 9 daxil reqemler verir.Geriye int qaytarir.
- **double data=random.NextDouble())** bu method ile ise tesadufu 0 ve 1 arasinda reqemler verir yeni kesir ededler.Geriye double qaytarir.
- **byte data=random.NextBytes())** bu method bayit tutumu qeder tesadufu ededler verir.

---

3. **(ArrayList A1=new ArrayList())** kolleksionu ,Kolleksionlarin vasivlerden ferqi odur ki masivlerde nece data saxlanmasini biz secirik ve deyise bilmerik eyni massivde yeni 3 secmisik yuxarida onu deyise bilmirik, lakin kolleksionlarda ise ozu her data qebul etdikde ise bir elave yer ayrir ve novbeti datani gozleyir.ArrayLisdin metodlarina baxaq.

- **(Add())**(tek data elave et) metodu ArrayLisdin terkibine tek tek deyerler atmaq ucundur,yeni A1.Add("Samir"), A1.Add(121),
- **(AddRange)**( cox sayda elave et) metodu bir nece deyeri eyni anda ArrayList e atmaq ucundur.
- **(Remove())**-->(menasi sil)--> bu metot ile ArrayList icindeki isdenilen datani sile bilerik lakin datanin indeksini yox ozunu yazmaq lazimdi.Mes: A1.Remove("Samir") bu zaman gedib axdaracaq ve samir sozunu silecek.
- **(RemoveRange)**(menasi-> silinme araligi) bu ise indeksle isleyir filan indeksden basla 2 element sil. Mes: A1.RemoveRange(3,2) ucuncu indeksden basla 2 elementi silin.
- **(RemoveAt)**--> bu metot ise tek tek indeks silmek ucundur .Mes: A1.RemoveAt(2) yeni ikinci indeksi get sil.
- **(Reverse)** (menasi tersine cevir) bu metot ise sonuncu indeksde olan datani ilk indeksin uzerine getrir.Yeni sonuncu datadan baslayaraq ilk dataya kimi butun datalari sifirinci indeksden baslayaraq yazdirir.
- **(Sort())**(menasi A-Z e duzmek,siralamaqdir)-> A-Z e siraliyir metinleri ve reqemleri ise kicikden boyuye.
- **(Contains)**(menasi ehdiva edr umid edr ve yoxlayir) bu method ise daxil edilen datanin icerisinde bize lazim olan data varmi diye yoxlayir ve geriye bool qaytarir.
- **(IndexOf)**(indeks menasina gelir)--> bu method ise massiv ve ya kolleksionun daxilinde her hansi data var sa onun indeksini geri int olaraq donur.mes: **(int indeks= A1.IndexOf("samir");)** sozu varsa gedib onun indeksini tapib getrir.
- **(Clear)**(menasi butovlukde silmekdir)--> bu methoddan isdifade etsek butun elementleri silecek lakin capassite silinmiyecek ,yeni element ucun ayrilan yer silinmir lakin icerisi bos qalir.
- **(TrimToSize)** bu method ise yuxarida dediyimiz element silinsede onun ucun ayrilan yeri silinmir, lakin bu method ile sabit olaraq 4 elemet yeri saxlayir ve qalanini silir.
- **(ToArray)** bu metod koleksionlari opject masivvine atmaq ucundur.
- **(Resize(ref massiv,massiv.Lenght+1))** bu method ile massivin nece elementli oldugunu bilmirikse ardicil olaraq massivin uzunlugunu deyisdire bilerik, yeni bu method bize hemin massivi vermesede yenisini yaradir kohneni onun uzerine atir ve geri donur.Burad ref geri donusunden isdifade edilir ,yeni gedr massivin yenisini yaradir kohne massivi onun uzerine atir ve bize geri donderir.

4. **(Hashtable A1=new Hashtable())** bu kolleksion diger koleksionlardan ferqlenir .Ferqi odur ki bu iki object deyer teleb edir yeni biri key,digeri ise vouli deyer ,birinci acar soz daxil edilir digeri ise sabit bir deyer ,burada eyni acar soz ola bilmez,amma eyni valu deyer ola biler.Yuxarida qeyd olunan ArrayListin metodlari bu kolleksionlarda da isdifade edilir.

5. **(SortedList A1=new SortedList())** bu kolleksion da **(Hashtable)** kimi eynidir,iki object deyer isder ve isdediyi object den biri key(acar) soz olur lakin bir iki ferqi var ve o ferqe baxaq.Burada daxil olan acar sozler eyni tipden int,bayt,string ve s.olmalidir ve tekirarsiz olmalidir.Diger ferqide ondan ibaretdir ki acar sozleri stringdirse A-Z e duzer,reqemdirse kicikden boyuye duzer.

---

6. **(Stack A1=new Stack())** bu kolleksion bir object deyeri qebul edir.Bu koleksiona data eklemek ve bezi emeliyatlari asagidaki methodlarla edilir.

- **(A1.Push("SALAM"))** bu method ile Stack koleksionuna data atmaq(gondermek olar) mes: A1.Push("salam").
- **(A1.Pop())** bu method ile sonuncu daxil olan bir datani bir object e atar mes: **(object s=A1.Pop())** kimi.ve goturduyu Datani Stack den silir.
- **(A1.Peek())** bu method ise Stack den sonuncu datani goturer bir object e atar mes: **(object s=A1.Peek())** kimi.ve goturduyu datani Stack den silmir.

7. **(Queue Q1=new Queue())** bu koleksion da stack ile eynidir lakin stack de son giren ilk cixdigi halda Queue de ise ilk giren ilk cixir.Burada bir nece method var baxaq.

- **(Q1.Enqueue("samir"))** bu method Queue ye data elave etmek ucundur ve burda string olan samir sozunu dataya elave etdi.
- **(Q1.Dequeue())** bu method ile ilk daxil edilen datani goturmek olar lakin hemin datani Queue koleksionundan silecek. \***(Q1.Peek())** bu method ise Stack den sonuncu datani goturer bir object e atar mes: **(object s=A1.Peek())** kimi.ve goturduyu datani Stack den silmir.Bu method Queue koleksionunda da kecerlidi.

---

                                                              Metotlar ve Classlar

1. **(Metotlar)**----> metotlar kod yazarken bize cox komeklik edir yeni bir metot yazib bir hissesi eyni olan tapsiriqda yeniden cagirib isdifade ede bilerik.biz yeni metodlar yarada bilerik.Methodlar geriye deyer qaytaran ve geriye deyer qaytarmiyan olur.Geriye deyer qaytaran Methodlarda **return)** acar sozunden isdifade olunur.Methodlari Class-larin daxilinde yaradilir ve isdediyimiz qeder method yarada bilerik .Methodlar eyni adli olduqda gonderilen **datatype-lari)** ferqli olmalidir.Mes: Topla methodu **int number)** qebul edirse novbeti Topla methodu **int number,int a)** qebul etmelidir ve s.Deqiq desek method adlari eyni olduqda onlarin data qebul etmelerinin sayi ferqli ve ya daxil olan datanin tipleri ferqli ya da ki daxil olunan datalarin sayi eyni olsa yerleri ferqli olmalidir.

2. **(Public)**---> Public dedikde her kese gorunen olunacaq. Yeni biz basqa bir class da methoda public desek onda hemin method her yerde basqa class-lar da gorunen yeni cagira bilerik.
3. **(Private)**---> Private dedikde ise biz yalniz hemin klasin icindeki metodu cagira bilirik.Eger Public yazmamisiqsa bu avtomatik Private sayilir.
4. **(Protected)**--->
5. **(Internal)**--->
6. **(Internal Protected)**---->.

---

0.                                                                                                                                                                                              __Valu ve Reference types)__
    **Valu ve Reference)** tayip dedikde ne nezerde tutulduguna baxaq. **RAM)** yeni muvveqeti yaddas iki hisseye ayrilir **Stack ve Heap)** ve butun emeliyatlar bu ikisinde aparilir ve komputer sondurene qeder davam edir .Asagida hansi tiplerin **Stack ve Heap)** yaddasda saxlanildigini gosdermisem. **QEYD)** Valu tayiplar stack yaddasda saxlanilir, reference tayiplar ise Heap yaddasda saxlanilir. Valu tayiplar reference tayibdan her zaman suretli isleyir.
1.  **int, bayt,double ve s daxilinde reqem saxliya bildiklerimiz.)** -->bunlar her biri **valu tayipdir stack yaddasda saxlanilir)** ve reference tayiplardan suretli isleyir.
2.  **string,char, massivler mes:int[] ,classlar ve s.)** bunlar ise **Reference tayipdir ve Heap yaddasda saxlanilir)** ve valu tayiplardan asagi suretde isleyir.

---

0 **OOP Obyekt yonumlu proqramlasdirma)**

1. **enum)** enum ne demekdir ?.Enum ile limitli sayda olan secimleri yarada bilerik yeni hefdenin gunleri ilin aylarini ve ya sistemde menyulari ve s. yaratmaq olar.Enum susmaya gore **intden)** toreyib ve biz diger tiplerden yeni tam olan tiplerden torede bilerik mes: byte ,sbyte,short ve s. Her hansi tipden toretmek isdedikde **public enum Menu:byte)** qeyd etmek lazimdir . Enumlar da 1 ve bir nece secim bir secimden aslidirsa ele qurmaq olar ki hemin secimler isdediyimiz secimden asili olsun .Enum ozune mexsus xususiyyeti var bu xususuyyet 2-lik say sisteminde kodlardan aslidir. Enum-larda **( | )** toplama yeni iklikde olan kodlarin toplami **(&)** vurma emeliyyatidir buna genis sekilde misal cekek mes: tutaq ki bizde enum **(user=1, moderator=2, admin=user|moderator)** burada topluyanda indeksler toplanir ve eslinde user=1 de 1-in iklikde kodu **0001)** ve moderator=2 2-nin ikilikde kodu **0010)** toplanir. ve neticede 3-un ikilikde olan **0011)** alinir yeni admin 3 cu indeksdir ve admin diger iki user ve moderatorun isini gore biler. Bele hallardan isdifade etmek lazim olduqda indeksleri 2 usdu kimi gotururuk.Yeni 2 sifir, 2 usdu bir bele bele davam edir . Qeyd: enumun ozunun methodlari vardir ve onlar asagidakilardir.

- **( Enum.GetValues(typeof(enum adi yeni tipi)))** bu method ile enum daki butun secimleri cap ede bilerik.Lakin mutleq enumun tipini gosdermeliyik .Cunki menyu enami ola biler ilin aylari enami ola biler ve s.
- **(Enum.TryParse(typeof(Menu), Console.ReadLine(), true, out object result))** bu method ise enum tryparse methodudur yeni verilmis enumda bizim daxil etdiyimiz numune varmi diye yoxluyur varsa ture yoxdursa false qaytarir. burada biz ilk olaraq tryparse icinde enum tipini yazdiq sonra datani daxil etdik ve herifin boyuk olub olmamasini yoxladiq **ture** olduqda boyuk kicik herif ferq etmir isleyir **false** olduqda ise enum necedirse elede yazilmalidir ve sonda ise eger varsa daxil etdiyimiz data onu object uzerine alir.
- **(Enum.IsDefined(typeof(Menu), result))** bu method ile ise gelen datanin yeni resultun hemin enum daxilinde olub olmadigini yoxluya bilerik.
- **(Enum.GetName(typeof(Menu), 2))** bu method ile ise enum 2 ci indeksindeki hansi secim oldugunu tapa bilerik. Burda 2 yerine Menu.ad yazsaq gedib hemin datani getrir.
- **(Enum.GetUnderlyingType(typeof(Menu))** bu method ile ise biz enum hansi tipden torediyini oyrene bilerik.
-

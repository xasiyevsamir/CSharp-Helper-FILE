<b>C-Sharp</b>

<details><summary><b>1.Movzu:Bezi axdarislar..</b></summary><br/>
<a href="https://stackoverflow.com/questions/449887/sending-e-mail-using-c-sharp">1.C# E-mail gondermek yolu !</a><br>
<a href="https://survey.stackoverflow.co/2022/#technology">2.Burada proqram dillerinin ilden ile inkisafina baxa bilerik !</a><br>
<a href="https://app.diagrams.net/#G1mSYKv9CSSXe6tr4bshxjfb5QuU_hI0kP">3.Alqoritim qurmaq ucun isdifade edilen sexemleri bize verir !</a><br>
<a href="https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/">4.C# da acar sozlere baxmaq !</a><br>
<a href="http://www.java2s.com/Tutorial/CSharp/CatalogCSharp.htm">5.C# ders sayiti !</a><br>
<a href="http://extraconversion.com/base-number">6.Say sisteminin cevrilisi!</a></details>
<b>________________________________________________________________________________________________________________</b>

<details><summary><b>2.Movzu:Cmd ---- emirleri.</b></summary><br/>
1.<b>cd bosluq enter</b> oldugun fayila aparir.<br/> 2.<b>cd bosluq ..</b> bir fayil geri cixir.<br/> 3.<b>cd bosluq fayilin adi</b> adi qeyd edilen fayila kecit edir.<br/> 4.<b>cls</b>acilmis butun melumatlari temizleyir.<br/> 5.<b>dir</b> fayilin icine daxil olur.<br/> 6.<b>mkdir</b> yeni fayil yaradir.<br/> 7.<b>prompt $$</b> yeni setri dollar isaresi ile basladir.<br/> 8.<b>dotnet run</b> emri ise kodu ise salir.<br/> 9.<b>code .</b> visual studio coda kecid emridir.<br/> 10.<b>echo "" >>.gitignore</b> -- burada yeni cmd ekraninda .gitignore fayili yarada bilerik bu emirle.<br/> 11.<b>rundll32.exe user32.dll,LockWorkStation</b> komputeri cmd ile kilidlemek ucun olan emir.<br/>
<b><i>(Solutions and project)</i></b><br/>
QEYD. Cmd --qara ekrandan istifade ederek biz yeni solutions ve preject yarada bilerik.Bunun ucun bir nece etablari kecmeliyik.Evvelce yeni fayil yaratmaliyiq. Fayili ise mkdir emri ile yarada bilerik bunu yuxarida qeyd etmisem . Yeni Solutions ve project yaradaq..

1.  ci mkdir emri ile fayil yaradiriq.
2.  ci dotnet new sln --name (solutions adi meselen: code)
3.  cu project yaratmaq ucun--> dotnet new console --framework net6.0 --use-program-main emrinden istifade edirik .Burada isdesek net6.0 fersiyani istesek deyise bilerik.
4.  cu ise solutions ve projecti elaqelendiririk-->> dotnet sln (solution adi yeni:code) add 5.project\csproj sonlugu ile biten fayil ve enter.<br/>

<a href="https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-sln"><b>Axdaris yerine dotnet new sln --name MySolution</b>-yazdiqda asagidaki sekili tapmaq lazimdir.</a><br/>
<i>Sayita daxil olduqdan sonra bu (dotnet new sln --name MySolution) yazilisi tapib isdifade ede bilerik. </i><br/>

<p>
<img src="image\cs35.png" alt="Sekil silinib" title="Yeni solutions yaratmaq."/>
</p><br/>
<p> Axdaris yerine dotnet create new console app project yazzsaq yeni project yaratmaq ucun asagidaki sekil gelecekdir.
<img src="image\cs36.png" alt="Sekil silinib" title="Yeni project yaratmaq."/>
</p><br/> 14.<i> Yaratdigimiz solutions ve projecs elaqelendirmek ucun google axdarisa (dotnet add project solutions create) sayita daxil olduqdan sonra ise qarsimiza cixan (dotnet sln solution.sln add --solution-folder foo1\foo2\foo3 bar.csproj) yazilisdan istifade ederek elaqeni yaradiriq.</i><br/>
<p>
<img src="image\cs37.png" alt="Sekil silinib" title="Yeni solutions yaratmaq."/>
</p><br/>
</details>
<b>________________________________________________________________________________________________________________</b>

<details><summary><b>3.Movzu:GITHUB ---->> Yaratmaq.</b></summary><br/>
    QEYD. Github yaratmaq ucun profile daxil olub qeydiyatdan kecirik, daha sonra ise bir nece emirden isdifade ederek yeni repositories yarada bilerik .
    …or create a new repository on the command line

1.  git clone (linkimizi buraya yerlesdiririk).<br/>
2.  echo "dirnaq arasina ne isdesez yaza bilersiz">> README.md -------->>(readme fayili yaratmaq ucundur.)<br/>
3.  git init ---------->>>(git pafqasi yaratmaq ucundur )<br/>
3.  git add README.md ------->>(readmi fayilini testiq etmek ucun)<br/>
4.  git commit -m "first commit" -----(deyisikliye ad vermek ucun)<br/>
6. git branch -M main<br/>
6. git remote add origin https://github.com/xasiyevRandom method./taskkkk.git<br/>
7. git push -u origin main<br/>
8. Eger Github-a ilk defe qosuluruqsa onda asgidaki emirleri etmeliyik ardicilliqla.<br/>
<b>a.git</b> config --global user.name "xasiyevsamir"<br/>
<b>b.git</b> config --global user.email "qeydiyyatdan kecdiyimiz email."<br/>
<b>c.git</b> config --global user.password "qeydiyyatdan kecdikde yaratdigimiz password."<br/>
<b>d.git</b> config user.name "xasiyevsamir"<br/>
<b>e.git</b> config user.email "qeydiyyatdan kecdiyimiz email."<br/>
<b>f.git</b> config user.password "qeydiyyatdan kecdikde yaratdigimiz password."<br/>
Bu emirlerden istifade etmekle yeni repositories yarada bilerik!!!
</details>
<b>________________________________________________________________________________________________________________</b>

<details><summary><b>4.Movzu:Math sinifi.</b></summary><br/><br/>

1.<b>(Math.Pow(10,2))</b> ---> burada 10 kvadratini yazmisiq yeni (10\*10) .Bunu isdediyimiz kimi yaza bilerik yeni kub ve s. Meselen: Math.Pow(10,3) , (10,4).<br/>
2.<b>(Math.Log10)</b>---> ededin nece reqemli oldugunu tapir amma neticenin usdune mutleq 1 gelirik.<br/> 
3.<b>(Math.sqrt)</b>----> koku tapmaq ucun istifada edilir.<br/>
4.<b>(Math.Round)</b>---> riyazi yuvarlasdirmaq ucun istifade edilir.<br/> 
5.<b>(Math.Floor)</b>---> asagi yuvarlasdirmaq,yeni tam hisseye kimi atir.<br/> 
6.<b>(Math.Ceiling)</b>---> yuxari yuvarlasdirmaq.<br/> 
7.<b>(Math.PI)</b>---> pi deyeridir .hesabliyada isdifade ede bilerik.<br/> 
8.<b>(Math.Abs)</b>--->Modulu tapmaq ucundur.<br/> 
9.<b>(Math.Max)</b>--> ededin maksimumun tapir.<br/> 
10.<b>(Math.Min)</b>--> ededin minumumun tapir.<br/>

</details>
<b>________________________________________________________________________________________________________________</b>

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
<i><b>dec>lon>doub>int>short>byte</b>.Reqem tipli datatiplerin tutumuna gore muqayisesi.</i>
<p>
<i>Reqem tipleri asagidakilardir.</i>
 <img src="image\cs44.png"  alt="Sekil silinib" title="Reqem tipleri"/>
</p>
 </details>
<details><summary><b>Refarence</b></summary><br/>Metin tipli datalari saxlamaq ucundur Mes:<b>string, char, class,Method,Massiv ve s.</b><br/>
<b><i>1.Convert.ToInt32</i></b>----> <i>Butun tiplerden cevirme apara bilir Parse dan ferqli olaraq.</i><br/>
<b><i>2.Tipin adi.Parse</i></b> ----> </i>Yalniz reqem tipli stringleri cevire bilir. mes: "123". Yeni string olmayan neyise cevire bilmir</i>.<br/>
<b><i>3.Tipin adi.TryParse(date, out Tipin adi a)</b></i>---> <i>bu cevirme digerlerinden ferqlenir yeni geriye bool (ture,false) qaytarir yeni cevrile bilir ya cevrile bilmir .</i></details>
</details>
<b>________________________________________________________________________________________________________________</b>

<details><summary><b>6.Movzu: Operatorlar.</b></summary>
Operatorlar bir nece yere ayrilirlar bunlar asagidakilardir.
<p>
 <img src="image\cs4.png" width="650" height="400" alt="Sekil silinib" title="Operatorlar."/>
 </p><br/>

 <details><summary><p><b>Sade operatorlar--></b>
 <img src="image\cs6.png" width="300"  alt="Sekil silinib" title=" Sade Operatorlar."/>
 </p></summary>
 <p>
 <img src="image\cs38.png"  alt="Sekil silinib" title=" Umumi sade emelliyat."/>
 </p>
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
<i><b>Sizeof(int)-</b>DateType nece byte yer tutdugunu bildirir.</i><br/>
 <img src="image\cs39.png" width="300"  alt="Sekil silinib" title="Sizeof operatorlar"/>
 <img src="image\cs40.png" width="300"  alt="Sekil silinib" title="Netice"/><br/>
 <i><b>typeof(int)-</b>Datanin tayipini yoxlamaq ucundur.</i><br/>
 <img src="image\cs41.png" width="300"  alt="Sekil silinib" title="typeof operatorlar"/>
 <img src="image\cs42.png" width="300"  alt="Sekil silinib" title="Netice"/><br/>
 <i><b>?-null operatoru</b>-Reqem tipli datalar hec vaxd null ola bilmez ama biz mecbur ede bilerik ki o null olsun ve olanda serte girsin.</i><br/>
 <img src="image\cs43.png" width="300"  alt="Sekil silinib" title="?-null operatorlar"/>
 </p></summary>
</details></details>
<b>________________________________________________________________________________________________________________</b>

<details><summary><b>7.Movzu:Console codlari.</b></summary>
1.<b>Console.Write();</b> ---> bu kod vasitesi ile biz ekranda her hansi bir melumati cap(yazdira) ede bilerik.Yazini cap edir ve nobeti yazini cap etdirende qarsisina alir yeni Console.Write("Random method.")
Console.Write("xasiyev") netice---> Random method.xasiyev olacaqdir. oldugu setirde qalir.<br/> 2.<b>Console.WriteLine();</b> ---> bu yuxaridaki emirle eynidir lakin bu emirde eyni setirde deyil novbeti setire kecid olunur.<b>Netice----> Random method. </b> --->> xasiyev olacaqdir.<br/> 5.<b>Console.Redkey();</b> yazilmis her hansi melumati oxumaq ucun ekranda gozluyer bir melumat daxil etdikde ise baglanar.<br/> 6.<b>var key=Console.ReadKey(), (key.Key==ConsoleKey.Enter)</b>bu yazilisla biz isdifadecinin hasi duymeni sabasini izah ede bilerik.<br/> 7.<b>Console.ReadLine();</b> istifadeciden melumat almaq ucun ekranda gozluyer melumati daxil edib enteri basdiqada melumati bize getrir.<br/> 8.<b>Console.CursorTop()</b> bu method ise kursorun hal hazirki durdugu yeri gosderir.<br/> 9.<b>Console.SetCursorPosition(0,Console.CursorTop)</b> bu method ile cursoru harda durmagindan asli olmayaraq hemin setrin ilk baslangicina getrir.burada sifir o demekdirki hemin setr olsun Console.CursorTop ise hemin setirde kursorun hal hazirki durdugu yer.<br/> 10.<b>Console.WindowWidth</b> bu ise console ekrani boyunca demekdir.<br/>
</details>
<b>________________________________________________________________________________________________________________</b>

<details><summary><b>8.Movzu:Datetype</b></summary>
<b>Datetype 4 yere ayrilir .<i>(Metin, reqem, mentiqi, zaman......).....</i><a href="https://www.w3schools.com/cs/cs_data_types.php">Datetype baxin --></a><br/></b><br/>
<details><summary><b>Metin tipli Datetipe.</b></summary>
1.<b>string</b> --> Her hansi bir metin tipli melumatlari saxlamaq ucun istifade edilir.Mes: <b>string name ="Random method.", "Random method. 123","1234".</b> stringin uzunlugu <b>name.Lenght</b> propertisi ile tapilir, bu zaman bosluqlarda sayilir.mes: <i>"Random method. 123" de uzunluq</i><b> 9 dur.</b><br/>
</details>.

<b></b><br/> 2.<b>(Char)</b> --> bu tipde string tipi kimi eynidir lakin bir metin yeni A,B daxil etdikde istifade edrik eyni zamanda string de istifade etmek dogrudur .<b>string ve char methodlari</b><br/> -<b>(Join())</b> (qosmaq,birlesdirmek menasini verir) bu method ile metinleri bir birine isdediyimiz sekilde birlesdire bilerik. Mes: <b>string name1=string.Join("*",name)</b> -->Netice:Random method.*Random method. 123*1234 string[] ve char[] massivine ayitdir.<br/> -<b>(ToCharArray())</b> bu method ile stringde olan metni herif herif Char[] masivine yazdira bilerik.<br/> -<b>(Array.Reverse())</b> bu method masivlerin sonuncu ideksinden baslar sifirinci idekse atar sora axirdan 2ci ideksi birinci indekse atar ve s.<br/> -<b>(Data.PadLeft(6,'0'))</b> bu method sola isdenilen simvolu ve ya bolsulugu atmaq ucundur.Burda sola 6 sifir atdiq.<br/> -<b>(Data.PadRight(6,'0'))</b> bu method saga isdelinen simvolu ve ya boslugu atmaq ucundur.Burda saga 6 sifir atdiq.<br/> -<b>(Data.ToUpper())</b> bu method gelen ve ya elimizde olan datani hamisini boyuk heriflere cevirir.<br/> -<b>(Data.ToLower())</b> bu method gelen ve ya elimizde olan datanin hamisini kicik herife cevirir.<br/> -<b>(Data.Substring(0,4))</b> bu method datada necenci indeksden deyrikse ordan basliyir ve nece element gotur deyirikse o qederini gotrur, mes:burda 0-ci indeksden basliyir ve 4 element gotrur.<br/> -<b>(Data.IndexOf)</b>(indeks menasina gelir)--> bu method ise massiv ve ya kolleksionun daxilinde her hansi data var sa onun indeksini geri int olaraq donur.mes:<b>(int indeks= A1.IndexOf("Random method.");)</b> sozu varsa gedib onun indeksini tapib getrir.Amma qeyd edek ki bu method qarsisina cixan birinci elementin indeksini gotrur ve emeliyyati bitrir ,yeni orda bir nece Random method. sozu olsa ilk qarsisina cixani goturecekdi. Qeyd: edeki eger axdardigimiz soz orada yoxdursa int olaraq geri donus <b>-1</b> olacaqdir .Cunki sifir ozu mumkun indeksdir.<br/> -<b>(Data.Replace("Random method.","valeh"))</b> bu method ise metinde olan isdenilen datani basqa data ile deyismeye imkan verir.Burada Random method. sozunu metinden cixarib valeh sozunu elave etdik.<br/> -<b>(Data.Trim())</b> bu method sonda ve evvelde ki bosluqlari ve ya <b>Data.Trim('*')</b> sonu ve evelindeki ulduz ve ya diger simvollar olarsa olarida silecek.<br/> -<b>(Data.TrimStart())</b> bu methodda trimden toreyib ve ondan ferqli olaraq datanin evvelindeki boslugu ve ya simvolu silir.<br/> -<b>(Data.TrimEnd())</b> bu methodda trimden toreyib ve ondan ferqli olaraq datanin sonundaki boslugu ve ya simvollari silir.<br/> -<b>(Data.LastIndexOf())</b> IndexOf ile eyni isi gorur sadece axdarisa sondan baslayir ve ilk dogru melumati tapan kimi onun indeksini int olaraq geri donur ve emeliyyatii bitirir.Qeyd: LastIndexOf sondan basliyaraq yoxlayir ve ilk uygun datanin ik elementinin indeksini geri qaytarir mes:(Random method.) axdarsaq s- herifinin indeksini bize geri donus edecek.<br/> -<b>(Data.Insert(1,"salam"))</b> bu method ile isdenilen indekse isdediyimiz datani elave ede bilerik.burada 1ci indekse salam sozunu elave etdik.<br/> -<b>(Data.Remove(1,2))</b> bu method ile isdenilen indeksden baslayib sile bilerik eyni zamanda silme araliginida biz veririk meselen biz burda 1 ci indeksden basla 2 element sil demisik.<br/> -<b>string s=new string('\*',3)</b> --> bu o demekdir ki 3 dene <b>\*\*\*</b> yazdiracaq.Amma method deyil string obyektidir.<br/> 4.<b>StringBuilder sb = new StringBuilder();</b> bu da bir sinifdir ve metinlerle isleyir ve string tiplerinden daha cox suretlidi kolleksiondur demek olar ki. ve onun metodlari asagidakilardir.<br/>

-<br>sb.Append("Random method.")</b> bu methodun komeyi ile datani stringbuilder e elave etmek olar.Bu methodun 25 overladi var ve demek olarki butun tipleri stringbuilder e elave etmek olur.<br/> -<b>sb.AppendLine()</b> bu method ise datani elave edir ve novbeti datani bir asagi setre elave edir.BU methodun 3 overladi var yeni bezi tipleri stringe cevrib gondermeliyik.<br/> -<b>sb.AppendFormat("{0}{1}",2,3)</b> bu method ile stringleri datalara uygun yaza bilerik.Burada 0 ci indekse 2 1ci indekse ise 3 atdi.<br/> -<b>sb.AppendJoin()</b> bu method ise stringlerde oldugu kimi burdada datalari bir birine isdediyimiz kimi birlesdirir.<br/> -<b>sb.Clear()</b> bu method ile datani sile bilerik.<br/> -<b>sb.Length</b> bu ise method deyil sadece uzunlugunu tapa bilerik stringbuildin.<br/> -<b>sb.Capacity</b> bu da method deyil sadece ayirdigi yerdir .<br/>

5.<b>(object)</b> bu tip uzerine butun tipleri ala bilir yeni inti, double, string ve s.Lakin uzerine aldigi tipi o tip kimi de cixarmalidir. int a=10; object b=a;(qutulama boxing) int c=(int)b;(qutudan cixartma unboxing). bunlari intin dauble kecidi ve double
inte kecidi ile qarisdirmaq olma . Cox oxsasada coxda ferqlidirler. object tipin eslinde xaricden nese gelerse saxlanilmasi uc isdifade oluna biler. Cunki biz xaricden hansi tipin geleceyini bilmirik .<br/> 6.<b>(var)</b>---> Var sagina baxaraq datanin hansi tipden oldugunu anliyir. var tip deyil .<br/> 7.<b>(dynamic)</b> tipdir ve onun icindeki datalara baxa ve uzerinde emeliyat apara bilerik.sadece sehv nese daxil etdikde error bizden gizledir.<br/> 8.<b>(as)</b> bu kivord obyekte geden tipin hansi tip oldugunu bilmek ucun ve as kivordu geriye null qaytarir. Null ola bileceyini demek isdiyirikse ? isaresinden istifade edirik mes: byte? a=b as byte?.<br/> 9.<b>(is)</b> bu kivord de eyni ile as benzeyir yeni opject den gelen bayitdirmi int c =10; object v=c; (v is byte) ve ya (v is int)<br/>

<p><img src="image\cs46.png" height="500px"  alt="Sekil silinib" title="Interpolisin yazilisi."/></p>
</details>
<b>________________________________________________________________________________________________________________</b>
<details><summary><b>9.Const--Deyismez.</b></summary>
<p><img src="image\cs45.png" width="300"  alt="Sekil silinib" title="Const-Sabit."/></p>
</details>
<b>________________________________________________________________________________________________________________</b>
<details><summary><b>10.Massivler.</b></summary>
 <i>
 <b>(int[] number=new int[3])</b> --> burada biz int vassivi yaratdiq .Massivler muxdelif tiplerden ola biler.Burada int[3] 3 reqemi masivvin nece elementli olmasini yeni nece int tipinden data saxlamasini gosderir.Burada 3 indeksli yeni 3 data saxlanilir.Lakin komputer sayarken 0 dan saymaga baslayir.Yeni (0,1,2) burda saysaq 3 data saxlamaq olar yeni 0 ci indeksde bir data ve digerlerinde eynisi.Massivlerin mehtodlari var ve biz bu methodlari istifade etmek ucun <b>Array.</b> klasindan isdifade edirik .Yeni massiv ucun hansi methodu cagirsaq Array. deyirik.BU methodlar asagidakilardir.
 </i>
<p><img src="image\cs47.png"   alt="Sekil silinib" title="1 olculu Massivler."/></p>
<a href="https://learn.microsoft.com/en-us/dotnet/csharp/programming-guide/arrays/multidimensional-arrays">1.Cox olculu massiv !</a><br/>
<b>Iki olculu massiv</b>.<i>Yuxaridaki sekildeki massiv 1 olculu massivdir 2 olculu massiv ise asagidakidir.</i><br/>
<p><img src="image\cs48.png"   alt="Sekil silinib" title="2 olculu Massivler."/></p>
<b>(int[] number=new int[3])</b> --> burada biz int vassivi yaratdiq .Massivler muxdelif tiplerden ola biler.Burada int[3] 3 reqemi masivvin nece elementli olmasini yeni nece int tipinden data saxlamasini gosderir.<br/>Burada 3 indeksli yeni 3 data saxlanilir.Lakin komputer sayarken 0 dan saymaga baslayir.Yeni (0,1,2) burda saysaq 3 data saxlamaq olar yeni 0 ci indeksde bir data ve digerlerinde eynisi.<br/>Massivlerin mehtodlari var ve biz bu methodlari istifade etmek ucun <b>Array)</b> klasindan isdifade edirik .Yeni massiv ucun hansi methodu cagirsaq Array. deyirik.BU methodlar asagidakilardir.<br/>
<b>1.Array.Resize(ref massiv, a))</b> bu method ile biz masssivin nece elementli oldugunu bilmediyimiz halda isdifade ederek her defe massivin uzunlugunu artira bilerik ve ref massiv ve int a datalarini qebul edir.<br/>
<b>2.Array.IndexOf()</b>(indeks menasina gelir)--> mena olaraq eyni isi gorur ferqi odur ki massivlerde <b>Array.)</b> diye cagrilir stringlerde ise <b>data.)</b> cagrilir.<br/>
<b>3.Array.Reverse()</b> bu method masivlerin sonuncu ideksinden baslar sifirinci idekse atar sora axirdan 2ci ideksi birinci indekse atar ve s. mena olaraq eyni isi gorur ferqi odur ki massivlerde <b>Array.)</b> diye cagrilir stringlerde ise <b>data.)</b> cagrilir.<br/>
<b>4.Sort()</b>(menasi A-Z e duzmek,siralamaqdir)-> A-Z e siraliyir metinleri ve reqemleri ise kicikden boyuye. mena olaraq eyni isi gorur ferqi odur ki massivlerde <b>4.Array.</b> diye cagrilir stringlerde ise <b>data.)</b> cagrilir.<br/>
<b>5.Array.Clear())</b> bu method ile massivin butun indekslerindeki elementleri hamisini sifir edir.<br/>
<b>6.Array.Exists(array, a => a == 10); int[] array = { 1, 5, 3, 4, 5, 4, 7, 8, 11, 10, 11, },)</b> bu method ise massivin icinde bize lazim olan eded var yoxsa yoxdur diye bize cavab verir ve geri donus ture ve false doner. Burada => boyukdur lamda isaresi adlanir ve yoxluyur ve cavab qaytarir , gorunduyu kimi biz burada massivde 10 reqemin olub olmamisini yoxlamisiq ve bize ture cavabini donecekdir.<br/>
<b>7.Array.FindAll(array, a => a == 5))</b> bu method da Array.Exists ile eyni isi gorur yeni axdardigimizi tapir ferqli olaraq ture,false deyil tapdigi datanin ozunu geri doner.<br/>
<b>8.Array.Copy(array,Newarray , 2, 5))</b> bu method ile bir massivdeki datani diger massive kopyaliya bilerik ve bunun ucun hansi massivden gotureceyikse onu qeyd edirik yeni massiv hansi olacaqsa onu qeyd edirik ve necenci indeksden baslasin kopyalamaga onu ve sonda nece element kopyalanacaq onu qeyd edirik.<br/>
</details>
<b>________________________________________________________________________________________________________________</b>
<details><summary><b>11. If ,else if , else, switch.</b></summary>
<i>Serti skopkalar--Bir nece sertin eyni anda yoxlanmasini isdeyirikse bir nece <b>if</b> yazmaliyiq ki butun sertlere daxil olsun eks halda ise bir <b>if</b> ve bir nece <b> else if</b> yazmaliyiq bu halda yalniz dogru serte daxil olacaq yeni butun sertleri bir bir yoxlamiyacaq . <b>else</b> ise ifin eksini bildirir. If olmadan else if ve ya else yazmaq olmaz.<b>if</b> -den sonra bir nece if ve ya else if yaza bilerik.</i><br/>
<p><img src="image\cs49.png"   alt="Sekil silinib" title="If ,else if , else,."/></p>
<i>switch skopqasi</i>
<p><img src="image\cs50.png"  width="350"   alt="Sekil silinib" title="switch."/></p>
<p><img src="image\cs51.png"  width="350"   alt="Sekil silinib" title="switch ferqli case olduqda ve eyni isi gordukde."/></p>

</details>
<b>________________________________________________________________________________________________________________</b>
<details><summary><b>12.Loops-Dovurler.</b></summary>
<i>Dovurlerin bir nece novleri var bunlara misal olaraq asagidakilari gosdere bilerik.
</i>
<ul type="square">
  <li><b>for loop;</b></li>
  <li><b>while loop;</b></li>
  <li><b>do while loop;</b></li>
  <li><b>foreach loop;</b></li>
</ul>
<i><b>for loop</b>.Asagidaki sekilde sertin yerine yeni for ne qeder dovur etmelidir yerine <b>true</b> yazdiqda sonsuz dovre dusecek.
</i><br/>
<p><img src="image\cs52.png"    alt="Sekil silinib" title="for loop"/></p>
<i><b>break-(qirmaq) ve contiune-(davam etmek)</b>.Acar sozlerdir ve dovur olduqda dovru isdediyimiz zaman qira ve ya davam etdire bilerik.Bu acar sozleri butun loop-larda isdifade ede bilerik.</i>
<p><img src="image\cs53.png"    alt="Sekil silinib" title="Acar sozler."/></p>
<i><b>while loop</b>. While dovru true,false qebul edir yeni ture oldugu muddetce dovur davam edecekdir.Ne zaman dovur false olarsa o zaman dovur bitecekdir.</i><br/>
<p><img src="image\cs54.png"    alt="Sekil silinib" title="While loop."/></p>
<i><b>do While loop</b>. Bu loop da While loop ile eynidir yalniz bir ferqi odur ki en azi emeliyyata bir defe girir sonra serti yoxlayir yeni sert sonda yoxlanilir true ise dovur davam edir false olduqda ise dovur bitir.</i><br/>
<p><img src="image\cs55.png"    alt="Sekil silinib" title="do While loop."/></p>
<i><b>foreach loop</b>. Bu dovur indeksli olan datalarda isdifade edile biler meselen massivler ve s.</i><br/>
<p><img src="image\cs56.png"    alt="Sekil silinib" title="foreach loop."/></p>
<i><b>goto l1</b>.Bu dovur ise yuxaridakilardan ferqli olaraq biz sert dogru olduqda yeniden kodu oxmagini yeni yeniden baslamasini isdiye bilerik.Asagidaki sekilde daha yaxsi izah edilib. Diger dovur ise method-un icinde ozunu cagirmaqdi asagidaki sekilde her iki mmisal gosterilib.</i><br/>
<p><img src="image\cs57.png"    alt="Sekil silinib" title="goto l1."/></p>
<p><img src="image\cs58.png"    alt="Sekil silinib" title="Method ile dovur."/></p>

</details>
<b>________________________________________________________________________________________________________________</b>
<details><summary><b>13.Methodlar.</b></summary>
<i><b>(Methodlar)</b>----> methodlar kod yazarken bize cox komeklik edir yeni bir method yazib bir hissesi eyni olan tapsiriqda yeniden cagirib isdifade ede bilerik.Biz yeni metodlar yarada bilerik.Methodlar geriye deyer qaytaran ve geriye deyer qaytarmiyan olur.Geriye deyer qaytaran methodlarda <b>return)</b> acar sozunden isdifade olunur.Methodlari Class-larin daxilinde yaradilir ve isdediyimiz qeder method yarada bilerik .Methodlar eyni adli olduqda gonderilen <b>datatype-lari)</b> ferqli olmalidir.Mes: Topla methodu <b>int number)</b> qebul edirse novbeti Topla methodu <b>int number,int a)</b> qebul etmelidir ve s.Deqiq desek method adlari eyni olduqda onlarin data qebul etmelerinin sayi ferqli ve ya daxil olan datanin tipleri ferqli ya da ki daxil olunan datalarin sayi eyni olsa yerleri ferqli olmalidir.Geri deyer qaytarmayan methodlari ise <b>void</b>--> adlanir yeni hecne deyer qaytarmir.</i><br/>
<i><b>1.Geri deyer qaytarmayan method yeni return olmayan method.</b></i><br/>
<p><img src="image\cs59.png"    alt="Sekil silinib" title="return olmayan method."/></p>
<i><b>2.Geri deyer qaytaran method yeni return olan method.Sekilde gorunduyu kimi ArrayList geri donus olunur.</b></i><br/>
<p><img src="image\cs60.png"    alt="Sekil silinib" title="return olan method."/></p>
<i><b>2.Geri deyer qaytaran ve deyer alan method yeni return olan deyer teleb eden method.Sekilde gorunduyu kimi bir deyer daxil edilir ArrayList geri donus olunur.</b></i><br/>
<p><img src="image\cs61.png"    alt="Sekil silinib" title="return olan deyer alan method."/></p>
</details>
<b>________________________________________________________________________________________________________________</b>

<details><summary><b>14.DIL MEDENIYETI.</b></summary>
1.  <b>(Console.OutputEncoding = Encoding.Unicode;)</b> biz elimizde olan datani cole yeni fronta gondererken bu codu yazmaliyiq ki bezi herifleri tanimir ve onlarida tanisin.<br/>
2.  <b>(Console.InputEncoding = Encoding.Unicode;)</b> biz colde olan datani yeni frontda olan datani iceri back e gonderirikse bu codu yazmaliyiq ki duzgun olaraq daxil etsin.<br/>
3.  <b>(CultureInfo ce = new CultureInfo("az-Latn-AZ"); Thread.CurrentThread.CurrentCulture = ce;)</b> bunu yazdiqda ise proqram sirf azerbaycan dilinde isleyecek <b>Culture-(medeniyet), Thread-(Movzu), Current-(Cari, indiki), --menasina gelir)</b>.<br/>
4.  <b>(System.Threading.Thread.Sleep(1000);)</b> bu ise gozlemedi yeni saniye seklinde 1000-1 saniyedir. <b>Sleep()-yatmaq ,qalmaq, gozlemek, menasina gelir)</b>.<br/>
5.  <b>Stopwatch stopwatch = new Stopwatch();)</b> bu da bir sinifdir lakin bu melumat saxlamaq ucun deyil sadece yazdigimiz codlarin nece saniye erzinde isliyib basa catdigini bilerik. Bunun da methodlari vardir.<br/>
- <b>stopwatch.Start())</b> bu methodu ise baslamamisdan evvel ise salmaq ucundur.<br/>
- <b>stopwatch.Stop())</b> bu method ise is bitenden sonra isdifade edilir ki it bitene qeder olcsun.
</details>
<b>________________________________________________________________________________________________________________</b>
<!-- RANDOM -->
<details><summary><b>15.Random</b></summary>
<i><b>Random classi texmini reqemler goturmek ucun isdifade edilir.Onun bir nece methodu vardir ve onlar asagidakilardir.</b></i><br/>
<i>1->rnd.Next()</i><br/>
<i>2->rnd.Next(<b>int.maxvalue</b>)</i><br/>
<i>3->rnd.Next(<b>int.minvalue, int.maxvalue</b>)</i><br/>
<i>4->rnd.NextDouble()</i><br/>
<i>5->rnd.NextInt64()</i><br/>
<i>6->rnd.NextInt64(<b>long maxvalue</b>)</i><br/>
<i>7->rnd.NextInt64(<b>long minvalue, long maxvalue</b>)</i><br/>
<i>8->rnd.NextBytes(<b>massiv</b>);</i><br/>
<i>9->rnd.NextSingle()</i><br/><br/><br/>
<p>
<b>1->rnd.Next() </b>--<i>Bu method ile biz 0-dan integer-in maximumu qeder yeni (int.maxvalue) qeder texmini bir reqem verir.</i><br/>
<img src="./image/cs64.png" width="400px" height="300px"    alt="Sekil silinib" title="Random metho."/>
 <img src="./image/cs65.png" width="400px" height="300px"   alt="Sekil silinib" title="Random method."/><br/><br/><br/>
<b>2->rnd.Next(15) </b>--<i>Bu method ile biz 0-dan 15-ə qeder texmini bir reqem verir.Burada 0 daxildir 15 ise yox.</i><br/>
<img src="./image/cs66.png" width="400px" height="300px"    alt="Sekil silinib" title="Random method."/>
 <img src="./image/cs67.png" width="400px" height="300px"   alt="Sekil silinib" title="Random method."/><br/><br/><br/>
<b>3->rnd.Next(5,21) </b>--<i>Bu method ile biz 5-dan 21-ə qeder texmini bir reqem verir.Burada 5 daxildir 21 ise yox.Yeni biz elde etdiyimiz texmini reqemlerin hansi araliqda olmasini ozumuz teyin ede bilerik.</i><br/>
<img src="./image/cs68.png" width="400px" height="300px"    alt="Sekil silinib" title="Random method."/>
 <img src="./image/cs69.png" width="400px" height="300px"   alt="Sekil silinib" title="Random method."/><br/><br/><br/>
 <b>4->rnd.NextDouble() </b>--<i>Bu method ile biz 0-dan 1-ə qeder texmini bir reqem verir.Burada 1 daxil deyil.</i><br/>
<img src="./image/cs70.png" width="400px" height="300px"    alt="Sekil silinib" title="Random method."/>
 <img src="./image/cs71.png" width="400px" height="300px"   alt="Sekil silinib" title="Random method."/><br/><br/><br/>
 <b>5->,6->,7-> rnd.NextInt64() </b>--<i>Bu method ile biz 0-dan long.maxvalu qeder texmini bir reqem verir.Boyuk reqemler saxlamaq ucundur.Integer kimi 3 overloads var yeni elave yuklenmesi.</i><br/>
<img src="./image/cs72.png" width="400px" height="300px"    alt="Sekil silinib" title="Random method."/>
 <img src="./image/cs73.png" width="400px" height="300px"   alt="Sekil silinib" title="Random method."/><br/><br/><br/>
 <b>8-> rnd.NextBytes(data) </b>--<i>Bu method ile biz byte massivini texmini 0 ile 256 arasinda reqemler ile doldura bilerik.Yalniz byte massivi ucun kecerlidir.</i><br/>
<img src="./image/cs74.png" width="400px" height="300px"    alt="Sekil silinib" title="Random method."/>
 <img src="./image/cs75.png" width="400px" height="300px"   alt="Sekil silinib" title="Random method."/><br/><br/><br/>
 <b>9-> rnd.NextSingle() </b>--<i>Bu method ile bize float deyerini geri qaytarir.</i><br/>
<img src="./image/cs76.png" width="400px" height="300px"    alt="Sekil silinib" title="Random method."/>
 <img src="./image/cs77.png" width="400px" height="300px"   alt="Sekil silinib" title="Random method."/><br/><br/><br/>
</p>
</details>
<b>________________________________________________________________________________________________________________</b>
<!-- ENUM -->
<details><summary><b>16.Enum</b></summary>
1. <b>(enum)</b> enum ne demekdir ?.Enum ile limitli sayda olan secimleri yarada bilerik yeni hefdenin gunleri ilin aylarini ve ya sistemde menyulari ve s. yaratmaq olar.<br/>Enum susmaya gore <b>(intden)</b> toreyib ve biz diger tiplerden yeni tam olan tiplerden torede bilerik mes: byte ,sbyte,short ve s.<br/> Her hansi tipden toretmek isdedikde <b>public enum (MonthName:byte)</b> qeyd etmek lazimdir . Enumlar da 1 ve bir nece secim bir secimden aslidirsa ele qurmaq olar ki hemin secimler isdediyimiz secimden asili olsun .<br/>Enum ozune mexsus xususiyyeti var bu xususuyyet 2-lik say sisteminde kodlardan aslidir.<br/> Enum-larda <b>( | )</b> toplama yeni iklikde olan kodlarin toplami <b>(&)</b> vurma emeliyyatidir buna genis sekilde misal cekek mes: tutaq ki bizde enum <b>(user=1, moderator=2, admin=user|moderator)</b> burada topluyanda indeksler toplanir ve eslinde user=1 de 1-in iklikde kodu <b>(0001)</b> ve moderator=2 2-nin ikilikde kodu <b>(0010)</b> toplanir ve neticede 3-un ikilikde olan <b>(0011)</b> alinir yeni admin 3 cu indeksdir ve admin diger iki user ve moderatorun isini gore biler.<br/>Bele hallardan isdifade etmek lazim olduqda indeksleri 2 usdu kimi gotururuk.Yeni 2 sifir, 2 usdu bir bele bele davam edir . <br/>
<p>
<img src="./image/cs80.png"    alt="Sekil silinib" title="Enum"/><br/><br/><br/>
<img src="./image/cs78.png"    alt="Sekil silinib" title="Enum"/><br/><br/><br/>
<img src="./image/cs79.png"    alt="Sekil silinib" title="Enum"/><br/><br/><br/>
<b>Qeyd: enumun ozunun methodlari vardir ve onlar asagidakilardir.</b><br/>
<img src="./image/cs87.png"    alt="Sekil silinib" title="Enum"/><br/>
 <b>Enum.GetValues(typeof(enum adi yeni tipi))</b> bu method ile enum daki butun secimleri cap ede bilerik.Lakin mutleq enumun tipini gosdermeliyik .Cunki int,byte,long,ulong,short ve s.TIplerden ola biler. <br/>
<img src="./image/cs81.png"    alt="Sekil silinib" title="Enum Method"/><br/>
<img src="./image/cs82.png"    alt="Sekil silinib" title="Enum Method"/><br/><br/><br/>
 <b>Enum.TryParse(typeof(MonthName), Console.ReadLine(), true, out object result)</b> bu method ise enum tryparse methodudur yeni verilmis enumda bizim daxil etdiyimiz numune varmi diye yoxluyur varsa ture yoxdursa false qaytarir.Burada biz ilk olaraq tryparse icinde enum tipini yazdiq sonra datani daxil etdik ve herifin boyuk olub olmamasini yoxladiq <b>ture</b> olduqda boyuk kicik herif ferq etmir isleyir <b>false</b> olduqda ise enum necedirse elede yazilmalidir ve sonda ise eger varsa daxil etdiyimiz data onu object uzerine alir.<br/>
<img src="./image/cs83.png"    alt="Sekil silinib" title="Enum Method"/><br/><br/><br/>
 <b>Enum.IsDefined(typeof(MonthName), result)</b> bu method ile ise gelen datanin yeni resultun hemin enum daxilinde olub olmadigini yoxluya bilerik.<br/>
<img src="./image/cs84.png"    alt="Sekil silinib" title="Enum Method"/><br/><br/><br/>
 <b>Enum.GetName(typeof(MonthName), 1)</b> bu method ile ise enum 1 ci indeksindeki hansi secim oldugunu tapa bilerik. Burda 1 yerine MonthName.Yanvar yazsaq gedib hemin datani getrir.<br/>
<img src="./image/cs85.png"    alt="Sekil silinib" title="Enum Method"/><br/>
<img src="./image/cs86.png"    alt="Sekil silinib" title="Enum Method"/><br/><br/><br/>
<b>Enum.GetUnderlyingType(typeof(MonthName)</b> bu method ile ise biz enum hansi tipden torediyini oyrene bilerik.<br/>
<img src="./image/cs88.png"    alt="Sekil silinib" title="Enum Method"/><br/><br/><br/>
</p>
</details>
<b>__________________________________________________________________________________________________________________</b>
<!-- CLASS -->
<details><summary><b>17.Class</b></summary>
<p>
<i>Class bezi qaydalari.</i><br/>
<img src="./image/cs63.png"    alt="Sekil silinib" title="Conustructors."/><br/><br/>
<i>Static conustructor method qaydasi.</i><br/>
<img src="./image/cs89.png"    alt="Sekil silinib" title="this kivordu."/><br/><br/>
<i><b>this</b>. kiyvordunun izahi ve bir birini cagiran conustructor method.</i><br/>
<img src="./image/cs90.png"    alt="Sekil silinib" title="this kivordu."/><br/><br/><br/>
<i><b>OOP -in esaslari.</b></i><br/>
<i><b>1.Inheritance</b>--Mirass vermek nesillendirmek.</i><br/>
<i><b>2.Encapsulation</b>--Gizletmek ,Gizlin etmek ,Kapsullamaq.</i><br/>
<i><b>3.Inheritance</b>--Mirass vermek nesillendirmek.</i><br/>
<i><b>4.Inheritance</b>--Mirass vermek nesillendirmek.</i><br/><br/><br/>

<i><b>1.Inheritance</b>--Mirass vermek nesillendirmek.</i><br/>
<img src="./image/cs91.png"    alt="Sekil silinib" title="inheritance."/><br/>
<img src="./image/cs92.png"    alt="Sekil silinib" title="inheritance."/><br/><br/>
<i><b>Conustructor methodun ana classin conustructor methodunu cagirmasi.</b></i><br/>
<img src="./image/cs93.png"    alt="Sekil silinib" title="inheritance."/>
<img src="./image/cs94.png"    alt="Sekil silinib" title="inheritance."/><br/><br/><br/>
<i><b>2.Encapsulation</b>--Gizletmek ,Gizlin etmek ,Kapsullamaq.</i><br/>
<img src="image\cs95.png"   alt="Sekil silinib" title="inheritance."/><br/><br/>
<i><b>3.Inheritance</b>--Mirass vermek nesillendirmek.</i><br/>
<i><b>4.Inheritance</b>--Mirass vermek nesillendirmek.</i>

</p>
</details>
<b>________________________________________________________________________________________________________________</b>
<details><summary><b>18.SQL</b></summary>
<i>Dockerde containers yaradilmasi asagidaki codlar vasidesi ile olur.</i><br/>
<b>1.docker run -e "ACCEPT_EULA=Y" -e "MSSQL_SA_PASSWORD=!Salam2000@" -e "MSSQL_PID=Developer" -p 1434:1433 -v MSSQL_Task_1:/var/opt/mssql --name MSSQL_Task_1 --restart always mcr.microsoft.com/mssql/server:2019-latest.</b><br/>
<a href="https://www.youtube.com/watch?v=HPouaPz2vcc">1.Docker kursu butun videolara bax!</a><br>
<i><b>Sql server numune ve codlari.</b></i><br/>
<p><img src="./sql-image/Client-server-model.svg.png"    alt="Sekil silinib" title="server qurulus ."/></p>

<b>Mssql ve C# data type qarsiliqlari asagidaki sekilde gosderilib.</b><br/>
<a href="https://github.com/xasiyevRandom method./MsSql/blob/master/docs/datatypes.md">1.Bu linkden daha yaxsi anlasiliqli olacaqdir!</a><br>

<p><img src="./sql-image/server_2.png"    alt="Sekil silinib" title="Mssql ve C# data type."/></p>
<p><img src="./sql-image/sql1.png"    alt="Sekil silinib" /></p>
<p><img src="./sql-image/sql2.png"    alt="Sekil silinib" /></p><br/>
<p><img src="./sql-image/sql3.png"    alt="Sekil silinib" /></p><br/>
<p><img src="./sql-image/sql4.png"    alt="Sekil silinib" /></p><br/>
<i>Sql comandalar asagidakilari misal gosdermek olar.</i><br/>
<i>1.DDL – Data Definition Language --Məlumat Tərifi Dili</i><br/>
<i>2.DQL – Data Query Language---Data Sorğu Dili</i><br/>
<i>3.DML – Data Manipulation Language---Məlumatların Manipulyasiya Dili</i><br/>
<i>4.DCL – Data Control Language---Məlumata Nəzarət Dili</i><br/>
<i>5.TCL – Transaction Control Language---Tranzaksiyaya Nəzarət Dili</i><br/>

<p><img src="./sql-image/sql5.webp"    alt="Sekil silinib" title="sql comandalar."/></p><br/>
<p><img src="./sql-image/sql6.png"    alt="Sekil silinib" title="sql comandalar."/></p><br/>
<p><img src="./sql-image/sql7.png"    alt="Sekil silinib" title="sql comandalar."/></p><br/>.

</details>
<b>________________________________________________________________________________________________________________</b>

<details><summary><b>19.Hazir deyil.</b></summary>
</b>(Say tipli datatayplar)</b>

1.  </b>(byte)</b> ---> tutumu {0,255} dir mes: byte say1=10;
2.  </b>(sbyte)</b>--> 255 iki hisseye ayrilir ve (-128-->127 kimi).
3.  </b>(int)</b> ----> tutumu {biraz coxdur} mes: int say2=1234345;
4.  </b>(uint)</b>--> minusdari pilusdarinin uzerine gelir ve buda tutumunu artirir.
5.  </b>(double)</b> --->tutumu {coxdur} mes: double say3=1234565432; bunda elave kesir ededleride ozunde saxliya bilir.
6.  </b>(float)</b> ----> tutumu {coxdur} mes: float say4=123432F; kesir ededleri saxliya bilir sonuna mutleq F herifi qoymaliyiq.
7.  </b>(decimal)</b> ---->tutumu {coxdur} mes: decimal say4=1233212321 M; kesir ededleri saxliya bilir sonuna mutleq M herifi qoymaliyiq.
8.  </b>(long)</b> --->tutumu {coxdur} mes: long say5=23234543232;
9.  </b>(ulong)</b>--> minusdari pilusdarinin uzerine gelir ve buda tutumunu artirir.
10. </b>(short)</b> ---> tutumu {32767}
11. </b>(ushort)</b>---> minusdari pilusdarinin uzerine gelir ve buda tutumunu artirir.

</b>(sizeof())</b> ile tipin nece bayit yer tutduguna baxa bilerik.meselen sizeof(int)

## 1 </b>(dec>lon>doub>int>short>byte)</b>

</b>(mentiqi deyisken)</b>

1.  </b>(bool)</b> mentiqi deyiskendir yoxlanis edir dogru olub olmadigini yoxluyur ve geriye </b>(true)</b> </b>(false)</b> qaytarir.

---

</b>(zaman tipli deyisken)</b> 2. </b>(DateTime)</b> --> tarix ve zamani ozunde saxiliyir DataTIme vaxd=(</b>DataTime.Now.Year)</b> !!

---

                                                    ACAR SOZLER.

1.  </b>(checked)</b> ---> asmalarin qarsisini alir ,yeni mes : int maksiumum kecdikde xeberdarliq edir.
2.  </b>(break)</b> ---> Acar sozu qirmaq demekdir ve sert daxilinde emeliyati dayandirar ve koddan cixar.
3.  </b>(countine)</b>---> Acar sozdur davam et demekdir yeni break kimi emeliyati saxlamaz yalniz gormezden gelib davam eder.
4.  </b>(return)</b>---> geri donus geri qaytar demekdir ve gelen datani cagrilan metoda gonderer.
5.  </b>(out)</b> bu geri donus demekdir ve out a colde qiymet versekde olar vermesekde ama iceride mutleq qiymet vermeliyik.mes: TryParsda out var, orda oldugu kimi out-a qiymet vermirik sadece </b>int b;)</b> ve ya </b>(out int b)</b> kimi yaziriq , ama qiymet versek de olar.
6.  </b>(ref)</b> bu da geri donus demekdir lakin out dan ferqli olaraq ref-e colde mutleq qiymet verilmelidir.Iceride ise versekde olar vermesekde.Umumiyetle methodlarda geri donus </b>return)</b> ile olur .Bize methodun bir nece geri donusunu isdiyirikse onda </b>ref ve ya out)</b> dan isdifade edirik .</b>return)</b> yalniz bir deyer geri donus ede bilir.
7.  </b>(in)</b> bu da geri donusdur ferqi ise colde daxil edilen nedirse iceridede o olaraq qalir hec vaxd deyismir sehven deyisdirmek yeni bolmek azaltmaq fln etsek de deyismir nece methoda daxil olubsa ele de cixir.

---

                                                  Masivler ve Kolleksionlar.

---

2. </b>Random random = new Random())</b> (Random-tesadufu demekdir) Random bir klasdir ve bu klass bize tesadufu reqemler vere bilir ve methodu var onlar asagidakilardir.

- </b>int data=Random method.Next(1,10))</b> bu method bize texmini reqem verir.Maksium int qeder ola bilir ve her zaman biz araliq verende yeni burda 1 ile 10 arasinda tesadufu reqemler ver dedikde 1 daxil 10 ise daxil olmur 1 ile 9 daxil reqemler verir.Geriye int qaytarir.
- </b>double data=Random method.NextDouble())</b> bu method ile ise tesadufu 0 ve 1 arasinda reqemler verir yeni kesir ededler.Geriye double qaytarir.
- </b>byte data=Random method.NextBytes())</b> bu method bayit tutumu qeder tesadufu ededler verir.

---

3. </b>(ArrayList A1=new ArrayList())</b> kolleksionu ,Kolleksionlarin vasivlerden ferqi odur ki masivlerde nece data saxlanmasini biz secirik ve deyise bilmerik eyni massivde yeni 3 secmisik yuxarida onu deyise bilmirik, lakin kolleksionlarda ise ozu her data qebul etdikde ise bir elave yer ayrir ve novbeti datani gozleyir.ArrayLisdin metodlarina baxaq.

- </b>(Add())</b>(tek data elave et) metodu ArrayLisdin terkibine tek tek deyerler atmaq ucundur,yeni A1.Add("Random method."), A1.Add(121),
- </b>(AddRange)</b>( cox sayda elave et) metodu bir nece deyeri eyni anda ArrayList e atmaq ucundur.
- </b>(Remove())</b>-->(menasi sil)--> bu method ile ArrayList icindeki isdenilen datani sile bilerik lakin datanin indeksini yox ozunu yazmaq lazimdi.Mes: A1.Remove("Random method.") bu zaman gedib axdaracaq ve Random method. sozunu silecek.
- </b>(RemoveRange)</b>(menasi-> silinme araligi) bu ise indeksle isleyir filan indeksden basla 2 element sil. Mes: A1.RemoveRange(3,2) ucuncu indeksden basla 2 elementi silin.
- </b>(RemoveAt)</b>--> bu method ise tek tek indeks silmek ucundur .Mes: A1.RemoveAt(2) yeni ikinci indeksi get sil.
- </b>(Reverse)</b> (menasi tersine cevir) bu method ise sonuncu indeksde olan datani ilk indeksin uzerine getrir.Yeni sonuncu datadan baslayaraq ilk dataya kimi butun datalari sifirinci indeksden baslayaraq yazdirir.
- </b>(Sort())</b>(menasi A-Z e duzmek,siralamaqdir)-> A-Z e siraliyir metinleri ve reqemleri ise kicikden boyuye.
- </b>(Contains)</b>(menasi ehdiva edr umid edr ve yoxlayir) bu method ise daxil edilen datanin icerisinde bize lazim olan data varmi diye yoxlayir ve geriye bool qaytarir.
- </b>(IndexOf)</b>(indeks menasina gelir)--> bu method ise massiv ve ya kolleksionun daxilinde her hansi data var sa onun indeksini geri int olaraq donur.mes: </b>(int indeks= A1.IndexOf("Random method.");)</b> sozu varsa gedib onun indeksini tapib getrir.
- </b>(Clear)</b>(menasi butovlukde silmekdir)--> bu methoddan isdifade etsek butun elementleri silecek lakin capassite silinmiyecek ,yeni element ucun ayrilan yer silinmir lakin icerisi bos qalir.
- </b>(TrimToSize)</b> bu method ise yuxarida dediyimiz element silinsede onun ucun ayrilan yeri silinmir, lakin bu method ile sabit olaraq 4 elemet yeri saxlayir ve qalanini silir.
- </b>(ToArray)</b> bu metod koleksionlari opject masivvine atmaq ucundur.
- </b>(Resize(ref massiv,massiv.Lenght+1))</b> bu method ile massivin nece elementli oldugunu bilmirikse ardicil olaraq massivin uzunlugunu deyisdire bilerik, yeni bu method bize hemin massivi vermesede yenisini yaradir kohneni onun uzerine atir ve geri donur.Burad ref geri donusunden isdifade edilir ,yeni gedr massivin yenisini yaradir kohne massivi onun uzerine atir ve bize geri donderir.

4. </b>(Hashtable A1=new Hashtable())</b> bu kolleksion diger koleksionlardan ferqlenir .Ferqi odur ki bu iki object deyer teleb edir yeni biri key,digeri ise vouli deyer ,birinci acar soz daxil edilir digeri ise sabit bir deyer ,burada eyni acar soz ola bilmez,amma eyni valu deyer ola biler.Yuxarida qeyd olunan ArrayListin metodlari bu kolleksionlarda da isdifade edilir.

5. </b>(SortedList A1=new SortedList())</b> bu kolleksion da </b>(Hashtable)</b> kimi eynidir,iki object deyer isder ve isdediyi object den biri key(acar) soz olur lakin bir iki ferqi var ve o ferqe baxaq.Burada daxil olan acar sozler eyni tipden int,bayt,string ve s.olmalidir ve tekirarsiz olmalidir.Diger ferqide ondan ibaretdir ki acar sozleri stringdirse A-Z e duzer,reqemdirse kicikden boyuye duzer.

---

6. </b>(Stack A1=new Stack())</b> bu kolleksion bir object deyeri qebul edir.Bu koleksiona data eklemek ve bezi emeliyatlari asagidaki methodlarla edilir.

- </b>(A1.Push("SALAM"))</b> bu method ile Stack koleksionuna data atmaq(gondermek olar) mes: A1.Push("salam").
- </b>(A1.Pop())</b> bu method ile sonuncu daxil olan bir datani bir object e atar mes: </b>(object s=A1.Pop())</b> kimi.ve goturduyu Datani Stack den silir.
- </b>(A1.Peek())</b> bu method ise Stack den sonuncu datani goturer bir object e atar mes: </b>(object s=A1.Peek())</b> kimi.ve goturduyu datani Stack den silmir.

7. </b>(Queue Q1=new Queue())</b> bu koleksion da stack ile eynidir lakin stack de son giren ilk cixdigi halda Queue de ise ilk giren ilk cixir.Burada bir nece method var baxaq.

- </b>(Q1.Enqueue("Random method."))</b> bu method Queue ye data elave etmek ucundur ve burda string olan Random method. sozunu dataya elave etdi.
- </b>(Q1.Dequeue())</b> bu method ile ilk daxil edilen datani goturmek olar lakin hemin datani Queue koleksionundan silecek. \</b>\*(Q1.Peek())</b> bu method ise Stack den sonuncu datani goturer bir object e atar mes: </b>(object s=A1.Peek())</b> kimi.ve goturduyu datani Stack den silmir.Bu method Queue koleksionunda da kecerlidi.

---

                                                              methodlar ve Classlar

1. </b>(methodlar)</b>----> methodlar kod yazarken bize cox komeklik edir yeni bir method yazib bir hissesi eyni olan tapsiriqda yeniden cagirib isdifade ede bilerik.biz yeni metodlar yarada bilerik.Methodlar geriye deyer qaytaran ve geriye deyer qaytarmiyan olur.Geriye deyer qaytaran Methodlarda </b>return)</b> acar sozunden isdifade olunur.Methodlari Class-larin daxilinde yaradilir ve isdediyimiz qeder method yarada bilerik .Methodlar eyni adli olduqda gonderilen </b>datatype-lari)</b> ferqli olmalidir.Mes: Topla methodu </b>int number)</b> qebul edirse novbeti Topla methodu </b>int number,int a)</b> qebul etmelidir ve s.Deqiq desek method adlari eyni olduqda onlarin data qebul etmelerinin sayi ferqli ve ya daxil olan datanin tipleri ferqli ya da ki daxil olunan datalarin sayi eyni olsa yerleri ferqli olmalidir.

2. </b>(Public)</b>---> Public dedikde her kese gorunen olunacaq. Yeni biz basqa bir class da methoda public desek onda hemin method her yerde basqa class-lar da gorunen yeni cagira bilerik.
3. </b>(Private)</b>---> Private dedikde ise biz yalniz hemin klasin icindeki metodu cagira bilirik.Eger Public yazmamisiqsa bu avtomatik Private sayilir.
4. </b>(Protected)</b>--->
5. </b>(Internal)</b>--->
6. </b>(Internal Protected)</b>---->.

---

0.                                                                                                                                                                                                                                                                                             __Valu ve Reference types)__
    </b>Valu ve Reference)</b> tayip dedikde ne nezerde tutulduguna baxaq. </b>RAM)</b> yeni muvveqeti yaddas iki hisseye ayrilir </b>Stack ve Heap)</b> ve butun emeliyatlar bu ikisinde aparilir ve komputer sondurene qeder davam edir .Asagida hansi tiplerin </b>Stack ve Heap)</b> yaddasda saxlanildigini gosdermisem. </b>QEYD)</b> Valu tayiplar stack yaddasda saxlanilir, reference tayiplar ise Heap yaddasda saxlanilir. Valu tayiplar reference tayibdan her zaman suretli isleyir.
1.  </b>int, bayt,double ve s daxilinde reqem saxliya bildiklerimiz.)</b> -->bunlar her biri </b>valu tayipdir stack yaddasda saxlanilir)</b> ve reference tayiplardan suretli isleyir.
2.  </b>string,char, massivler mes:int[] ,classlar ve s.)</b> bunlar ise </b>Reference tayipdir ve Heap yaddasda saxlanilir)</b> ve valu tayiplardan asagi suretde isleyir.

- </details>

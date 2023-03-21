                                                           (Cmd ---- emirleri.)

1. (cd bosluq enter) oldugun fayila aparir.
2.  (cd bosluq ..) bir fayil geri cixir.
3.  (cd bosluq fayilin adi) adi qeyd edilen fayila kecit edir.
4. (cls) acilmis butun melumatlari temizleyir.
5.  (dir) fayilin icine daxil olur.
6. (mkdir) yeni fayil yaradir.
7. (prompt $$) yeni setri dollar isaresi ile basladir.
8. (dotnet run) emri ise kodu ise salir.
9. (code .) visual studio coda kecid emridir.

10. Yeni solutions yaradanda google axdarisda bunu yazaraq tapa bilerik (dotnet new create solution) sayita daxil olduqdan sonra qarsimiza bele bir yazilis cixacaq ve istifade edeceyik (dotnet new sln --name MySolution).
11. Yeni project yaradanda google axdarisda bunu yazaraq tapa bilerik (dotnet create new console app project) sayita daxil olduqdan sonra bele bir yazilisi goreceyik ve istifade edeceyik (dotnet new console --framework net6.0 --use-program-main)
12. Yaratdigimiz solutions ve projecs elaqelendirmek ucun google axdarisa (dotnet  add project solutions create) sayita daxil olduqdan sonra ise qarsimiza cixan (dotnet sln solution.sln add --solution-folder foo1\foo2\foo3 bar.csproj) yazilisdan istifade ederek elaqeni yaradiriq.
________________________________________________________________________________________________________________________________________

                                                    (Bezi axdarislar.)

1. Sending E-mail using C#- Stack Overflow.
2. Stack Overflow Developer Survey 2022. (burada proqram dillerinin ilden ile inkisafina baxa bilerik)
3. diagram.net app (alqoritim qurmaq ucun isdifade edilen sexemleri bize verir).
4. c# method keywords (c# da acar sozlere baxmaq ucun bu sayita baxa bilerik).
5. http://www.java2s.com/Tutorial/CSharp/CatalogCSharp.htm (c# ders sayiti)
_________________________________________________________________________________________________________

                                                  
                                                     (MOVZU.1----->> GIRIS)

QEYD. Cmd --qara ekrandan istifade ederek biz yeni solutions ve preject yarada bilerik.Bunun ucun bir nece etablari kecmeliyik.Evvelce yeni fayil yaratmaliyiq. Fayili ise mkdir emri ile yarada bilerik bunu yuxarida qeyd etmisem . Yeni Solutions ve project yaradaq.

1. ci mkdir emri ile fayil yaradiriq.
2. ci dotnet new sln --name (solutions adi meselen: code)
3. cu project yaratmaq ucun--> dotnet new console --framework net6.0 --use-program-main emrinden istifade edirik .Burada isdesek net6.0 fersiyani istesek deyise bilerik.
4. cu ise solutions ve projecti elaqelendiririk-->> dotnet sln (solution adi yeni:code) add project\csproj sonlugu ile biten fayil ve enter.
________________________________________________________________________________________________________________________________________

                                                           ( GITHUB ---->> Yaratmaq.))

QEYD. Github yaratmaq ucun profile daxil olub qeydiyatdan kecirik, daha sonra ise bir nece emirden isdifade ederek yeni repositories yarada bilerik .
 
 …or create a new repository on the command line
1. git clone (linkimizi buraya yerlesdiririk).
2. echo "dirnaq arasina ne isdesez yaza bilersiz">> README.md -------->>(readme fayili yaratmaq ucundur.)
3. git init ---------->>>(git pafqasi yaratmaq ucundur )
4. git add README.md  ------->>(readmi fayilini testiq etmek ucun)
5. git commit -m "first commit" -----(deyisikliye ad vermek ucun)
6. git branch -M main
7. git remote add origin https://github.com/xasiyevsamir/taskkkk.git
8. git push -u origin main

        Bu emirlerden istifade etmekle yeni repositories yarada bilerik!!!

________________________________________________________________________________________________________________________________________

                                                          (RIYAZI CODLAR.)

1. __(Math.Pow(10,2))__ ---> burada 10 kvadratini yazmisiq yeni (10*10) .Bunu isdediyimiz kimi yaza bilerik yeni kub ve s. Meselen: Math.Pow(10,3) , (10,4).
2. __(Math.Log10)__---> ededin nece reqemli oldugunu tapir amma neticenin usdune mutleq 1 gelirik.
3. __(Math.sqrt)__----> koku tapmaq ucun istifada edilir.
4. __(Math.Round)__---> riyazi yuvarlasdirmaq ucun istifade edilir.
5. __(Math.Floor)__---> asagi yuvarlasdirmaq,yeni tam hisseye kimi atir.
6. __(Math.Ceiling)__---> yuxari yuvarlasdirmaq.
7. __(Math.PI)__---> pi deyeridir .hesabliyada isdifade ede bilerik.
8. __(Math.Abs)__--->Modulu tapmaq ucundur.
9. __(Math.Max)__--> ededin maksimumun tapir.
10. __(Math.Min)__--> ededin minumumun tapir.
________________________________________________________________________________________________________________________________________
 
                                                              (VAREYBILLAR.)

1. Vareybillar bizim kod yazarken adlandirdigimiz hissedir ,yeni aldigimiz melumati, deyeri neyin daxilinde saxliyiriqsa bunlara vareybillar deyilir.Mes : int a =10; string b="cofe", double c=12.3;
burada a,b, ve c vareybil adlanir.Vareybillari biz teyin edirik. Burada 10, 12.3, "cofe" ise data adlanir yeni melumat.Burada int, string ve double ise bizim datatype adlanir.Yeni datatype datanin hansi tipden oldugunu bildirir, fincanda cofe dedikde burda cofe data b vareybil string ise datatype-dir.Yeni fincanin hansi materialdan oldugunu bildirir yeni saxsi ve ya suse.
________________________________________________________________________________________________________________________________________

                                                             (OPERATORLAR.)

Operatorlar bir nece yere ayrilirlar bunlar asagidakilardir.
1. Sade operatorlar (+, -, *, /, %)
   __(+)__ --> toplama emeliyatini yerine yetirmek ucundur.
   __(-)__ --> cixma emeliyatini yerine yetirmek ucundur.
   __(*)__ --> vurma emeliyatini yerine yetirmek ucundur.
   __(/)__ --> bolme emeliyatini yerine yetirmek ucundur.
   __(%)__ --> ededi boldukde qaliqi tapmaq ucundur.

2. Mentiqsel operatorlar __(=, ==, <, >, <=, >=)__
   __(=)__ --> menimsetme operatordur, yeni int a=19, burda 19 u a-ya menimsetdi yeni daxiline atdi.
   __(==)__ --> beraberdir operatorudur, yeni a=2, b=2, burada a==b.
   __(<>)__ --> boyukdur kicikdir operatorudur.
   __(<=,>=)__ --> kicik beraberdir boyuk beraberdir operatorudur.

3. Serti operatorlar (&&, ||, !)
   __(&&)__ --> (ve) operatorudur burda sertin herbiri dogru olmalidir.
   __(||)__ --> (ve ya) operatorudur burada sertlerden hec olmasa biri dogru olmalidir.
   __(!)__ --> (deyilse) operatorudur.Yeni ture-nu false-a cevirir yada false-u ture-ya cevrir.

                                  Bezi qaydalar.

4. int a=10;                                          
   a=a+2   a=12;               
   -------------              
   a+=2 a=12   a++             
     
     int b =12 
 Console.WriteLine(b++)   b=12 
 Console.WriteLine(b)    b=13   
 Console.WriteLine(++b) b=13    
 Console.WriteLine(b)  b=13 
                       
int c=(++a + a++);  c=11+11=22
int c=(++a - a++); c=11-11=0  
int c=(--a + a--); c=9+9=18 
int c=(--a - a--); c=9-9=0                           
int c=(--a + a++); c=9+9=18
___________________________________________________________________________________________________________________________

   0                                             __(CODLAR VE DATATYPE.)__

1. __(Console.Write();)__ ---> bu kod vasitesi ile biz ekranda her hansi bir melumati cap(yazdira) ede bilerik.Yazini cap edir ve nobeti yazini cap etdirende qarsisina alir yeni Console.Write("samir")
                                         Console.Write("xasiyev")  netice---> samirxasiyev olacaqdir. oldugu setirde qalir.

2. __(Console.WriteLine();)__ ---> bu yuxaridaki emirle eynidir lakin bu emirde eyni setirde deyil novbeti setire kecid olunur.
     
     Netice----> samir
                 xasiyev  olacaqdir.
3. __(Console.Redkey();)__  yazilmis her hansi melumati oxumaq ucun ekranda gozluyer bir melumat daxil etdikde ise baglanar.
4. __(Console.ReadLine();)__ istifadeciden melumat almaq ucun ekranda gozluyer melumati daxil edib enteri basdiqada melumati bize getrir
----------------------------------------------------------------------------------------------------------------------------------------
                                                   __(Datatypes.)__
      Datatayiplar 4 yere ayrilir .Metin, say, mentiqi, zaman,
__(metin tipli deyiskenler)__

 1. __(string)__ --> Her hansi bir metin tipli melumatlari saxlamaq ucun istifade edilir.Mes: string name ="samir", "samir123","1234",
 2. __(Char)__ --> bu tipde string tipi kimi eynidir lakin bir metin yeni A,B daxil etdikde istifade edrik eyni zamanda string de istifade etmek dogrudur .
 3. __(object)__ bu tip uzerine butun tipleri ala bilir yeni inti, double, string ve s.Lakin uzerine aldigi tipi o tip kimi de cixarmalidir. int a=10; object b=a;(qutulama boxing) int c=(int)b;(qutudan cixartma unboxing). bunlari intin dauble kecidi ve double 
 inte kecidi ile qarisdirmaq olma . Cox oxsasada coxda ferqlidirler. object tipin eslinde xaricden nese gelerse saxlanilmasi uc isdifade oluna biler. Cunki biz xaricden hansi tipin geleceyini bilmirik .
 4. __(var)__---> Var sagina baxaraq datanin hansi tipden oldugunu anliyir. var tip deyil .
 5. __(dynamic)__ tipdir ve  onun icindeki datalara baxa ve uzerinde emeliyat apara bilerik.sadece sehv nese daxil etdikde error bizden gizledir.
 6. __(as)__ bu kivord obyekte geden tipin hansi tip oldugunu bilmek  ucun ve as kivordu geriye null qaytarir. Null ola bileceyini demek isdiyirikse ? isaresinden istifade edirik mes: byte? a=b as byte?.
 7. __(is)__ bu kivord de eyni ile as benzeyir yeni opject den gelen bayitdirmi int c =10; object v=c;  (v is byte) ve ya (v is int)
 
 --------------------------------------------------------------------------------------------------------------------------------------
 __(Say tipli datatayplar)__

   1. __(byte)__ ---> tutumu {0,255}  dir  mes: byte say1=10;
   2. __(sbyte)__--> 255 iki hisseye ayrilir ve (-128-->127 kimi).
   3. __(int)__ ----> tutumu {biraz coxdur}   mes: int say2=1234345;
   4. __(uint)__--> minusdari pilusdarinin uzerine gelir ve buda tutumunu artirir.
   4. __(double)__ --->tutumu {coxdur}  mes: double say3=1234565432; bunda elave kesir ededleride ozunde saxliya bilir.
   5. __(float)__ ----> tutumu {coxdur} mes: float say4=123432F; kesir ededleri saxliya bilir sonuna mutleq F herifi  qoymaliyiq.
   6. __(decimal)__ ---->tutumu {coxdur} mes: decimal say4=1233212321 M; kesir ededleri saxliya bilir sonuna mutleq M herifi qoymaliyiq.
   7. __(long)__ --->tutumu {coxdur} mes: long say5=23234543232;
   8. __(ulong)__--> minusdari pilusdarinin uzerine gelir ve buda tutumunu artirir.
   9. __(short)__ ---> tutumu {32767} 
   10. __(ushort)__---> minusdari pilusdarinin uzerine gelir ve buda tutumunu artirir.

   __(sizeof())__ ile tipin nece bayit yer tutduguna baxa bilerik.meselen sizeof(int)
                                         
   1                                      __(dec>lon>doub>int>short>byte)__
----------------------------------------------------------------------------------------------------------------------------------------
 __(mentiqi deyisken)__
 1. __(bool)__ mentiqi deyiskendir yoxlanis edir dogru olub olmadigini yoxluyur ve geriye __(true)__ __(false)__ qaytarir.
 ---------------------------------------------------------------------------------------------------------------------------------------
  __(zaman tipli deyisken)__ 
  1. __(DateTime)__ --> tarix ve zamani ozunde saxiliyir DataTIme vaxd=(__DataTime.Now.Year)__ !!
  --------------------------------------------------------------------------------------------------------------------------------------

                                                    ACAR SOZLER.
 
 1. __(checked)__ ---> asmalarin qarsisini alir ,yeni mes : int maksiumum kecdikde xeberdarliq edir.
 2. __(Convert.)__----> Butun tiplerden cevirme apara bilir Parse dan ferqli olaraq.
 3. __(tipinadi.Parse)__ ----> Yalniz reqem tipli stringleri cevire bilir. mes: "123".
 4. __(tipinadi.TryParse(date, out tipinadi a))__---> bu cevirme digerlerinden ferqlenir yeni geriye bool __(ture,false)__ qaytarir yeni cevrile bilir ya cevrile bilmir .
 5. __(break)__ ---> Acar sozu qirmaq demekdir ve sert daxilinde emeliyati dayandirar ve koddan cixar.
 6. __(countine)__---> Acar sozdur davam et demekdir yeni break kimi emeliyati saxlamaz yalniz gormezden gelib davam eder.
 7. __(return)__---> geri donus geri qaytar demekdir ve gelen datani cagrilan metoda gonderer.

________________________________________________________________________________________________________________________________________
                                                      
                                                      Metotlar ve Classlar
1. __(Metotlar)__----> metotlar kod yazarken bize cox komeklik edir yeni bir metot yazib bir hissesi eyni olan tapsiriqda yeniden cagirib isdifade ede bilerik.biz yeni metodlar yarada bilerik.
2. __(Public)__---> Public dedikde biz diger klasdaki metodlari da cagira bilirik.
3. __(Private)__---> Private dedikde ise biz yalniz hemin klasin icindeki metodu cagira bilirik.Eger Public yazmamisiqsa bu avtomatik Private sayilir.
4. __(Protected)__--->
5. __(Internal)__--->
<<<<<<< HEAD
6. __(Internal Protected)__---->



________________________________________________________________________________________________________________________________________
                                                  Masivler ve Kolleksionlar.

1. __(int[] number=new int[3])__ --> burada biz int vasivi yaratdiq .Massivler muxdelif tiplerden ola biler.Burada int[3] 3 reqemi masivvin nece setirli olmasini yeni nece int tipinden data saxlamasini gosderir.Burada 3 indeksli yeni 3 data saxlanilir.Lakin komputer sayarken 0 dan saymaga baslayir.Yeni (0,1,2) burda saysaq 3 data saxlamaq olar yeni 0 ci indeksde bir data ve digerlerinde eynisi.

2. __(ArrayList A1=new ArrayList())__ kolleksionu ,Kolleksionlarin vasivlerden ferqi odur ki masivlerde nece data saxlanmasini biz secirik ve deyise bilmerik eyni massivde yeni 3 secmisik yuxarida onu deyise bilmirik, lakin kolleksionlarda ise ozu her data qebul etdikde ise bir elave yer ayrir ve novbeti datani gozleyir.ArrayLisdin metodlarina baxaq.

* __(Add())__(tek data elave et) metodu ArrayLisdin terkibine tek tek deyerler atmaq ucundur,yeni A1.Add("Samir"), A1.Add(121),
* __(AddRange)__( cox sayda elave et) metodu bir nece deyeri eyni anda ArrayList e atmaq ucundur.
*  __(Remove())__-->(menasi sil)--> bu metot ile ArrayList icindeki isdenilen datani sile bilerik lakin datanin indeksini yox ozunu yazmaq lazimdi.Mes: A1.Remove("Samir") bu zaman gedib axdaracaq ve samir sozunu silecek.
* __(RemoveRange)__(menasi-> silinme araligi) bu ise indeksle isleyir filan indeksden basla 2 element sil. Mes:  A1.RemoveRange(3,2) ucuncu indeksden basla 2 elementi silin.
* __(RemoveAt)__--> bu metot ise tek tek indeks silmek ucundur .Mes: A1.RemoveAt(2) yeni ikinci indeksi get sil.
* __(Reverse)__ (menasi tersine cevir)bu metot ise sonuncu indeksde olan datani ilk indeksin uzerine getrir.Yeni sonuncu datadan baslayaraq ilk dataya kimi butun datalari sifirinci indeksden baslayaraq yazdirir.
* __(Sort())__(menasi A-Z e duzmek,siralamaqdir)-> bu yalniz metinlere aiddir, int ve s.aid deyil.
* __(Contains)__(menasi ehdiva edr umid edr ve yoxlayir) bu method ise daxil edilen datanin icerisinde bize lazim olan data varmi diye yoxlayir ve geriye bool qaytarir.
* __(IndexOf)__(indeks menasina gelir)--> bu method ise massiv ve ya kolleksionun daxilinde her hansi data var sa onun indeksini geri int olaraq donur.mes: __(int indeks= A1.IndexOf("samir");)__ sozu varsa gedib onun indeksini tapib getrir.
* __(Clear)__(menasi butovlukde silmekdir)--> bu methoddan isdifade etsek butun elementleri silecek lakin capassite silinmiyecek ,yeni element ucun ayrilan yer silinmir lakin icerisi bos qalir.
* __(TrimToSize)__ bu method ise yuxarida dediyimiz element silinsede onun ucun ayrilan yeri silinmir, lakin bu method ile sabit olaraq 4 elemet yeri saxlayir ve qalanini silir.
* __(ToArray)__bu metod koleksionlari opject masivvine atmaq ucundur...






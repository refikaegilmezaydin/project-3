# project-3
merge sort ödevim

#[16,21,11,8,12,22] -> Merge Sort
    ##Soru 1.1: Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
	      ###Cevap 1.1: [16,21,11,8,12,22] ana dizisinin Merge Sort tekniği ile sıralanışı aşağıdaki gibidir:
                         
                         [16,21,11,8,12,22]						
										
                [16,21,11]						[8,12,22]
										
	            [16,21]		[11]		        [8]	    [12,22]	
										
                [16]	[21]	[11]	[8]		[12]		[22]
										
	                   [16,21]	   [8,11]	   [12,22]		
										
	                       [8,16,21]	   [11,12,22]		
										
		                    [8,	11,	12,	16,	21,	22]			


##Soru 1.2: Big-O gösterimini yazınız.
###Cevap 1.2: Bu dizinin Merge Sort teknigi ile siralanmasinin time complexity gosterimi: *O(nlogn) seklinde olacaktir. Dizinin eleman sayisina gore islem basamaklari ve dolayisiyla toplam islem suresi dogru orantili olarak lineer artis gostermek yerine dizinin eleman sayisi surekli daha kucuk parcalara bolunerek karsilastirma yuku azaltilmasinin yanisira islem tekrarinin dizi eleman sayisina bagli olarak artip azalacagindan islem suresi logaritmik bir zaman/islem grafiği çıkaracaktır. 
-----------------------------------------
[Kodluyoruz sayfamız için tıklayınız:](https://www.patika.dev/tr)

# VOCABMENTOR
VocabMentor bir kelime ezberleme uygulamasıdır. 7 aşamadan oluşmaktadır; 1.Kelimenin kullanıcıya ingilizcesi sorulması. 2.Kelimenin kullanıcıya türkçesi sorulması. 3.Kelimenin girilen örnek cümlelerin rastgele bir tanesinin içerisinde nasıl kullanıldığını gösterip kelimeyinin anlamının sorulması. 4.Kelimenin girilen örnek cümlelerin rastgele bir tanesinin içerisinde nasıl kullanıldığını gösterip kelimeyinin anlamının sorulması. 5.Kelimenin girilen örnek cümlelerin rastgele bir tanesinin içerisinde nasıl kullanıldığını gösterip kelimeyinin anlamının sorulması. 6.Kelimenin resminin kullanıcıya sorulması. 7.Kelimenin sesinin kullanıcıya sorulması.

Kullanıcı eğer bir kelimeyi bilirse ona en az bir gün sonra türkçesi sorulur. Kullanıcı kelimeyi 2.kez bilirse en az bir hafta sonra örnek cümlelerden kelimesi sorulur. Kullanıcı kelimeyi 3.kez bilirse en az bir ay sonra örnek cümlelerden kelimesi sorulur. Kullanıcı kelimeyi 4.kez bilirse en az üç ay sonra örnek cümlelerden kelimesi sorulur. Kullanıcı kelimeyi 5.kez bilirse en az 6 ay sonra kullanıcıya kelimenin resmi sorulur. Kullanıcı eğer kelimeyi 6.kez bilirse kelimenin sesli okunuşu kullanıcıya dinletilir ve kelime sorulur. Kullanıcı eğer kelimeyi 7.kez bilirse bu kelimeyi öğrendi varsayılır ve bir daha sorulmaz.

Eğer bu adımların herhangi birinde kullanıcı yanlış cevap verirse süreç en başına döner.

Kullanıcıdan her kelime için ingilizcesi, türkçesi, en az 3 tane örnek cümlesi, resmi ve sesli okunuşu girmesi beklenmektedir.

Girilen ses dosyalarının 'wav' ses türünde olması gerekmektedir.

Yanlış bilgi, girilen kelimenin tekrar girilmesi kullancının yapmaması gereken şeylerdir. Bunları kontrol edecek bir mekanizma veya hatayı düzeltecek bir mekanizma yoktur.

Programın çalışması için gerekli olan node modülleri dosyalarda bulunmamaktadır. Terminalden indiriniz
(Bu projede react-hot-toast ve mui-x kütüphaneleri kullanılmıştır.)
(npm install @mui/x-charts)
(npm install react-hot-toast)

ÖNEMLİ NOT: Ses dosyalarını oynatmada sorunlar çıkabilmektedir. Bunun nedeni ses dosyasının Status Code'nun 206 Partial Content olarak dönmesidir. Bu sunucu kaynaklıdır. Bu kod medyanın parça parça çekildiğini gösterir. Bunun nedeni sunucu yada kullanıcının interneti olabilir.


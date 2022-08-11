# Son Koloni Oyunu
Last Colony, hem tek oyunculu modu hem de tamamen multiplayerli HTML5 ve JavaScript'te oluşturulan çok oyunculu mod içeren bir RTS oyunudur.

[Son Koloni Oyunun Demosunu Deneyin](http://www.adityaravishankar.com/projects/games/lastcolony/)

Tek oyunculu kampanya, binalar, araçlar, uçaklar ile birlikte bir senaryo içeren olayların anlatıldığı aşırı kemerli bir hikayeyi içeriyor.

İki oyunculu çok oyunculu, gerçek zamanlı oyuna izin vermek için WebSocket API ile Node.js'yi kullanması içerir.

<b>Ekran Görüntüleri</b>
|   |
|---|
| ![epbalaban01 github io_Last-Colony-Master_](https://user-images.githubusercontent.com/42430554/184126885-b2982fdf-0e60-41e4-b535-44b2f19534f7.png) | 


## Multiplayer Sunucu Kurulumu
1. [Düğüm] (http://nodejs.org/) ve [npm] (https://npmjs.org/) yazılımını kurun
2. Komutu kullanarak WebSocket-Node'yi kurun: `npm websocket install`
3. js klasörü içindeki sunucuyu şu komutu kullanarak başlatın: `node js / server.js`

## Pro HTML5 Oyunları
Bu oyunu tamamen sıfırdan nasıl yeniden oluşturacağınızı öğrenmek istiyorsanız, kitapta ayrıntılı bir yürüyüş bulabilirsiniz [Pro HTML5 Games](http://www.adityaravishankar.com/pro-html5-games/).

Bu oyunu yaratma sürecinde, yol bulmayı ve yönlendirmeyi kullanarak akıllı birim hareketi eklemeye bakıyoruz ve yazılı olayların ve sonlu durum makinelerinin bir kombinasyonunu kullanarak mücadele ediyoruz.

Daha sonra, WebSocket ve Node.JS'nin temellerinden, oyuncu oyunlarını senkronize tutarken ağ gecikmesini telafi etme gibi ayrıntılara kadar çok oyunculu eklemeye bakıyoruz.

## Credits
### Tasarım
1. "Hard Vaccum" Artwork and Game Sprites by [Daniel Cook](http://www.lostgarden.com/)
2. Tasarım Yapan [Open Game Art](opengameart.org)
	* [Thief Portrait by Zeldyn](http://opengameart.org/content/thief-portrait-female)
	* [Jacob Portrait by Gaspard](http://opengameart.org/content/four-post-apocalyptic-portraits)
	* [Priest Portrait by Zeldyn](http://opengameart.org/content/priest-portrait-female)

### Ses
Bedava Ses Müzikleri [Bedava Ses](http://www.freesound.org/)

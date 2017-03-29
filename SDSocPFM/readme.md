このディレクトリの中にはSDSocプラットフォームが３種類置いてあります。各々の名前は対応するSDSocバージョンを意味しています。例えば、PYNQ_2016_3はSDSoc2016.3専用のSDSocプラットフォームです。
PYNQのSDカードに焼いたimgファイルの種類によって、使うべきSDSocのバージョンが異なります。適切なバージョンで作成しないと、生成したsoファイルが認識されません。現時点(2017/03/27)で最新のpynq_z1_image_2017_02_10.imgに対応するSDSocのバージョンは2016.3です。また、pynq_z1_image_2016_09_14.imgに対応するSDSocのバージョンは2016.1です。(2015.4と2016.3では認識されませんでした)

https://s3-us-west-2.amazonaws.com/digilent/Products/PYNQ/pynq_z1_image_2017_02_10.zip  
https://reference.digilentinc.com/reference/programmable-logic/pynq-z1/start?s[]=pynq&s[]=z1  
pynq_z1_image_2016_09_14.img  
SDSocのプラットフォームを作るときは、同じバージョンのVivadoを用いることを推奨します。原因不明のエラーの原因になります。

Bú Cặc T đi t cho commands

step 1: tải server test bản mới nhất của honkai > https://www.google.com/url?q=https://autopatchos.starrails.com/client/download/20230527111343_8wBHfb9dmez1XooM/StarRail_1.1.0.zip&sa=D&source=docs&ust=1686990721592296&usg=AOvVaw3kNBUuUWMqtC-wrXIcaAEj
step 2: tải https://www.telerik.com/fiddler/fiddler-classic
step 3: nhập scripts lưu ý coppy sau ```

```
import Fiddler;

const list = [".yuanshen.com", ".hoyoverse.com", ".mihoyo.com", "starrails.com", ".kurogame.com", "zenlesszonezero.com", "api.g3.proletariat.com", "west.honkaiimpact3.com"]

class Handlers {
    static function OnBeforeRequest(oS: Session) { 

    // Disable script
    //return;

        for (var i = 0; i < list.length; i++) {
            if (oS.host.EndsWith(list[i])) {
                oS.host = "sr.crepe.moe"; // This can also be replaced with another IP address.
                //oS.oRequest.headers.Remove("Sec-WebSocket-Protocol");
            }

            if(oS.host.Contains("overseauspider.yuanshen.com")){
                oS.oRequest.FailSession(404, "Blocked", "your mom");
            }
        }
    }
}

```

step 4:
Nếu bạn ở Châu Á, vui lòng sửa đổi tập lệnh thành “cn-sr.crepe.moe” thay vì “sr.crepe.moe”
Đi đến phía trên bên trái màn hình của bạn, nhấp vào:
Công cụ > Tùy chọn > HTTPS > Đánh dấu vào tùy chọn “Capture HTTPS CONNECTs” > Đánh dấu vào tùy chọn “Decrypt HTTPS traffic” > Actions > Trust Root Certificate

Đảm bảo rằng bạn đã bật Capture Traffic.
File > Capture Traffic (Hoặc chỉ cần nhấn F12)

KHÔNG ĐÓNG FIDDLER NÓ CHUYỂN HƯỚNG LƯU LƯỢNG ĐẾN SR.CREPE.MOE
Mở Honkai Star Rail


Tạo bất kỳ tên người dùng và bất kỳ mật khẩu


Chọn đúng máy chủ gần bạn nhất nếu không trò chơi sẽ bị lỗi với lỗi 1001_3

step 5: chơi thôi

step 6: các lệnh demo

#avatar giveall

March 7th - 1001
Dan Heng - 1002
Himeko - 1003
Welt - 1004
Kafka - 1005
Silver Wolf - 1006
Arlan - 1008
Asta - 1009
Herta - 1013
Bronya - 1101
Seele - 1102
Serval - 1103
Gepard - 1104
Natasha - 1105
Pela - 1106
Clara - 1107
Sampo - 1108
Hook - 1109
Qingque - 1201
Tingyun - 1202
Luocha - 1203
Jingyuan - 1204
Sushang - 1206
Yukong - 1207
Yanqing - 1209
Bailu - 1211

Trailblaze path of destruction and preservation aren’t given
Trailblazer - Destruction path (Male) - 8001
Trailblazer - Destruction path (Female) - 8002
Trailblazer - Preservation path (Male) (2) - 8003
Trailblazer - Preservation path (Female) (2) - 8004

#level avatar avatarID level

#item give <itemId> nếu bạn muốn một mặt hàng cụ thể.
#Item give <id> x<count> chỉ định số lượng mục bạn muốn.
#Item clear xóa hết trong kho đồ

github id item: https://github.com/Dimbreath/StarRailData/blob/master/ExcelOutput/ItemConfig.json

#scene id ( floorid )
```
Parlor Car - 10000 DEAD
Master Control Zone - 10001  
Administrative District - 10101 
Boulder Town - 10102 
Central Starskiff Haven - 10201 
Base Zone - 20001 
Storage Zone - 20002 same as Base zone
Supply Zone - 20003 same as Base zone
Path Space - 20100 DEAD
Outlying Snow Plains - 20101 (Use the Calyx to fight monsters)
Backwater Pass - 20111 
Great Mine - 20121 
Rivet Town - 20122 
Robot Settlement - 20123
Silvermane Guard Restricted Zone - 20131
Corridor of Fading Echoes - 20132
Everwinter Hill - 20133 DEAD 
Everwinter Hill - 20134
Cloudford - 20211
Stargazer Navalia - 20212
Cloudford - 20213 DEAD
Parlor Car - 20214 DEAD
853985869 - 30101 DEAD
853985868 - 30102 DEAD
853985867 - 30103 DEAD
853985866 - 30104 DEAD
853985865 - 30105 DEAD
2016785284 - 30120 DEAD
Cavern of Corrosion - 30201 DEAD
853985803 - 30301 DEAD
Storage Zone - 40002 DEAD
Supply zone - 40003 DEAD
Corridor of Fading Echoes - 40101 DEAD
Great Mine - 40121 DEAD
Silvermane Guard Restricted Zone - 40131 DEAD
Cloudford - 40211 DEAD
-732304349 - 41000 DEAD / name is Robot Settlement
Robot Settlement - 41007 DEAD
Cloudford - 41008 DEAD
Great Mine - 41009 DEAD
Corridor of Fading Echoes - 41010 DEAD
Silvermane Guard Restricted Zone - 41011 DEAD
Cloudford - 41012 DEAD
Rivet Town - 41122 DEAD
Robot Settlement - 41123 DEAD
Silvermane Guard Restricted Zone - 41131 DEAD
Corridor of Fading Echoes - 41132 DEAD
Cloudford - 41211 DEAD
Stargazer Navalia - 41212 DEAD
??? - 80000 DEAD
Simulated Universe - 80001 DEAD
Herta's Office - 80112
Simulated Universe - 81001 DEAD
Simulated Universe - 81002 DEAD
Simulated Universe - 81003 DEAD
Simulated Universe - 81111 DEAD
Simulated Universe - 81121 DEAD
Simulated Universe - 81122 DEAD
Simulated Universe - 81123 DEAD
Simulated Universe - 81131 DEAD
Simulated Universe - 81132 DEAD
Simulated Universe - 81211 DEAD
Simulated Universe - 81212 DEAD
```

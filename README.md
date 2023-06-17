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

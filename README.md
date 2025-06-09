# Version146
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>> Danh sách Hotkey và cách sử dụng <<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<


>>>Ấn Double phím tương ứng :

	+ Click vào Tool rồi ấn  Double "ESC" để tắt hoàn toàn Tool.Nút Close trên Tool sẽ ẩn nó và chạy ngầm chứ không tắt nhé !  

	+ Ấn Double "f" để chạy Auto follow.

	+ Ấn Double "b" để Rebuff .

	+ Ấn Double "t" >>> đá thủ <<< tính năng cao cấp chỉ có trên Server TGHM Tu Chân.Main ấn double "t" xong dùng đá di chuyển hoặc npc tele đến chỗ khác pt tự động dùng đá dịch chuyển theo !
	Lưu ý : Chức năng chỉ áp dụng cho đá di chuyển mua trong O !

	+ Ấn Double "g" sẽ get ID của vật phẩm ở ô thứ nhất trong túi đồ và lưu vào file ItemsInfo.ini(ID ở dưới [ItemInfo],dùng để get ID của phù máu và mana,sau đó cut paste vào dòng phù tương ứng .
Do mỗi phiên bản add nhiều Item lạ  không thống nhất nên làm như vậy cho tiện)\


Mở rộng : >>> Caps Lock - ON <<<
	+ Ấn Double "f" để bật tắt  Auto follow. 

	+ Ấn Double "b" để bật tắt Auto Rebuff .

                                                   >>>>>>>>>>>>•<<<<<<<<<<<

1.Loggin vào game.

2.Chạy Tool,Chọn nhân vật  tương ứng trong ô comboBox của cửa sổ game cần auto.

3. Sync : Đồng bộ tấn công theo nhân vật chỉ định.Thực hiện như sau :
	- B1 : Target vào nhân vật muốn đánh theo.
	- B2 : Tích vào Sync xong.
	Muốn tạm thời không tấn công theo thì bỏ tích,muốn đánh theo lại thì chỉ cần tích vào mà ko cần target lại nữa,muốn đổi sang đánh theo nhân vật khác thì làm lại từ B1>B2.

4. AutoFollow : Tự động đi theo Key.Trong chế độ này thì nhân vật sẽ tự động theo Key nếu khoảng cách tới Key lớn hơn ô ghi bên cạnh. 
Ngoài ra sẽ tự động chuyển trạng thái cưỡi ngựa ,ko cưỡi hay Fly theo Key đồng thời sẽ tự động tăng độ cao.

5. Tool tự động dừng auto khi mất kết nối hay nhân vật thoát ra màn hình chọn nhân vật.

6.Nút "Show/Hide" ẩn của sổ game cho nó sáng cái màn hình.

7.Tool có 3 chế độ đánh là: - Đánh mod theo tên thì ("trước khi run phải target Mod cần đánh trước") 
			      - Đánh tất cả thì ko cần target,đánh toàn bộ mod xung quanh ! 			   

8.CountDie :Giới hạn số lần sống lại(mặc định 1000 lần) sau đó tool Pause.Manne : Số lượng hình nhân trong túi(bản 136 chưa có hàng mẫu để lấy ID nên ko khả dụng)

9. Về làng : nếu sau khi die muốn về làng

10. Dùng bùa : nếu sau khi die muốn dùng bùa hồi sinh

11. Kỹ Năng : Chờ Vũ linh hồi sinh.

12. Manne : Số lượng hình nhân hiện tại.

13. Die : Số lần chết.

14. Distance,Height,MobsLVL là các giới hạn chọn mob theo bán kính train, độ cao,level mob.

15. Change Hp-Mp : Tự động thay phù HP,Mp khi dung lượng phù nhỏ hơn giá trị ghi bên cạnh.Hiện tại chỉ hỗ trợ thay một số phù có sẵn trong danh sách ,
ae muốn thêm thì tự add thêm vào(cách add xem thông tin về Hotkey Double "g")

16. Min Relia : Độ bền tối thiểu để thay vũ khí.

17. Change Weapon : Tích vào để tự động thay,tối đa 3 lần,vú khí phải để ở ô 1-2-3 trong túi đồ. Thêm Back Repair (bật cả 2 chế độ thay và về sửa thì nó thay hết xong mới về sửa)
Ko cần get tọa độ npc,tool tự động bay lên rồi tăng độ cao tiếp theo sử dụng skill hồi thành về nơi gần nhất ,tự động tìm npc sửa đồ sau đó quay lại nơi bắt đầu start auto.
Khi bật chức năng die về làng thì chức năng này cũng tự động kích hoạt.
Lưu ý: khi hồi thành về mà ko có npc để sửa đồ nhân vật sẽ bỏ qua và tự ra bãi train.

18. Skill Attack của Tinh linh : Sử dụng theo thiwf gian tính bằng giây

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>TAB 2---SKILL<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<


19. Norman Attack : tấn công thường. Trường hợp class VL sẽ là Only Heal(heal đơn giản tích hợp >>> thận trọng khi sử dụng)
 
20. Load Skill : ấn để load skill vào các ô.Tool tự get thông tin Delay của skill ko cần Set.chọn skill rồi tick vào là được.

	Hỗ trợ 4 Skill tấn công và 1 Skill dùng chân nguyên(chọn số lượng chân nguyên tương ứng).
	
21. Patch : Dùng cho một số trường hợp ko tự động load skill(chỉ thấy ở một số máy cá biệt) thì vui lòng tìm đến file chứa skill tương ứng	
	

22. CHú ý phần Skill ReBuff có phần nhập lần lượt là thời gian(chuẩn bị + thi triển) của skill đó ô tiếp theo là thời gian Rebuff lại.

	>>> Thần thú train dạng thú thì skill Rebuff 1 và 2 để Thú vương cổ vũ và Cự linh thần lực !

	>>> Tiên thú nếu muốn sử dụng chức năng rebuff phản damage cho Pt thì skill buff Phản chấn phải để đầu tiên.Nó tự buff phản damage cho tất cả các class cận chiến !

23. Skill Tran: Thiết lập skill biến hình cho TT(sau này sẽ thêm TíT).Chọn skill biến hình,tích vào Transfiguration để kích hoạt tính năng này sẽ.

	Tự động hóa người thay Phù,Vũ khí,Rebuff rồi trở về dạng thú nếu train dạng thú.
	
	
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>TAB 3---Exten <<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<	
	
24. Sky Ege	: Khi bật tool sẽ hiện danh sách toàn bộ người chơi xung quanh( tính năng này kế thừa hồi đi du lịch Indo).Báo động màu sắc : Xanh - ok ,Đỏ - số người chơi xung quanh
nhiều hơn số người pt !
	
25. Max zoom : mở giới hạn zoom !

26. PickUp All: Nhawtk tất.Thời gian giữa các lần nhặt ghi trong ô bên cạnh.	

27. Throw : Vứt đồ trong túi có tên trong danh sách ThrowItem(trong file ItemsInfo.ini )

28. Height Save(độ cao bay an toàn khi từ làng ra bãi train) ,Height Repair(độ cao bay trong làng tránh mắc dây điện ;))	
	
29. Pot Hp-Mp : Chức năng cắn máu và mana bình.Với số máu và mana còn lại tương ứng ô ghi bên cạnh.

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>TAB 4---Pet <<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<

Click vào Show Note để xem chi tiết !

30. Pet: Chỉ dành cho Tít, tích vào để bật tính năng.
	- Envir : Loại hình pet (nước,mặt đất,fly) tính năng chưa ổn định !
	
	- PercentHp : Phần trăm máu còn lại của Pet,thấp hơn hoặc bằng sẽ tự động Heal.

	- TimeRev(s) : Thời gian hồi sinh Pet(tùy theo lvl của skill) tính bằng  giây !

	- Pets Loc : Vị trí của Pet trong túi thú - 1.Ngoài ra vị trí số 1 trong túi thú mặc định là thú cưỡi dùng cho tính năng Auto Follow.
	
	- Feeding : Tích vào để tự động cho ăn khi độ trung thành nhỏ hơn giá trị bên cạnh.(Thúc ăn mặc định ô 8 trong túi đồ - ô cuối cùng hàng thứ 1).
	- Skill Pet : đang thử nghiệm (hoạt động ko ổn định)
	
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>TAB 5---... <<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<

31. CHức năng thiết lập skill cho class mới(chơi 3 tộc ko cần quan tâm,đã get full skill)
	
32. Bổ xung thêm click	:
		- Thiết lập chuột
		- Thời gian thực hiện click
		- Thời gian click lại lần kế tiếp
		- Số lần lặp(=0 là lặp liên tục)
		Ấn GetP rồi qua cửa sổ game chuột phải vào điểm cần click để lấy tọa độ.
		
Có 2 chế click :
			- Mặc định click ngẫu nhiên(đến thời gian lặp lại click thì click)
			- Tuần tự : Click theo thứ tự từ trên xuống dưới !
			
			
33.Chú ý: một số trường hợp pause auto lại rồi run bị lỗi ae chạy lại tool hộ nhá ,lười chả fix ! Chủ tool nhiều việc lắm ae chịu khó đọc hướng dẫn và xem video !


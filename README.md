# CPBL_data_visualization
a data visualization for the data of baseball website CPBL

功能說明:
	(1)	最上面一排的六個按鈕分別代表六種不同的數據，滑鼠滑過去可以查看相對應的中文名稱
		預設選擇了AVG這個數據，使用者可以根據自己想要查看的數據點選
	(2)	左邊一排為球員名單(我們從中華職棒官網找出資歷達10年的球員)
		綠色的長條圖為其數據的十年平均，預設選擇了第一位球員
		使用者可以根據自己想要查看的球員點選
	(3)	右邊的長條圖顯示的資料為對應的球員的十年數據折線圖
		紅色面積部分為十年的平均(扣除無資料[0]的平均)，高於平均的年份以藍色圓形表示
		低於平均的年份以紅色圓形表示，最大值以較大藍色圓形表示
		最小值以較大紅色圓形表示，滑鼠滑過圓形可查看該點的數據

用途說明:
	主要用於呈現中華職棒年資達十年(或接近十年)的球員的各數據趨勢
	舉例來說，若選擇了球員彭政閔(第二號球員)的AVG數據觀看
	可以清楚的看出，該球員在前五年數據高於平均(藍色圓形)
	而近五年的數據則低於平均(紅色圓形)，由此可以看出
	這名球員可能正在走下坡
	
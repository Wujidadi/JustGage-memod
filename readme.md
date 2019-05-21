# JustGage

原作者 [Toorshia](https://github.com/toorshia)（[GitHub](https://github.com/toorshia/justgage)）。

2016 年 3 月 5 日，Toorshia 在[某個 issue](https://github.com/toorshia/justgage/issues/204) 中說他有朝一日會加入一個 `prototype.update()` 函數來動態更改 gauge 的所有參數，但直到今天（2019 年 5 月 21 日）仍是食言狀態；反倒是到了同年 12 月 19 日，才由 [jdiegogonzales](https://github.com/jdiegogonzales) 在 `prototype.refresh()` 中加入了變更最小值的功能。

Toorshia 於 2016 年 9 月 26 日的 1.2.9 版（至今為止他本人的最後一次更新）加入了由百分比率指定 `customSectors` 區間顏色的功能，但有 bug，一直沒能真的實現，直到 2018 年 9 月 28 日才由 [MartinLindalHansen](https://github.com/MartinLindalHansen) 修復。

2019 年 5 月 21 日，[我](https://github.com/Wujidadi)自己又修改了 `prototype.refresh()` 中參數 `min` 和 `max` 的定義，使這兩個值可以被指定為 0。
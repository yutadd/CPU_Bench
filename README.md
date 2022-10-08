# lock_core_VS_std_thread<br>
Compared that locking physical CPU core and std:thread<br>
物理コアをロックするのとstd:threadでどっちが早いか試すアプリ。<br>
このコードでの条件だといがいとstd:threadに任せちゃうほうが速かった...<br>
Benched for 30sec.<br>
assign thread to core:    267161689<br>
assign free thread:       822861222<br>
assign std:thread to core:363581241<br>
assign free std:thread:   894167643<br>

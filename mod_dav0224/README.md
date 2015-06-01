# mod_dav0224


// 文字列中の' ', '$', '`', '\' にはESC文字('\')を付与する．Linuxのパス文字を意識して．
// 文字列全体は""で囲む．
// コマンド実行時のcurrent dirはApacheのroot dirになる．

#define MY_DAVEXEC_PUT_CMDPATH "/opt/bin/davexec/davexec_put.py"
#define MY_DAVEXEC_DELETE_CMDPATH "/opt/bin/davexec/davexec_delete.py"


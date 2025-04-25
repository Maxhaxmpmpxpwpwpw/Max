-- Hint表示を並列処理で動かす
coroutine.wrap(function()
	local msg = Instance.new("Hint")
	msg.Parent = game.Workspace
	msg.Text = "作者: huhさかにたにへ"
	wait(999999999) -- 超長待機
	msg:Destroy()
end)()

-- Message部分（メイン処理）
local messages = {
	"作者:huh\nアイデア:K1nak0",
	"このスクリプトは物や人を飛ばすです。",
	"サーバーを荒らしましょう！",
	"うへ ",
	""
}

for _, text in ipairs(messages) do
	local m = Instance.new("Message")
	m.Parent = game.Workspace
	m.Text = text
	wait(4)
	m:Destroy()
end
# server-godlike-Run

PANEL_USERNAME

PANEL_PASSWORD

SERVER_URL

TG_BOT_TOKEN

TG_CHAT_ID

URL：https://api.github.com/repos/<你的用户名>/<仓库名>/dispatches

Header：Authorization: Bearer <你的GitHub Personal Access Token>、

Accept: application/vnd.github+json

Body（JSON）：{"event_type": "godlike-renew"}

可选
VLESS_LINK    
vless:// 链接（TLS + WebSocket）→ 会生成 tls + ws 配置。安装 xray-core 将 VLESS 节点转为本地 Socks5 代理使用这个本地 Socks5 代理工作。Secret 名称=VLESS_LINK 。值 =粘贴我的 vless:// 链接

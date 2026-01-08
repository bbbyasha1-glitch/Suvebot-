# Suvebot-
aiogram yt-dlp
def subscribe_keyboard():
    buttons = [
        [InlineKeyboardButton(text="📢 Канал 1", url="https://t.me/channel_one")],
        [InlineKeyboardButton(text="📢 Канал 2", url="https://t.me/channel_two")],
        [InlineKeyboardButton(text="✅ Проверить подписку", callback_data="check_sub")]
    ]
    return InlineKeyboardMarkup(inline_keyboard=buttons)

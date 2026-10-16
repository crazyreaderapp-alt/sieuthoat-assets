# Âm thanh — Siêu Thoát Chi Chiến — CREDITS

## File thu thật (CC0 — Kenney, kenney.nl)
Các file sau là bản thu thật, lấy từ các gói Kenney (Creative Commons Zero, CC0 —
dùng tự do cho cả dự án thương mại, không bắt buộc ghi credit, nhưng chúng tôi ghi
nhận nguồn tại đây). File đã đổi tên theo ID âm thanh của game.

| Game ID | Gốc Kenney | Gói |
|---|---|---|
| sfx_ui_click | click_001 | Interface Sounds |
| sfx_ui_hover | tick_001 | Interface Sounds |
| sfx_ui_card_select | select_001 | Interface Sounds |
| sfx_ui_tab | switch_003 | Interface Sounds |
| sfx_ui_error | error_001 | Interface Sounds |
| sfx_ui_reward | confirmation_002 | Interface Sounds |
| sfx_cultivation_tick | tick_004 | Interface Sounds |
| sfx_ui_card_flip | card-slide-1 | Casino Audio |
| sfx_draw | card-slide-3 | Casino Audio |
| sfx_gacha_spin | card-shuffle (cắt 2s) | Casino Audio |
| sfx_gacha_reveal_common | card-place-1 | Casino Audio |
| sfx_gacha_reveal_epic | card-place-2 | Casino Audio |
| sfx_gacha_reveal_legend | cards-pack-open-1 | Casino Audio |
| sfx_gacha_reveal_mythic | cards-pack-open-2 | Casino Audio |
| sfx_atk_kim | drawKnife1 | RPG Audio |
| sfx_atk_moc | impactWood_medium_000 | Impact Sounds |
| sfx_atk_quang | impactBell_heavy_000 | Impact Sounds |
| sfx_atk_counter | impactMetal_light_001 | Impact Sounds |
| sfx_hit | impactPunch_medium_000 | Impact Sounds |
| sfx_hit_crit | impactPunch_heavy_000 | Impact Sounds |
| sfx_destroy | impactGlass_heavy_000 | Impact Sounds |
| sfx_lp_damage | impactSoft_heavy_000 | Impact Sounds |
| sfx_trap_trigger | impactMetal_medium_000 | Impact Sounds |
| sfx_tribute | impactGlass_light_000 | Impact Sounds |
| sfx_artifact_activate | impactBell_heavy_001 | Impact Sounds |
| sfx_huonghoa_offer | impactBell_heavy_002 | Impact Sounds |
| sfx_atk_am | forceField_001 | Sci-fi Sounds |
| sfx_direct_atk | lowFrequency_explosion_000 | Sci-fi Sounds |

License: CC0 1.0 — https://creativecommons.org/publicdomain/zero/1.0/
Nguồn: https://kenney.nl — "Credit would be nice but is not mandatory."

## File tổng hợp lớp (original synthesis, tự tạo)
Các file sau được tổng hợp bằng script `gen_sounds.py` (noise định hình + hài âm
+ reverb convolution tự tạo). Hoàn toàn nguyên bản, không dùng bản thu có bản quyền:

sfx_atk_hoa (lửa), sfx_atk_thuy (nước), sfx_atk_phong (gió), sfx_atk_tho (đất),
sfx_thunder_tribulation (sấm thiên kiếp), sfx_summon_1_3 / 4_6 / 7_8 / 9 (triệu hồi),
sfx_token_summon, sfx_spell_activate, sfx_buff, sfx_debuff, sfx_heal, sfx_banish,
sfx_breakthrough_success / fail, sfx_realm_break, sfx_fusion_tamthanh,
bgm_victory, bgm_defeat, bgm_breakthrough, bgm_breakthrough_fail (stinger).

## BGM vòng lặp — file thật (Kevin MacLeod, CC-BY 4.0)

16 BGM vòng lặp là bản thu thật của Kevin MacLeod (incompetech.com),
giấy phép **Creative Commons Attribution 4.0 (CC-BY 4.0)** —
https://creativecommons.org/licenses/by/4.0/
Dùng tự do cho cả dự án thương mại, yêu cầu ghi credit (đã ghi tại đây).
Mỗi file đã cắt thành loop 70s (đoạn 15s→85s của bản gốc) + fade in/out 3s
để lặp liền mạch, nén OGG Vorbis q3.

| Game ID | Bài gốc Kevin MacLeod | Dùng cho |
|---|---|---|
| bgm_main_theme | Heroic Age | Theme chính |
| bgm_realm_nhan | Long Road Ahead | Nhân Giới |
| bgm_realm_huonghoa | Temple of the Manes | Hương Hỏa Giới |
| bgm_realm_amti | The Descent | Âm Ti Giới |
| bgm_realm_tien | Shades of Spring | Tiên Giới |
| bgm_realm_phat | Meditation Impromptu 01 | Phật Giới |
| bgm_realm_viet | Shenyang | Việt Giới |
| bgm_realm_ma | Black Vortex | Ma Giới |
| bgm_realm_yeu | Enchanted Journey | Yêu Giới |
| bgm_realm_quy | Darkness is Coming | Quỷ Giới |
| bgm_realm_dao | Echoes of Time | Đạo Giới |
| bgm_battle | Five Armies | Battle thường |
| bgm_battle_boss | Volatile Reaction | Battle boss |
| bgm_battle_final | Crossing the Chasm | Trận cuối |
| bgm_gacha | On the Shore | Gacha |
| bgm_cultivation | Meditation Impromptu 02 | Tu luyện |

Credit đầy đủ: "Music: Kevin MacLeod (incompetech.com), licensed under CC-BY 4.0".
Nguồn tải: https://incompetech.com/music/royalty-free/mp3-royaltyfree/

Engine tổng hợp ngũ cung (STC_BGM trong `js/sound.js`) vẫn giữ làm fallback
nếu file BGM lỗi/mất — game không bao giờ im lặng.

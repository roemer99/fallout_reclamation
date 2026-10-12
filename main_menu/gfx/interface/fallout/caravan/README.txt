FALLOUT RECLAMATION - Caravan graphics
======================================
All textures: DDS, BC3/DXT5 (cards, backs) or BC1/DXT1 (table).

cards/card_1.dds ... card_10.dds   Card faces by value (1 = Ace). Size 256 x 384.
cards/card_11.dds ... card_14.dds  Face cards: 11 = Jack, 12 = Queen, 13 = King, 14 = Joker.
                                    Currently TEMPLATES (card back + value).
                                    Replace them with the final card art, same names.
cards/card_slot.dds                 Empty card slot on the table.

backs/back_1.dds                    Card back of deck 1 (default). Size 256 x 384.
backs/back_2.dds, back_3.dds ...    More card backs: just add files with the next number
                                    and raise fallout_vav_cv_deck_count in
                                    in_game/common/script_values/fallout_vav_caravan_values.txt
                                    -> the "Change deck" button cycles through them.

table/table_1.dds                   Table surface. Size 1024 x 576.

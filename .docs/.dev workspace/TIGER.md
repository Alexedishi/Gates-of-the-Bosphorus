[19:03:18][jomini_scriptvalue.cpp:1659]: Value of wrong type in 'common/scripted_effects/7-00_eqfm_balkans_effects.txt:21'. Got value of type 'none'

error(missing-item): script value eqfm_crisis_progress_value not defined in common/script_values/
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
528 |  eqfm_balkans_crisis_progress_bar: "#! #header [concept_ottoman_integrity]: #v [GetGlobalVariable('eqfm_balkan_situation').Var('eqfm_crisis_var').GetValue|2]/250#!#!$gbbf_linebreak_normal$[GetPlayer.MakeScope.GetScriptValueDesc('eqfm_crisis_progress_value')]$gbbf_linebreak_normal$#white #bold [GetGlobalVariable('eqfm_balkan_situation').Var('eqfm_crisis_progress_var').GetValue|+=] monthly"
|


error(modifiers): `state_slave_import_mult` is a modifier for state and will not flow from building
--> [MOD] common/production_methods/gbbf_07_government_methods.txt
55 |             state_slave_import_mult = 0.1
|             ^^^^^^^^^^^^^^^^^^^^^^^
= Info: valid modifiers are for building, goods
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow


error(strict-scopes): scope:first_country might not be available here
--> [MOD] common/on_actions/gbbf_code_on_actions.txt
302 |         scope:first_country = {
|         ^^^^^^^^^^^^^^^^^^^
289 |         balkfm_trs_protectorate_autonomy
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
287 | on_diplomatic_action_overlord_increase_autonomy = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here

error(strict-scopes): scope:first_country might not be available here
--> [MOD] common/on_actions/gbbf_code_on_actions.txt
302 |         scope:first_country = {
|         ^^^^^^^^^^^^^^^^^^^
296 |         balkfm_trs_protectorate_autonomy
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
294 | on_diplomatic_action_subject_increase_own_autonomy = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here

error(strict-scopes): scope:second_country might not be available here
--> [MOD] common/on_actions/gbbf_code_on_actions.txt
305 |         scope:second_country = {
|         ^^^^^^^^^^^^^^^^^^^^
289 |         balkfm_trs_protectorate_autonomy
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
287 | on_diplomatic_action_overlord_increase_autonomy = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here
= Info: available names are first_country

error(strict-scopes): scope:second_country might not be available here
--> [MOD] common/on_actions/gbbf_code_on_actions.txt
305 |         scope:second_country = {
|         ^^^^^^^^^^^^^^^^^^^^
296 |         balkfm_trs_protectorate_autonomy
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
294 | on_diplomatic_action_subject_increase_own_autonomy = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here
= Info: available names are first_country

error(strict-scopes): scope:first_country might not be available here
--> [MOD] common/on_actions/gbbf_code_on_actions.txt
340 |         scope:first_country = {
|         ^^^^^^^^^^^^^^^^^^^
283 |         eqfm_balkans_decrease_autonomy
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
281 | on_diplomatic_action_overlord_decrease_autonomy = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here

error(strict-scopes): scope:second_country might not be available here
--> [MOD] common/on_actions/gbbf_code_on_actions.txt
343 |         scope:second_country = {
|         ^^^^^^^^^^^^^^^^^^^^
283 |         eqfm_balkans_decrease_autonomy
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
281 | on_diplomatic_action_overlord_decrease_autonomy = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here
= Info: available names are first_country

error(strict-scopes): scope:first_country might not be available here
--> [MOD] common/on_actions/gbbf_code_on_actions.txt
363 |         scope:first_country = {
|         ^^^^^^^^^^^^^^^^^^^
290 |         eqfm_balkans_increase_autonomy
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
287 | on_diplomatic_action_overlord_increase_autonomy = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here

error(strict-scopes): scope:second_country might not be available here
--> [MOD] common/on_actions/gbbf_code_on_actions.txt
366 |         scope:second_country = {
|         ^^^^^^^^^^^^^^^^^^^^
290 |         eqfm_balkans_increase_autonomy
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
287 | on_diplomatic_action_overlord_increase_autonomy = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here
= Info: available names are first_country

error(strict-scopes): local_var:eqfm_current_adjustment_var might not be available here
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
613 |                 multiplier = local_var:eqfm_current_adjustment_var
|                              ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
613 |                 multiplier = local_var:eqfm_current_adjustment_var
|                 ^^^^^^^^^^ <-- scopes initialized here

error(strict-scopes): local_var:eqfm_current_adjustment_var might not be available here
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
639 |                 multiplier = local_var:eqfm_current_adjustment_var
|                              ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
639 |                 multiplier = local_var:eqfm_current_adjustment_var
|                 ^^^^^^^^^^ <-- scopes initialized here

error(strict-scopes): local_var:eqfm_current_adjustment_var might not be available here
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
664 |                 multiplier = local_var:eqfm_current_adjustment_var
|                              ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
664 |                 multiplier = local_var:eqfm_current_adjustment_var
|                 ^^^^^^^^^^ <-- scopes initialized here

error(strict-scopes): local_var:eqfm_current_adjustment_var might not be available here
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
689 |                 multiplier = local_var:eqfm_current_adjustment_var
|                              ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
689 |                 multiplier = local_var:eqfm_current_adjustment_var
|                 ^^^^^^^^^^ <-- scopes initialized here

error(strict-scopes): local_var:eqfm_current_adjustment_var might not be available here
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
714 |                 multiplier = local_var:eqfm_current_adjustment_var
|                              ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
714 |                 multiplier = local_var:eqfm_current_adjustment_var
|                 ^^^^^^^^^^ <-- scopes initialized here

error(strict-scopes): scope:other_country might not be available here
--> [MOD] common/treaty_articles/gbbf_cease_raiding.txt
20 |         c:TUR ?= scope:other_country
|                  ^^^^^^^^^^^^^^^^^^^
14 |     visible = {
|     ^^^^^^^ <-- scopes initialized here

error(strict-scopes): scope:other_country might not be available here
--> [MOD] common/treaty_articles/gbbf_return_kotor.txt
21 |         scope:other_country = {
|         ^^^^^^^^^^^^^^^^^^^
14 |     visible = {
|     ^^^^^^^ <-- scopes initialized here

error(strict-scopes): scope:target might not be available here
--> [MOD] common/war_goal_types/00_gbbf_halt_expulsions.txt
22 |         scope:target = {
|         ^^^^^^^^^^^^
21 |     valid = {
|     ^^^^^ <-- scopes initialized here

error(strict-scopes): scope:turkfm_sabahaddin_scope might not be available here
--> [MOD] events/3-01_turkfm_tanzimat_events.txt
2047 |             scope:turkfm_sabahaddin_scope = {
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/journal_entries/3-01_turkfm_tanzimat.txt
688 |         trigger_event = turkfm_tanzimat.200
|                         ^^^^^^^^^^^^^^^^^^^ <-- triggered from here
654 | je_turkfm_tanzimat_young_turks = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here
= Info: available names are dlc_grefm, journal_entry, target, young_turks_host_scope or young_turks_movement_scope

error(strict-scopes): scope:mgrbfm_abbas_scope might not be available here
--> [MOD] events/4-00_mgrbfm_egypt_events.txt
269 |             set_heir = scope:mgrbfm_abbas_scope
|                        ^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/journal_entries/4-00_mgrbfm_egypt.txt
173 |             5 = mgrbfm_egypt.003
|                 ^^^^^^^^^^^^^^^^ <-- triggered from here
2 | je_mgrbfm_egypt_muhammad_ali = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here
= Info: available names are dlc_grefm, journal_entry, mgrbfm_heir_scope, mgrbfm_ruler_scope, ottoman_scope or target

error(strict-scopes): scope:mgrbfm_said_scope might not be available here
--> [MOD] events/4-00_mgrbfm_egypt_events.txt
277 |             set_heir = scope:mgrbfm_said_scope
|                        ^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/journal_entries/4-00_mgrbfm_egypt.txt
173 |             5 = mgrbfm_egypt.003
|                 ^^^^^^^^^^^^^^^^ <-- triggered from here
2 | je_mgrbfm_egypt_muhammad_ali = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here

error(strict-scopes): scope:mgrbfm_new_heir_scope might not be available here
--> [MOD] events/4-00_mgrbfm_egypt_events.txt
410 |         set_heir = scope:mgrbfm_new_heir_scope
|                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/journal_entries/4-00_mgrbfm_egypt.txt
175 |             5 = mgrbfm_egypt.005
|                 ^^^^^^^^^^^^^^^^ <-- triggered from here
2 | je_mgrbfm_egypt_muhammad_ali = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here
= Info: available names are dlc_grefm, journal_entry, ottoman_scope or target

error(strict-scopes): scope:mgrbfm_nile_flood_state_scope might not be available here
--> [MOD] events/4-00_mgrbfm_egypt_events.txt
1209 |     placement = scope:mgrbfm_nile_flood_state_scope
|                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/journal_entries/4-00_mgrbfm_egypt.txt
600 |         trigger_event = mgrbfm_egypt.200
|                         ^^^^^^^^^^^^^^^^ <-- triggered from here
570 | je_mgrbfm_egypt_imperialism = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here
= Info: available names are journal_entry or target
^^^^^^^^^^^

error(strict-scopes): scope:eqfm_balkan_character_scope might not be available here
--> [MOD] events/7-00_eqfm_balkans_events.txt
1991 |         scope:eqfm_balkan_character_scope = {
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/on_actions/gbbf_pulse_on_actions.txt
459 |         5 = eqfm_balkans.110
|             ^^^^^^^^^^^^^^^^ <-- triggered from here
429 |         eqfm_balkan_powder_keg_outsider_pulse
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
32 |         eqfm_balkan_powder_keg_monthly_pulse
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
2 | on_monthly_pulse_country = {
| ^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here
= Info: available names are eqfm_balkan_culture_scope, eqfm_balkan_pop_scope, eqfm_balkan_religion_scope, eqfm_balkan_state_scope or eqfm_post_origin_scope


error(strict-scopes): scope:eqfm_riot_state_scope might not be available here
--> [MOD] events/7-00_eqfm_balkans_events.txt
4262 |                 scope:eqfm_riot_state_scope = {
|                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/on_actions/gbbf_pulse_on_actions.txt
484 |         5 = eqfm_balkans.305
|             ^^^^^^^^^^^^^^^^ <-- triggered from here
429 |         eqfm_balkan_powder_keg_outsider_pulse
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
32 |         eqfm_balkan_powder_keg_monthly_pulse
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
2 | on_monthly_pulse_country = {
| ^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here
= Info: available names are eqfm_balkan_state_scope

error(strict-scopes): scope:eqfm_balkan_state_scope might not be available here
--> [MOD] events/7-00_eqfm_balkans_events.txt
4672 |     placement = scope:eqfm_balkan_state_scope
|                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/on_actions/gbbf_pulse_on_actions.txt
488 |         5 = eqfm_balkans.309
|             ^^^^^^^^^^^^^^^^ <-- triggered from here
429 |         eqfm_balkan_powder_keg_outsider_pulse
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
32 |         eqfm_balkan_powder_keg_monthly_pulse
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
2 | on_monthly_pulse_country = {
| ^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here

error(strict-scopes): scope:other_country might not be available here
--> [MOD] events/7-00_eqfm_balkans_events.txt
5975 |                 binds = scope:other_country
|                         ^^^^^^^^^^^^^^^^^^^
--> [MOD] common/on_actions/gbbf_pulse_on_actions.txt
527 |         5 = eqfm_balkans.700 # Diplomat Offers Mediation
|             ^^^^^^^^^^^^^^^^ <-- triggered from here
431 |         eqfm_balkan_powder_keg_involved_pulse
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
32 |         eqfm_balkan_powder_keg_monthly_pulse
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
2 | on_monthly_pulse_country = {
| ^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here

error(strict-scopes): scope:eqfm_senusiyya_state_region_scope might not be available here
--> [MOD] events/7-01_eqfm_senusiyya_events.txt
1187 |         scope:eqfm_senusiyya_state_region_scope = {
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/on_actions/gbbf_pulse_on_actions.txt
548 |         5 = eqfm_senusiyya.110
|             ^^^^^^^^^^^^^^^^^^ <-- triggered from here
33 |         eqfm_senusiyya_pulse
|         ^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
2 | on_monthly_pulse_country = {
| ^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here
= Info: available names are eqfm_senusiyya_state_scope

error(strict-scopes): scope:eqfm_senusiyya_expedition_leader_scope might not be available here
--> [MOD] events/7-01_eqfm_senusiyya_events.txt
2165 |     left_icon = scope:eqfm_senusiyya_expedition_leader_scope
|                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/journal_entries/7-01_eqfm_senusiyya.txt
335 |                 trigger_event = eqfm_senusiyya.303
|                                 ^^^^^^^^^^^^^^^^^^ <-- triggered from here
272 | je_eqfm_senusiyya_expedition = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here
= Info: available names are eqfm_expedition_loc_scope, journal_entry or target

error(unknown-field): unknown field `on_opened_soundeffect`
--> [MOD] events/7-01_eqfm_senusiyya_events.txt
2577 |         on_opened_soundeffect = "event:/SFX/Events/africa/diplomats_negotiating"
|         ^^^^^^^^^^^^^^^^^^^^^

error(strict-scopes): scope:eqfm_karadag_tur_leader might not be available here
--> [MOD] events/7-01_eqfm_senusiyya_events.txt
3188 |             scope:eqfm_karadag_tur_leader = {
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/journal_entries/7-01_eqfm_senusiyya.txt
372 |             5 = eqfm_senusiyya.321
|                 ^^^^^^^^^^^^^^^^^^ <-- triggered from here
272 | je_eqfm_senusiyya_expedition = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here

error(strict-scopes): scope:eqfm_jack_sparrow_scope might not be available here
--> [MOD] events/7-11_eqfm_pirates_events.txt
90 |     left_icon = scope:eqfm_jack_sparrow_scope
|                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/journal_entries/7-11_eqfm_pirates.txt
50 |             id = eqfm_pirates.001
|                  ^^^^^^^^^^^^^^^^ <-- triggered from here
1 | je_eqfm_pirates_of_the_adriatic = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here
= Info: available names are journal_entry or target

error(strict-scopes): scope:egyptian_crisis_scope might not be available here
--> [Vic3] events/egyptian_crisis_events.txt
44 |         scope:egyptian_crisis_scope = {
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/journal_entries/3-00_turkfm_sick_man.txt
165 |             egyptian_crisis_events.1
|             ^^^^^^^^^^^^^^^^^^^^^^^^ <-- triggered from here
111 | je_turkfm_sick_man_syria = {
| ^^^^^^^^^^^^^^^^^^^^^^^^ <-- scopes initialized here
= Info: available names are dlc_grefm, egyptian_crisis_state, journal_entry or target

warning(scopes): `var:eqfm_balkan_powder_keg_language_ban_culture_var` produces culture but expected religion
--> [MOD] common/decisions/7-00_eqfm_balkans_decisions.txt
136 |                 religion = var:eqfm_balkan_powder_keg_language_ban_culture_var
|                            ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(validation): unexpected comparator >=
--> [MOD] common/journal_entries/1-00_grefm_greece.txt
46 |                 var:grefm_tyranny_var >= 84
|                 ^^^^^^^^^^^^^^^^^^^^^

warning(scopes): `country_has_primary_culture` is for country but scope seems to be none
--> [MOD] common/journal_entries/2-02_balkfm_yugoslavia.txt
10 |         country_has_primary_culture = cu:serb
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^
1 | je_balkfm_serbia_and_montenegro = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scope was supplied by the game engine

warning(scopes): `country_has_primary_culture` is for country but scope seems to be none
--> [MOD] common/journal_entries/2-02_balkfm_yugoslavia.txt
172 |             country_has_primary_culture = cu:serb
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^
162 | je_balkfm_unification_of_yugoslavia = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scope was supplied by the game engine

warning(scopes): `country_has_primary_culture` is for country but scope seems to be none
--> [MOD] common/journal_entries/2-02_balkfm_yugoslavia.txt
173 |             country_has_primary_culture = cu:croat
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^
162 | je_balkfm_unification_of_yugoslavia = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scope was supplied by the game engine

warning(scopes): `country_has_primary_culture` is for country but scope seems to be none
--> [MOD] common/journal_entries/2-02_balkfm_yugoslavia.txt
174 |             country_has_primary_culture = cu:bosniak
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^
162 | je_balkfm_unification_of_yugoslavia = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scope was supplied by the game engine

warning(scopes): `country_has_primary_culture` is for country but scope seems to be none
--> [MOD] common/journal_entries/2-02_balkfm_yugoslavia.txt
175 |             country_has_primary_culture = cu:slovene
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^
162 | je_balkfm_unification_of_yugoslavia = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scope was supplied by the game engine

warning(scopes): `country_has_primary_culture` is for country but scope seems to be none
--> [MOD] common/journal_entries/2-02_balkfm_yugoslavia.txt
176 |             country_has_primary_culture = cu:bulgarian
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^
162 | je_balkfm_unification_of_yugoslavia = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scope was supplied by the game engine

warning(scopes): `any_scope_state` is for country, strategic region, front, state region or theater but scope seems to be none
--> [MOD] common/journal_entries/5-00_haykfm_highlands.txt
11 |         any_scope_state = {
|         ^^^^^^^^^^^^^^^
1 | je_haykfm_highlands = {
| ^^^^^^^^^^^^^^^^^^^ <-- scope was supplied by the game engine

warning(scopes): `create_com_progress_bar` expects scope to be country but scope seems to be none
--> [MOD] common/journal_entries/5-00_haykfm_highlands.txt
55 |         create_com_progress_bar = {
|         ^^^^^^^^^^^^^^^^^^^^^^^
--> [CMF] common/scripted_effects/com_struct.txt
2 |     create_character = {
|     ^^^^^^^^^^^^^^^^ <-- expected scope was deduced from `create_character` here
--> [CMF] common/scripted_effects/com_progressbar_effects.txt
22 |                 create_struct = {
|                 ^ <-- from here
69 |     initialize_com_progress_bar = {
|     ^ <-- from here
--> [MOD] common/journal_entries/5-00_haykfm_highlands.txt
55 |         create_com_progress_bar = {
|         ^ <-- from here
1 | je_haykfm_highlands = {
| ^^^^^^^^^^^^^^^^^^^ <-- actual scope was supplied by the game engine

warning(scopes): `any_scope_state` is for country, strategic region, front, state region or theater but scope seems to be none
--> [MOD] common/journal_entries/7-00_eqfm_balkans.txt
17 |         any_scope_state = {
|         ^^^^^^^^^^^^^^^
1 | je_eqfm_balkan_powder_keg = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scope was supplied by the game engine

warning(scopes): `any_scope_state` is for country, strategic region, front, state region or theater but scope seems to be none
--> [MOD] common/journal_entries/7-01_eqfm_senusiyya.txt
9 |         any_scope_state = {
|         ^^^^^^^^^^^^^^^
1 | je_eqfm_senusiyya = {
| ^^^^^^^^^^^^^^^^^ <-- scope was supplied by the game engine

warning(scopes): `any_scope_state` is for country, strategic region, front, state region or theater but scope seems to be none
--> [MOD] common/journal_entries/7-11_eqfm_pirates.txt
11 |         any_scope_state = {
|         ^^^^^^^^^^^^^^^
1 | je_eqfm_pirates_of_the_adriatic = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- scope was supplied by the game engine

warning(scopes): `this` produces none but expected country
--> [MOD] common/journal_entries/7-12_eqfm_karadag.txt
11 |             c:MON ?= this
|                      ^^^^
1 | je_eqfm_karadag = {
| ^^^^^^^^^^^^^^^ <-- scope was supplied by the game engine

warning(scopes): `this` produces none but expected country
--> [MOD] common/journal_entries/7-12_eqfm_karadag.txt
12 |             c:BOS ?= this
|                      ^^^^
1 | je_eqfm_karadag = {
| ^^^^^^^^^^^^^^^ <-- scope was supplied by the game engine

warning(scopes): `this` produces none but expected country
--> [MOD] common/journal_entries/7-12_eqfm_karadag.txt
13 |             c:TUR ?= this
|                      ^^^^
1 | je_eqfm_karadag = {
| ^^^^^^^^^^^^^^^ <-- scope was supplied by the game engine

warning(missing-localization): missing english localization key notification_turkfm_tanzimat_started_tooltip
--> [MOD] common/messages/3-01_turkfm_tanzimat_messages.txt
1 | turkfm_tanzimat_started = {
| ^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_turkfm_armenians_deported_tooltip
--> [MOD] common/messages/3-02_turkfm_milletindir_messages.txt
1 | turkfm_armenians_deported = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_turkfm_expulsions_protested_tooltip
--> [MOD] common/messages/3-02_turkfm_milletindir_messages.txt
7 | turkfm_expulsions_protested = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_mgrbfm_floods_mitigated_tooltip
--> [MOD] common/messages/4-00_mgrbfm_egypt_messages.txt
1 | mgrbfm_floods_mitigated = {
| ^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_mgrbfm_red_sea_claimed_tooltip
--> [MOD] common/messages/4-00_mgrbfm_egypt_messages.txt
7 | mgrbfm_red_sea_claimed = {
| ^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senussi_ghosted_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
2 | eqfm_senussi_ghosted = {
| ^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senussi_entrenched_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
8 | eqfm_senussi_entrenched = {
| ^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senussi_urbanized_up_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
14 | eqfm_senussi_urbanized_up = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senussi_urbanized_down_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
20 | eqfm_senussi_urbanized_down = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senussi_villages_up_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
26 | eqfm_senussi_villages_up = {
| ^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senussi_villages_down_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
32 | eqfm_senussi_villages_down = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senussi_desert_up_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
38 | eqfm_senussi_desert_up = {
| ^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senussi_desert_down_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
44 | eqfm_senussi_desert_down = {
| ^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senussi_arrival_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
50 | eqfm_senussi_arrival = {
| ^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senusiyya_involved_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
57 | eqfm_senusiyya_involved = {
| ^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senusiyya_uninvolved_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
63 | eqfm_senusiyya_uninvolved = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senusiyya_expelled_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
69 | eqfm_senusiyya_expelled = {
| ^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senusiyya_spreads_to_country_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
75 | eqfm_senusiyya_spreads_to_country = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senusiyya_spreads_to_state_region_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
81 | eqfm_senusiyya_spreads_to_state_region = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_senusiyya_yearly_progress_tooltip
--> [MOD] common/messages/7-01_eqfm_senusiyya_messages.txt
87 | eqfm_senusiyya_yearly_progress = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_jack_sparrow_reincarnated_tooltip
--> [MOD] common/messages/7-11_eqfm_pirates_messages.txt
2 | eqfm_jack_sparrow_reincarnated = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_adriatic_yearly_progress_tooltip
--> [MOD] common/messages/7-11_eqfm_pirates_messages.txt
8 | eqfm_adriatic_yearly_progress = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_smail_aga_iced_tooltip
--> [MOD] common/messages/7-12_eqfm_karadag_messages.txt
2 | eqfm_smail_aga_iced = {
| ^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_bosnia_ejected_tooltip
--> [MOD] common/messages/7-12_eqfm_karadag_messages.txt
9 | eqfm_bosnia_ejected = {
| ^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_ottomans_ejected_tooltip
--> [MOD] common/messages/7-12_eqfm_karadag_messages.txt
15 | eqfm_ottomans_ejected = {
| ^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_expeditionary_force_arrives_tooltip
--> [MOD] common/messages/7-12_eqfm_karadag_messages.txt
22 | eqfm_expeditionary_force_arrives = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_expeditionary_force_withdraws_tooltip
--> [MOD] common/messages/7-12_eqfm_karadag_messages.txt
28 | eqfm_expeditionary_force_withdraws = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_noble_released_tooltip
--> [MOD] common/messages/7-12_eqfm_karadag_messages.txt
34 | eqfm_noble_released = {
| ^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_noble_captured_tooltip
--> [MOD] common/messages/7-12_eqfm_karadag_messages.txt
40 | eqfm_noble_captured = {
| ^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_folk_hero_killed_tooltip
--> [MOD] common/messages/7-12_eqfm_karadag_messages.txt
46 | eqfm_folk_hero_killed = {
| ^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_village_skirmish_tooltip
--> [MOD] common/messages/7-12_eqfm_karadag_messages.txt
52 | eqfm_village_skirmish = {
| ^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_villages_burned_tooltip
--> [MOD] common/messages/7-12_eqfm_karadag_messages.txt
58 | eqfm_villages_burned = {
| ^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_noble_beheaded_tooltip
--> [MOD] common/messages/7-12_eqfm_karadag_messages.txt
64 | eqfm_noble_beheaded = {
| ^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_desert_raids_halted_tooltip
--> [MOD] common/messages/7-13_eqfm_desert_messages.txt
1 | eqfm_desert_raids_halted = {
| ^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key notification_eqfm_yearly_progress_tooltip
--> [MOD] common/messages/7-13_eqfm_desert_messages.txt
7 | eqfm_yearly_progress = {
| ^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key grefm_value_from_literary_tradition
--> [MOD] common/script_values/1-10_grefm_greek_nationalism_values.txt
526 |         desc = grefm_value_from_literary_tradition
|                ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(scopes): `gbbf_has_rumelian_culture_trigger` expects scope to be character, pop, new combat unit or political movement but scope seems to be country
--> [MOD] common/script_values/7-00_eqfm_balkans_values.txt
139 |                 gbbf_has_rumelian_culture_trigger = no
|                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_triggers/0-00_gbbf_general_triggers.txt
57 |             culture ?= cu:greek
|             ^^^^^^^ <-- expected scope was deduced from `culture` here
--> [MOD] common/script_values/7-00_eqfm_balkans_values.txt
138 |                 overlord ?= {
|                 ^^^^^^^^ <-- actual scope was deduced from `overlord` here

warning(scopes): `gbbf_has_rumelian_culture_trigger` expects scope to be character, pop, new combat unit or political movement but scope seems to be country
--> [MOD] common/script_values/7-00_eqfm_balkans_values.txt
203 |                 gbbf_has_rumelian_culture_trigger = no
|                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_triggers/0-00_gbbf_general_triggers.txt
57 |             culture ?= cu:greek
|             ^^^^^^^ <-- expected scope was deduced from `culture` here
--> [MOD] common/script_values/7-00_eqfm_balkans_values.txt
202 |                 overlord ?= {
|                 ^^^^^^^^ <-- actual scope was deduced from `overlord` here

warning(validation): expected yes or no
--> [MOD] common/script_values/7-00_eqfm_balkans_values.txt
319 |                 round = 0.01
|                         ^^^^

warning(scopes): `turkfm_young_turks_progress_value` expects scope to be country but scope seems to be journal entry
--> [MOD] common/scripted_effects/3-01_turkfm_tanzimat_effects.txt
458 |             value = turkfm_young_turks_progress_value
|                     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/script_values/3-01_turkfm_tanizmat_values.txt
445 |             add = government_legitimacy
|                   ^^^^^^^^^^^^^^^^^^^^^ <-- expected scope was deduced from `government_legitimacy` here
--> [MOD] common/scripted_effects/3-01_turkfm_tanzimat_effects.txt
455 |     scope:journal_entry = {
|     ^^^^^^^^^^^^^^^^^^^ <-- actual scope was deduced from the scope's name

warning(scopes): `eqfm_state_region_loyalist_fraction_value` expects scope to be country, culture, state or interest group but scope seems to be state region
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
169 |             value = eqfm_state_region_loyalist_fraction_value
|                     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/script_values/7-00_eqfm_balkans_values.txt
352 |     every_scope_pop = {
|     ^^^^^^^^^^^^^^^ <-- expected scope was deduced from `every_scope_pop` here
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
166 |     every_state_region_in_rumelia = {
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- actual scope was deduced from `every_state_region_in_rumelia` here

warning(scopes): `eqfm_state_region_radical_fraction_value` expects scope to be country, culture, state or interest group but scope seems to be state region
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
173 |             value = eqfm_state_region_radical_fraction_value
|                     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/script_values/7-00_eqfm_balkans_values.txt
377 |     every_scope_pop = {
|     ^^^^^^^^^^^^^^^ <-- expected scope was deduced from `every_scope_pop` here
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
166 |     every_state_region_in_rumelia = {
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- actual scope was deduced from `every_state_region_in_rumelia` here

warning(modifiers): `state_pop_support_movement_radical_mult` is a modifier for state and will not flow from political movement scope
--> [Vic3] common/static_modifiers/00_ip3_03_modifiers.txt
168 |     state_pop_support_movement_radical_mult = 0.25
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
1350 |                 name = eastern_crisis_movement_attraction
|                        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
1340 |             every_political_movement = {
|             ^^^^^^^^^^^^^^^^^^^^^^^^ <-- scope was deduced from `every_political_movement` here
= Info: valid modifiers are for political movement
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `state_pop_support_movement_cultural_minority_mult` is a modifier for state and will not flow from political movement scope
--> [Vic3] common/static_modifiers/00_ip3_03_modifiers.txt
169 |     state_pop_support_movement_cultural_minority_mult = 0.50
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
1350 |                 name = eastern_crisis_movement_attraction
|                        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
1340 |             every_political_movement = {
|             ^^^^^^^^^^^^^^^^^^^^^^^^ <-- scope was deduced from `every_political_movement` here
= Info: valid modifiers are for political movement
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(missing-localization): missing english localization key modifier_eocfm_schismatic
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
323 | modifier_eocfm_schismatic = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_eocfm_ignored_dissent
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
326 | modifier_eocfm_ignored_dissent = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_eocfm_purged_ecclesiarchy
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
329 | modifier_eocfm_purged_ecclesiarchy = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_eocfm_fast_tracking_bishops
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
332 | modifier_eocfm_fast_tracking_bishops = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_eocfm_conceded_to_traditionalists
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
335 | modifier_eocfm_conceded_to_traditionalists = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_eocfm_retained_ecclesiarchy
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
338 | modifier_eocfm_retained_ecclesiarchy = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_eocfm_monk_smackdown_tolerated
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
341 | modifier_eocfm_monk_smackdown_tolerated = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_eocfm_agitator_delay
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
344 | modifier_eocfm_agitator_delay = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_eocfm_autocephaly_granted
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
347 | modifier_eocfm_autocephaly_granted = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_eocfm_autocephaly_abandoned
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
350 | modifier_eocfm_autocephaly_abandoned = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_eocfm_expelled_metropolitan
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
353 | modifier_eocfm_expelled_metropolitan = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_eocfm_accepted_conversion
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
356 | modifier_eocfm_accepted_conversion = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_eocfm_ruler_accepted_conversion
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
359 | modifier_eocfm_ruler_accepted_conversion = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_eocfm_refused_conversion
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
362 | modifier_eocfm_refused_conversion = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_eocfm_ruler_refused_conversion
--> [MOD] common/static_modifiers/0_gbbf_technical_modifiers.txt
365 | modifier_eocfm_ruler_refused_conversion = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key modifier_balkfm_economic_reforms
--> [MOD] common/static_modifiers/2-06_balkfm_romania_modifiers.txt
13 | modifier_balkfm_economic_reforms = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key state_pop_support_movement_land_reform_mult_desc
--> [MOD] common/static_modifiers/4-00_mgrbfm_egypt_modifiers.txt
49 |     state_pop_support_movement_land_reform_mult = 0.10
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(modifiers): `country_prestige_add` is a modifier for country and will not flow from state scope
--> [MOD] common/static_modifiers/7-00_eqfm_balkans_modifiers.txt
295 |     country_prestige_add = 50
|     ^^^^^^^^^^^^^^^^^^^^
--> [MOD] events/7-00_eqfm_balkans_events.txt
194 |                 name = modifier_eqfm_rumelia_secured
|                        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
189 |         every_scope_state = {
|         ^^^^^^^^^^^^^^^^^ <-- scope was deduced from `every_scope_state` here
= Info: valid modifiers are for battle, building, state, tax, unit (combat), goods
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `country_authority_mult` is a modifier for country and will not flow from state scope
--> [MOD] common/static_modifiers/7-00_eqfm_balkans_modifiers.txt
296 |     country_authority_mult = 0.25
|     ^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] events/7-00_eqfm_balkans_events.txt
194 |                 name = modifier_eqfm_rumelia_secured
|                        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
189 |         every_scope_state = {
|         ^^^^^^^^^^^^^^^^^ <-- scope was deduced from `every_scope_state` here
= Info: valid modifiers are for battle, building, state, tax, unit (combat), goods
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `country_prestige_mult` is a modifier for country and will not flow from state scope
--> [MOD] common/static_modifiers/7-00_eqfm_balkans_modifiers.txt
303 |     country_prestige_mult = -0.10
|     ^^^^^^^^^^^^^^^^^^^^^
--> [MOD] events/7-00_eqfm_balkans_events.txt
235 |                 name = modifier_eqfm_rumelia_lost
|                        ^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
230 |         every_scope_state = {
|         ^^^^^^^^^^^^^^^^^ <-- scope was deduced from `every_scope_state` here
= Info: valid modifiers are for battle, building, state, tax, unit (combat), goods
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `country_authority_mult` is a modifier for country and will not flow from state scope
--> [MOD] common/static_modifiers/7-00_eqfm_balkans_modifiers.txt
304 |     country_authority_mult = -0.10
|     ^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] events/7-00_eqfm_balkans_events.txt
235 |                 name = modifier_eqfm_rumelia_lost
|                        ^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
230 |         every_scope_state = {
|         ^^^^^^^^^^^^^^^^^ <-- scope was deduced from `every_scope_state` here
= Info: valid modifiers are for battle, building, state, tax, unit (combat), goods
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `interest_group_in_opposition_approval_add` is a modifier for interest group and will not flow from state scope
--> [MOD] common/static_modifiers/7-00_eqfm_balkans_modifiers.txt
307 |     interest_group_in_opposition_approval_add = -5
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] events/7-00_eqfm_balkans_events.txt
235 |                 name = modifier_eqfm_rumelia_lost
|                        ^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
230 |         every_scope_state = {
|         ^^^^^^^^^^^^^^^^^ <-- scope was deduced from `every_scope_state` here
= Info: valid modifiers are for battle, building, state, tax, unit (combat), goods
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(missing-localization): missing english localization key political_movement_character_attraction_mult
--> [MOD] common/static_modifiers/7-00_eqfm_balkans_modifiers.txt
400 |     political_movement_character_attraction_mult = -0.25
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key political_movement_character_attraction_mult_desc
--> [MOD] common/static_modifiers/7-00_eqfm_balkans_modifiers.txt
400 |     political_movement_character_attraction_mult = -0.25
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key political_movement_character_attraction_mult
--> [MOD] common/static_modifiers/7-00_eqfm_balkans_modifiers.txt
419 |     political_movement_character_attraction_mult = 0.25
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key political_movement_character_attraction_mult_desc
--> [MOD] common/static_modifiers/7-00_eqfm_balkans_modifiers.txt
419 |     political_movement_character_attraction_mult = 0.25
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key political_movement_character_attraction_mult
--> [MOD] common/static_modifiers/7-00_eqfm_balkans_modifiers.txt
464 |     political_movement_character_attraction_mult = 0.50
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key political_movement_character_attraction_mult_desc
--> [MOD] common/static_modifiers/7-00_eqfm_balkans_modifiers.txt
464 |     political_movement_character_attraction_mult = 0.50
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key political_movement_character_attraction_mult
--> [MOD] common/static_modifiers/7-00_eqfm_balkans_modifiers.txt
482 |     political_movement_character_attraction_mult = -0.50
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(missing-localization): missing english localization key political_movement_character_attraction_mult_desc
--> [MOD] common/static_modifiers/7-00_eqfm_balkans_modifiers.txt
482 |     political_movement_character_attraction_mult = -0.50
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(modifiers): `country_senusiyya_influence_growth_add` is a modifier for country and will not flow from interest group scope
--> [MOD] common/static_modifiers/7-01_eqfm_senusiyya_modifiers.txt
72 |     country_senusiyya_influence_growth_add =  0.1
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] events/7-01_eqfm_senusiyya_events.txt
1564 |                 name = modifier_eqfm_senusiyya_welcomed
|                        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
1562 |         ig:ig_devout = {
|         ^^^^^^^^^^^^ <-- scope was deduced from `ig:ig_devout` here
= Info: valid modifiers are for interest group
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `state_radicals_from_political_movements_mult` is a modifier for state and will not flow from interest group scope
--> [MOD] common/static_modifiers/7-01_eqfm_senusiyya_modifiers.txt
74 |     state_radicals_from_political_movements_mult = 0.05
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] events/7-01_eqfm_senusiyya_events.txt
1564 |                 name = modifier_eqfm_senusiyya_welcomed
|                        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
1562 |         ig:ig_devout = {
|         ^^^^^^^^^^^^ <-- scope was deduced from `ig:ig_devout` here
= Info: valid modifiers are for interest group
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `interest_group_amenability_add` is a modifier for interest group and will not flow from state scope
--> [MOD] common/static_modifiers/7-01_eqfm_senusiyya_modifiers.txt
151 |     interest_group_amenability_add = -25
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] events/7-01_eqfm_senusiyya_events.txt
1846 |                 name = modifier_eqfm_preaching_orthodoxy_ig
|                        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
--> [MOD] common/scripted_effects/7-01_eqfm_senusiyya_effects.txt
824 |     random_scope_state = {
|     ^^^^^^^^^^^^^^^^^^ <-- scope was deduced from `random_scope_state` here
= Info: valid modifiers are for battle, building, state, tax, unit (combat), goods
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `interest_group_pop_attraction_mult` is a modifier for interest group and will not flow from state scope
--> [MOD] common/static_modifiers/7-01_eqfm_senusiyya_modifiers.txt
152 |     interest_group_pop_attraction_mult = 0.25
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] events/7-01_eqfm_senusiyya_events.txt
1846 |                 name = modifier_eqfm_preaching_orthodoxy_ig
|                        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
--> [MOD] common/scripted_effects/7-01_eqfm_senusiyya_effects.txt
824 |     random_scope_state = {
|     ^^^^^^^^^^^^^^^^^^ <-- scope was deduced from `random_scope_state` here
= Info: valid modifiers are for battle, building, state, tax, unit (combat), goods
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `country_clergymen_pol_str_mult` is a modifier for country and will not flow from interest group scope
--> [MOD] common/static_modifiers/7-01_eqfm_senusiyya_modifiers.txt
157 |     country_clergymen_pol_str_mult = 0.10
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] events/7-01_eqfm_senusiyya_events.txt
1852 |                 name = modifier_eqfm_preaching_orthodoxy_country
|                        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
1850 |         ig:ig_devout = {
|         ^^^^^^^^^^^^ <-- scope was deduced from `ig:ig_devout` here
= Info: valid modifiers are for interest group
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `country_prestige_add` is a modifier for country and will not flow from character scope
--> [MOD] common/static_modifiers/7-11_eqfm_pirates_modifiers.txt
10 |     country_prestige_add = 25
|     ^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_effects/7-11_eqfm_pirates_effects.txt
286 |             name = modifier_eqfm_completed_adriatic_expedition
|                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
258 |     random_scope_character = {
|     ^^^^^^^^^^^^^^^^^^^^^^ <-- scope was deduced from `random_scope_character` here
= Info: valid modifiers are for battle, character, unit (combat)
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `state_trade_advantage_mult` is a modifier for state and will not flow from character scope
--> [MOD] common/static_modifiers/7-11_eqfm_pirates_modifiers.txt
11 |     state_trade_advantage_mult = 0.05
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_effects/7-11_eqfm_pirates_effects.txt
286 |             name = modifier_eqfm_completed_adriatic_expedition
|                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
258 |     random_scope_character = {
|     ^^^^^^^^^^^^^^^^^^^^^^ <-- scope was deduced from `random_scope_character` here
= Info: valid modifiers are for battle, character, unit (combat)
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `character_interception_add` is a modifier for character and will not flow from country scope
--> [MOD] common/static_modifiers/7-11_eqfm_pirates_modifiers.txt
55 |     character_interception_add = 1
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] events/7-11_eqfm_pirates_events.txt
3556 |             name = modifier_eqfm_corsair_recruits
|                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
3497 |     type = country_event
|            ^^^^^^^^^^^^^ <-- scope was supplied by the game engine
= Info: valid modifiers are for battle, building, country, interest group, political movement, state, tax, unit, goods, military formation
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `character_convoy_raiding_mult` is a modifier for character and will not flow from country scope
--> [MOD] common/static_modifiers/7-11_eqfm_pirates_modifiers.txt
56 |     character_convoy_raiding_mult = 0.25
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] events/7-11_eqfm_pirates_events.txt
3556 |             name = modifier_eqfm_corsair_recruits
|                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
3497 |     type = country_event
|            ^^^^^^^^^^^^^ <-- scope was supplied by the game engine
= Info: valid modifiers are for battle, building, country, interest group, political movement, state, tax, unit, goods, military formation
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `country_prestige_add` is a modifier for country and will not flow from character scope
--> [MOD] common/static_modifiers/7-13_eqfm_desert_modifiers.txt
16 |     country_prestige_add = 25
|     ^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_effects/7-13_eqfm_desert_effects.txt
106 |             name = modifier_eqfm_completed_desert_expedition
|                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
99 |     every_scope_character = {
|     ^^^^^^^^^^^^^^^^^^^^^ <-- scope was deduced from `every_scope_character` here
= Info: valid modifiers are for battle, character, unit (combat)
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(modifiers): `country_legitimacy_base_add` is a modifier for country and will not flow from character scope
--> [MOD] common/static_modifiers/7-13_eqfm_desert_modifiers.txt
17 |     country_legitimacy_base_add = 5
|     ^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_effects/7-13_eqfm_desert_effects.txt
106 |             name = modifier_eqfm_completed_desert_expedition
|                    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- from this temporary modifier
99 |     every_scope_character = {
|     ^^^^^^^^^^^^^^^^^^^^^ <-- scope was deduced from `every_scope_character` here
= Info: valid modifiers are for battle, character, unit (combat)
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

warning(missing-localization): missing english localization key gaudi_capital_expansion_level_4_modifier
--> [MOD] common/static_modifiers/zz_gbbf_placeholder_modifiers.txt
1 | gaudi_capital_expansion_level_4_modifier = {
| ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(scopes): `eqfm_cleanup_karadag_effect` expects root to be country, state, strategic region or market but root seems to be none
--> [MOD] common/treaty_articles/gbbf_cease_raiding.txt
29 |             eqfm_cleanup_karadag_effect = yes
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [Vic3] common/script_values/event_values.txt
60 |     value = root.gdp
|                  ^^^ <-- expected root was deduced from `gdp` here
--> [MOD] common/treaty_articles/gbbf_cease_raiding.txt
27 |     on_entry_into_force = {
|     ^^^^^^^^^^^^^^^^^^^ <-- actual root was supplied by the game engine

warning(scopes): `eqfm_cleanup_karadag_effect` expects root to be country, state, strategic region or market but root seems to be none
--> [MOD] common/treaty_articles/gbbf_cease_raiding.txt
32 |             eqfm_cleanup_karadag_effect = yes
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [Vic3] common/script_values/event_values.txt
60 |     value = root.gdp
|                  ^^^ <-- expected root was deduced from `gdp` here
--> [MOD] common/treaty_articles/gbbf_cease_raiding.txt
27 |     on_entry_into_force = {
|     ^^^^^^^^^^^^^^^^^^^ <-- actual root was supplied by the game engine

warning(scopes): expected bool
--> [MOD] events/1-00_grefm_greece_events.txt
459 |             value = 0
|                     ^

warning(scopes): expected bool
--> [MOD] events/1-00_grefm_greece_events.txt
599 |             value = 0
|                     ^

warning(validation): unexpected comparator >=
--> [MOD] events/1-00_grefm_greece_events.txt
1950 |         var:grefm_tyranny_var >= 60
|         ^^^^^^^^^^^^^^^^^^^^^                                                                                                                 ^

warning(scopes): `eqfm_balkan_powder_keg_rumelian_radicals_effect` expects scope to be state but scope seems to be country
--> [MOD] events/7-00_eqfm_balkans_events.txt
2517 |             eqfm_balkan_powder_keg_rumelian_radicals_effect = {
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
1790 |         add_radicals_in_state = {
|         ^^^^^^^^^^^^^^^^^^^^^ <-- expected scope was deduced from `add_radicals_in_state` here
--> [MOD] events/7-00_eqfm_balkans_events.txt
2517 |             eqfm_balkan_powder_keg_rumelian_radicals_effect = {
|             ^ <-- from here
2502 |                 owner = {
|                 ^^^^^ <-- actual scope was deduced from `owner` here

warning(scopes): `add_religion_standard_of_living_modifier` is for state but scope seems to be country
--> [MOD] events/7-00_eqfm_balkans_events.txt
2520 |             add_religion_standard_of_living_modifier = {
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
2502 |                 owner = {
|                 ^^^^^ <-- scope was deduced from `owner` here

warning(scopes): `scope:eqfm_balkan_culture_scope` produces culture but expected religion
--> [MOD] events/7-00_eqfm_balkans_events.txt
3203 |                 religion = scope:eqfm_balkan_culture_scope
|                            ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
1661 |         culture = {
|         ^^^^^^^ <-- scope was deduced from `culture` here

warning(scopes): `scope:eqfm_balkan_culture_scope` produces culture but expected religion
--> [MOD] events/7-00_eqfm_balkans_events.txt
3212 |             religion = scope:eqfm_balkan_culture_scope
|                        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
1661 |         culture = {
|         ^^^^^^^ <-- scope was deduced from `culture` here

warning(scopes): `scope:eqfm_balkan_culture_scope` produces culture but expected religion
--> [MOD] events/7-00_eqfm_balkans_events.txt
3283 |             religion = scope:eqfm_balkan_culture_scope
|                        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_effects/7-00_eqfm_balkans_effects.txt
1661 |         culture = {
|         ^^^^^^^ <-- scope was deduced from `culture` here

warning(validation): value expects one of strongly_disapprove, disapprove, neutral, approve or strongly_approve
--> [MOD] events/7-00_eqfm_balkans_events.txt
4503 |                 value > 0
|                         ^

warning(validation): value expects one of strongly_disapprove, disapprove, neutral, approve or strongly_approve
--> [MOD] events/7-00_eqfm_balkans_events.txt
4507 |                 value <= 0
|                          ^

warning(validation): value expects one of strongly_disapprove, disapprove, neutral, approve or strongly_approve
--> [MOD] events/7-00_eqfm_balkans_events.txt
4511 |                 value <= 0
|                          ^

warning(validation): value expects one of strongly_disapprove, disapprove, neutral, approve or strongly_approve
--> [MOD] events/7-00_eqfm_balkans_events.txt
4528 |                 value > 0
|                         ^

warning(validation): value expects one of strongly_disapprove, disapprove, neutral, approve or strongly_approve
--> [MOD] events/7-00_eqfm_balkans_events.txt
4532 |                 value > 0
|                         ^

warning(scopes): `gbbf_country_has_rumelian_culture_trigger` expects scope to be country but scope seems to be state
--> [MOD] events/7-00_eqfm_balkans_events.txt
5967 |                 gbbf_country_has_rumelian_culture_trigger = no
|                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_triggers/0-00_gbbf_general_triggers.txt
97 |             country_has_primary_culture = cu:greek
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- expected scope was deduced from `country_has_primary_culture` here
--> [MOD] events/7-00_eqfm_balkans_events.txt
5965 |                 any_scope_state = {
|                 ^^^^^^^^^^^^^^^ <-- actual scope was deduced from `any_scope_state` here

warning(scopes): `gbbf_country_has_rumelian_culture_trigger` expects scope to be country but scope seems to be state
--> [MOD] events/7-00_eqfm_balkans_events.txt
5979 |                 gbbf_country_has_rumelian_culture_trigger = no
|                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_triggers/0-00_gbbf_general_triggers.txt
97 |             country_has_primary_culture = cu:greek
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- expected scope was deduced from `country_has_primary_culture` here
--> [MOD] events/7-00_eqfm_balkans_events.txt
5977 |                 any_scope_state = {
|                 ^^^^^^^^^^^^^^^ <-- actual scope was deduced from `any_scope_state` here

warning(scopes): `gbbf_country_has_rumelian_culture_trigger` expects scope to be country but scope seems to be state
--> [MOD] events/7-00_eqfm_balkans_events.txt
6005 |                 gbbf_country_has_rumelian_culture_trigger = no
|                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_triggers/0-00_gbbf_general_triggers.txt
97 |             country_has_primary_culture = cu:greek
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- expected scope was deduced from `country_has_primary_culture` here
--> [MOD] events/7-00_eqfm_balkans_events.txt
6003 |                 any_scope_state = {
|                 ^^^^^^^^^^^^^^^ <-- actual scope was deduced from `any_scope_state` here

warning(scopes): `gbbf_country_has_rumelian_culture_trigger` expects scope to be country but scope seems to be state
--> [MOD] events/7-00_eqfm_balkans_events.txt
6028 |                 gbbf_country_has_rumelian_culture_trigger = no
|                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
--> [MOD] common/scripted_triggers/0-00_gbbf_general_triggers.txt
97 |             country_has_primary_culture = cu:greek
|             ^^^^^^^^^^^^^^^^^^^^^^^^^^^ <-- expected scope was deduced from `country_has_primary_culture` here
--> [MOD] events/7-00_eqfm_balkans_events.txt
6026 |                 any_scope_state = {
|                 ^^^^^^^^^^^^^^^ <-- actual scope was deduced from `any_scope_state` here

warning(validation): value expects one of strongly_disapprove, disapprove, neutral, approve or strongly_approve
--> [MOD] events/7-11_eqfm_pirates_events.txt
1457 |                 value > 0
|                         ^

warning(scopes): `scope:turkfm_cattaro_scope` produces province but expected country, state or state region
--> [MOD] events/7-12_eqfm_karadag_events.txt
519 |     placement = scope:turkfm_cattaro_scope
|                 ^^^^^^^^^^^^^^^^^^^^^^^^^^
556 |         p:x90A0E0 = {
|         ^^^^^^^^^ <-- scope was deduced from `p:x90A0E0` here

warning(scopes): `scope:turkfm_cattaro_scope` produces province but expected country, state or state region
--> [MOD] events/7-12_eqfm_karadag_events.txt
616 |     placement = scope:turkfm_cattaro_scope
|                 ^^^^^^^^^^^^^^^^^^^^^^^^^^
653 |         p:x90A0E0 = {
|         ^^^^^^^^^ <-- scope was deduced from `p:x90A0E0` here

warning(gui): expected SetRoot
--> [MOD] gui/gbbf_popup.gui
26 |             visible = "[And4(
|                              ^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/02_balkfm/2-02_balkfm_yugoslavia_l_english.yml
27 |  je_balkfm_yugoslav_nationalism_status: "Integrating [GetPlayer.MakeScope.Var('balkfm_yugoslav_promotion_target_var').GetName] (#v [GetPlayer.MakeScope.Var('balkfm_yugoslav_promotion_var').GetName] %#!)"
|                                                                                                                       ^^^^^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/02_balkfm/2-02_balkfm_yugoslavia_l_english.yml
27 |  je_balkfm_yugoslav_nationalism_status: "Integrating [GetPlayer.MakeScope.Var('balkfm_yugoslav_promotion_target_var').GetName] (#v [GetPlayer.MakeScope.Var('balkfm_yugoslav_promotion_var').GetName] %#!)"
|                                                                                                                                                                                              ^^^^^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/02_balkfm/2-02_balkfm_yugoslavia_l_english.yml
124 |  balkfm_value_from_minority_support: "the $gbbf_movement_support$ behind the [GetPlayer.MakeScope.Var('je_balkfm_yugoslav_nationalism').Var('balkfm_yugoslav_promotion_target_var').GetName] cultural $gbbf_movement$"
|                                                                                                                                                                                     ^^^^^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/02_balkfm/2-02_balkfm_yugoslavia_l_english.yml
126 |  balkfm_value_from_promoted_culture_radicals: "the average $gbbf_radicalism$ of [GetPlayer.MakeScope.Var('je_balkfm_yugoslav_nationalism').Var('balkfm_yugoslav_promotion_target_var').GetName] $gbbf_pops$ in [ROOT.GetCountry.GetNameNoFlag]"
|                                                                                                                                                                                        ^^^^^^^

warning(localization): The substitution parameter $balkfm_ali_rizvanbegovic_waxed_name$ is not defined anywhere as a key.
--> [MOD] localization/english/02_balkfm/2-07_balkfm_bosnia_l_english.yml
28 |  notification_balkfm_ali_rizvanbegovic_waxed_tooltip: "#header $balkfm_ali_rizvanbegovic_waxed_name$#!$gbbf_linebreak_normal$$balkfm_ali_rizvanbegovic_waxed_desc$"
|                                                                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $balkfm_ali_rizvanbegovic_waxed_desc$ is not defined anywhere as a key.
--> [MOD] localization/english/02_balkfm/2-07_balkfm_bosnia_l_english.yml
28 |  notification_balkfm_ali_rizvanbegovic_waxed_tooltip: "#header $balkfm_ali_rizvanbegovic_waxed_name$#!$gbbf_linebreak_normal$$balkfm_ali_rizvanbegovic_waxed_desc$"
|                                                                                                                               ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $balkfm_ali_rizvanbegovic_ascendant_name$ is not defined anywhere as a key.
--> [MOD] localization/english/02_balkfm/2-07_balkfm_bosnia_l_english.yml
31 |  notification_balkfm_ali_rizvanbegovic_ascendant_tooltip: "#header $balkfm_ali_rizvanbegovic_ascendant_name$#!$gbbf_linebreak_normal$$balkfm_ali_rizvanbegovic_ascendant_desc$"
|                                                                     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $balkfm_ali_rizvanbegovic_ascendant_desc$ is not defined anywhere as a key.
--> [MOD] localization/english/02_balkfm/2-07_balkfm_bosnia_l_english.yml
31 |  notification_balkfm_ali_rizvanbegovic_ascendant_tooltip: "#header $balkfm_ali_rizvanbegovic_ascendant_name$#!$gbbf_linebreak_normal$$balkfm_ali_rizvanbegovic_ascendant_desc$"
|                                                                                                                                       ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $gbbf_bio_ali_of_jannina$ is not defined anywhere as a key.
--> [MOD] localization/english/02_balkfm/2-08_balkfm_albania_events_l_english.yml
3 |  balkfm_albania.001.d: "For several decades, the people of $ALB_YAN$ enjoyed a degree of prosperity and relative autonomy from the $turkfm_porte$ while under the rule of $gbbf_bio_ali_of_jannina$. Following his deposition, the [GetCulture('albanian').GetName] people have come under the same pressures as other subjects in [GetGeographicRegion('geographic_region_rumelia').GetName]. While they are divided amongst several regions and lack a cohesive national movement, there a growing sense of an \"$ALB$\" that goes beyond being a mere subject of Constantinople."
|                                                                                                                                                                            ^^^^^^^^^^^^^^^^^^^^^^^

warning(datafunctions): GetCityName cannot follow a State promote
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_events_l_english.yml
274 |  eqfm_balkans.310.b: "[ROOT.GetCountry.GetCapital.GetCityName] will not be extorted."
|                                                   ^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
266 |  notification_eqfm_overtaxed_desc: "Aggressive taxation by the [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration in [SCOPE.sState('eqfm_balkan_state_scope').GetName] has caused outcry against their rule. $eqfm_escalation_increase_medium$"
|                                                                                                                                                                                                                                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
269 |  notification_eqfm_tax_break_desc: "In response to outcry by impacted communities, the [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has granted relief from taxation in rural areas of [SCOPE.sState('eqfm_balkan_state_scope').GetName]. $eqfm_deescalation_increase_medium$"
|                                                                                                                                                                                                                                                                      ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
272 |  notification_eqfm_plague_desc: "A massive plague outbreak has occurred in the [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective]'s $gbbf_georegion_rumelia_adj$ holdings centered in [SCOPE.sState('eqfm_balkan_state_scope').GetName]. $eqfm_escalation_increase_medium$"
|                                                                                                                                                                                                                                                ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
275 |  notification_eqfm_quarantine_desc: "In response to a plague outbreak centered in [SCOPE.sState('eqfm_balkan_state_scope').GetName], the [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has imposed checkpoints and quarantines to stem the spread of the disease. $eqfm_escalation_increase_small$"
|                                                                                                                                                                                                                                                                                             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
278 |  notification_eqfm_protection_firman_denied_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetName] has directly rebuked the authority of the Ecumenical Patriarch to directly intervene in abuses against the [GetReligion('orthodox').GetName] Millet. $eqfm_escalation_increase_small$"
|                                                                                                                                                                                                                                                                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
281 |  notification_eqfm_protection_firman_granted_desc: "In response to pleas by the Ecumenical Patriarch, the [SCOPE.sCountry('eqfm_post_origin_scope').GetName] has increased the legal protections for the [GetReligion('orthodox').GetName] Millet. $eqfm_deescalation_increase_small$"
|                                                                                                                                                                                                                                                     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
284 |  notification_eqfm_translations_denied_desc: "A request to provide legal documents in the local languages has been categorically rejected by the [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration in [SCOPE.sState('eqfm_balkan_state_scope').GetName]. $eqfm_escalation_increase_small$"
|                                                                                                                                                                                                                                                                                ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
287 |  notification_eqfm_translations_provided_desc: "Responding to a request for better access to administrative documents in [SCOPE.sState('eqfm_balkan_state_scope').GetName], the [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has set up translation services for communities in [SCOPE.sState('eqfm_balkan_state_scope').GetName]. $eqfm_deescalation_increase_small$"
|                                                                                                                                                                                                                                                                                                                                                               ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
302 |  notification_eqfm_domineering_bey_desc: "A local Bey in [SCOPE.sState('eqfm_balkan_state_scope').GetName] has provoked outrage by endeavouring to enforce absolute control over [SCOPE.sState('eqfm_balkan_state_scope').GetName]. $eqfm_escalation_increase_small$"
|                                                                                                                                                                                                                                      ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
305 |  notification_eqfm_recalled_bey_desc: "A local Bey in [SCOPE.sState('eqfm_balkan_state_scope').GetName] has been recalled by the $turkfm_porte$ for attempting to enforce absolute control over [SCOPE.sState('eqfm_balkan_state_scope').GetName]. $eqfm_deescalation_increase_medium$"
|                                                                                                                                                                                                                                                     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
308 |  notification_eqfm_protected_churches_desc: "In response to repeated disruptions of church services in [SCOPE.sState('eqfm_balkan_state_scope').GetName], the $turkfm_porte$ has increased protections for churches and provided reparations. $eqfm_deescalation_increase_small$"
|                                                                                                                                                                                                                                                ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
311 |  notification_eqfm_churches_disrupted_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has ignored repeated disruptions of [GetReligion('orthodox').GetName] church services in [SCOPE.sState('eqfm_balkan_state_scope').GetName]. $eqfm_escalation_increase_medium$"
|                                                                                                                                                                                                                                                                      ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
314 |  notification_eqfm_schools_denied_desc: "A widespread request for local school funding in [SCOPE.sState('eqfm_balkan_state_scope').GetName] has been denied by the $turkfm_porte$. $eqfm_escalation_increase_medium$"
|                                                                                                                                                                                     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
317 |  notification_eqfm_schools_approved_desc: "A widespread request for local school funding in [SCOPE.sState('eqfm_balkan_state_scope').GetName] has been granted by the [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration. $eqfm_deescalation_increase_small$"
|                                                                                                                                                                                                                                                ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_large$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
320 |  notification_eqfm_newspaper_censored_desc: "A popular revivalist newspaper has been subjected to widespread censorship by the [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration. $eqfm_escalation_increase_large$"
|                                                                                                                                                                                                         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
323 |  notification_eqfm_newspaper_ignored_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has ignored the sudden rise in popularity of revivalist printings spreading from [SCOPE.sState('eqfm_balkan_state_scope').GetName]. $eqfm_escalation_increase_medium$"
|                                                                                                                                                                                                                                                             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
359 |  notification_eqfm_gunrunners_arrested_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has arrested several gunrunners operating in [SCOPE.sState('eqfm_balkan_state_scope').GetName]. $eqfm_deescalation_increase_medium$"
|                                                                                                                                                                                                                           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
362 |  notification_eqfm_gunrunners_released_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has pardoned several gunrunners operating in [SCOPE.sState('eqfm_balkan_state_scope').GetName]. $eqfm_escalation_increase_medium$"
|                                                                                                                                                                                                                           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
367 |  notification_eqfm_stores_ransacked_desc: "Shopkeepers across [SCOPE.sState('eqfm_balkan_state_scope').GetCityHubName] in [SCOPE.sState('eqfm_balkan_state_scope').GetName] have found their businesses ransacked and looted by anti-Christian mobs. $eqfm_escalation_increase_medium$"
|                                                                                                                                                                                                                                                       ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
370 |  notification_eqfm_millets_enforced_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has ordered the reinforcement of outdated millet classifications in the Balkans. $eqfm_escalation_increase_medium$"
|                                                                                                                                                                                                         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_large$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
373 |  notification_eqfm_millets_eroding_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has permitted discussions regarding outdated millet classifications in the Balkans. $eqfm_deescalation_increase_large$"
|                                                                                                                                                                                                           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
376 |  notification_eqfm_jack_sparrowed_desc: "Pirate [GetPlayer.MakeScope.Var('eqfm_jack_sparrow_var').GetCharacter.GetLastName] has looted several shipping merchants and sold many of their number into slavery. $eqfm_escalation_increase_small$"
|                                                                                                                                                                                                                ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
379 |  notification_eqfm_crowds_dispersed_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has forcibly broken up mass protests in [SCOPE.sState('eqfm_balkan_state_scope').GetName]. $eqfm_escalation_increase_medium$"
|                                                                                                                                                                                                                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
382 |  notification_eqfm_crowds_tolerated_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has shown remarkable tolerance for mass protests in [SCOPE.sState('eqfm_balkan_state_scope').GetName]. $eqfm_escalation_increase_small$"
|                                                                                                                                                                                                                               ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_large$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
385 |  notification_eqfm_crowds_beaten_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has violently broken up protests across [SCOPE.sState('eqfm_balkan_state_scope').GetName]s. Dozens are presumed dead with many more injuries. $eqfm_escalation_increase_large$"
|                                                                                                                                                                                                                                                                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_large$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
388 |  notification_eqfm_local_language_ban_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has begun to curtail the use of minority languages in official contexts. $eqfm_escalation_increase_large$"
|                                                                                                                                                                                                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_large$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
391 |  notification_eqfm_languages_protected_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has moved to protect the use of minority languages in legal and official contexts. $eqfm_deescalation_increase_large$"
|                                                                                                                                                                                                              ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_very_large$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
394 |  notification_eqfm_total_language_ban_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has imposed a ban on the use of any language other than Turkish in any official context. $eqfm_escalation_increase_very_large$"
|                                                                                                                                                                                                                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
409 |  notification_eqfm_jack_sparrow_strikes_again_desc: "Pirate [GetPlayer.MakeScope.Var('eqfm_jack_sparrow_var').GetCharacter.GetLastName] has seized on instability in $gbbf_georegion_rumelia$ to launch a massive series of convoy raids. $eqfm_escalation_increase_small$"
|                                                                                                                                                                                                                                            ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
412 |  notification_eqfm_ignored_displacement_desc: "Minority communities in $gbbf_georegion_rumelia$ have found themselves displaced by Muslim settlers. $eqfm_escalation_increase_medium$"
|                                                                                                                                                      ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
415 |  notification_eqfm_restricted_displacement_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has acted to reduce the displacement of minority communities by Muslim settlement. $eqfm_deescalation_increase_medium$"
|                                                                                                                                                                                                                  ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_very_large$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
418 |  notification_eqfm_supported_displacement_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has acted to accelerate the displacement of minority communities by Muslim settlement. $eqfm_escalation_increase_very_large$"
|                                                                                                                                                                                                                     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
421 |  notification_eqfm_brigandage_dispute_desc: "Brigands in the Balkans have caused a diplomatic incident by raiding into Ottoman lands and then retreating back beyond the border. $eqfm_escalation_increase_small$"
|                                                                                                                                                                                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
424 |  notification_eqfm_brigandage_ignored_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has ignored the problem of cross-country Brigandage originating from our hinterlands. $eqfm_deescalation_increase_small$"
|                                                                                                                                                                                                                ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
427 |  notification_eqfm_brigandage_conciliation_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has ignored the problem of cross-country Brigandage in the Balkans. $eqfm_deescalation_increase_small$"
|                                                                                                                                                                                                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
432 |  notification_eqfm_churches_burned_desc: "Muslim mobs have burned several churches across the Balkans. $eqfm_escalation_increase_medium$"
|                                                                                                         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_small$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
435 |  notification_eqfm_church_reparations_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has ateqfm_church_reparationsted to defuse tensions by providing reparations for recent church burnings in the Balkans. $eqfm_escalation_increase_small$"
|                                                                                                                                                                                                                                                  ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
438 |  notification_eqfm_speaker_lynched_desc: "A popular speaker was recently lynched by a Muslim mob in the Balkans. $eqfm_escalation_increase_medium$"
|                                                                                                                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
441 |  notification_eqfm_lynch_arrests_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has acted quickly to arrest several mobsters involved in a lynching in the Balkans. $eqfm_deescalation_increase_medium$"
|                                                                                                                                                                                                         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
444 |  notification_eqfm_brigandage_desc: "The violent actions of Brigands in the Balkans have eroded confidence in the authority of the [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration. $eqfm_escalation_increase_medium$"
|                                                                                                                                                                                                             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
447 |  notification_eqfm_garrison_deployed_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has deployed several garrisons into the countryside to combat Brigandage. $eqfm_deescalation_increase_medium$"
|                                                                                                                                                                                                   ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
450 |  notification_eqfm_ports_burned_desc: "An angry mob has put a major port city to the torch and massively disrupted trade in the Balkans. $eqfm_escalation_increase_medium$"
|                                                                                                                                           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_escalation_increase_large$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
453 |  notification_eqfm_blood_libel_ignored_desc: "Muslim firebrands in the Balkans have begun to disseminate blood libel against Christian communities. $eqfm_escalation_increase_large$"
|                                                                                                                                                      ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_medium$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
456 |  notification_eqfm_blood_libel_suppressed_desc: "The [SCOPE.sCountry('eqfm_post_origin_scope').GetAdjective] administration has dispatched Dragomans across the Balkans to combat the spread of blood libel against Christian communities. $eqfm_deescalation_increase_medium$"
|                                                                                                                                                                                                                                             ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $eqfm_deescalation_increase_large$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
460 |  notification_eqfm_tensions_defused_desc: "Our diplomats have successfully mediated tensions in the Balkans. $eqfm_deescalation_increase_large$"
|                                                                                                               ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

warning(localization): The substitution parameter $gbbf_georegion_rumelia.$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-00_eqfm_balkans_l_english.yml
585 |  eqfm_uninvolved_desc: "A level of $gbbf_balkans_involvement$ in the $eqfm_balkan_situation$. #bold Interloper#! An #bold Uninvolved#! [concept_country] has no stake in the outcome of the $eqfm_balkan_situation$. These countries are unaffected by the events in $gbbf_georegion_rumelia.$\n\n@information! #italic Different Actions will be available to you depending on your level of involvement.#!"
|                                                                                                                                                                                                                                                                       ^^^^^^^^^^^^^^^^^^^^^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/07_eqfm/7-01_eqfm_senusiyya_events_l_english.yml
101 |  eqfm_senusiyya.300.d: "The [ROOT.GetCountry.GetRuler.GetPrimaryRoleTitle] has authorized the deployment of an $eqfm_expedition$ to expel the $eqfm_senusiyya_movement$ from [GetPlayer.MakeScope.Var('eqfm_senusiyya_expedition_var').GetName]. All that remains is to appoint a leader."
|                                                                                                                                                                                                                                        ^^^^^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/07_eqfm/7-01_eqfm_senusiyya_events_l_english.yml
107 |  eqfm_senusiyya.301.t: "$eqfm_senusiyya_expedition$ Arrives in [GetPlayer.MakeScope.Var('eqfm_senusiyya_expedition_var').GetName]"
|                                                                                                                          ^^^^^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/07_eqfm/7-01_eqfm_senusiyya_events_l_english.yml
108 |  eqfm_senusiyya.301.d: "After taking a few weeks to muster and gather supplies, [SCOPE.sCharacter('eqfm_senusiyya_expedition_leader_scope').GetFullName] has departed into [GetPlayer.MakeScope.Var('eqfm_senusiyya_expedition_var').GetName] in support of our efforts to expel the $eqfm_senusiyya$."
|                                                                                                                                                                                                                                      ^^^^^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/07_eqfm/7-01_eqfm_senusiyya_events_l_english.yml
112 |  eqfm_senusiyya.302.d: "Our $eqfm_desert_expedition$ was sighted returning from the depths of the [GetPlayer.MakeScope.Var('eqfm_senusiyya_expedition_var').GetName]. They bring with them the tragic news of the death of its leader out in the wastes."
|                                                                                                                                                             ^^^^^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/07_eqfm/7-01_eqfm_senusiyya_events_l_english.yml
115 |  eqfm_senusiyya.303.t: "$eqfm_senusiyya_expedition$ Withdraws from [GetPlayer.MakeScope.Var('eqfm_senusiyya_expedition_var').GetName]"
|                                                                                                                              ^^^^^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/07_eqfm/7-01_eqfm_senusiyya_events_l_english.yml
116 |  eqfm_senusiyya.303.d: "Citing a lack of provisions and attritional losses, [SCOPE.sCharacter('eqfm_senusiyya_expedition_leader_scope').GetFullName] has returned from the depths of [GetPlayer.MakeScope.Var('eqfm_senusiyya_expedition_var').GetName]."
|                                                                                                                                                                                                                                                ^^^^^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/07_eqfm/7-01_eqfm_senusiyya_events_l_english.yml
125 |  eqfm_senusiyya.310.d: "Scouts have discovered a lodge for $eqfm_senusiyya$ activity in [GetPlayer.MakeScope.Var('eqfm_senusiyya_expedition_var').GetName]. The expedition awaits [SCOPE.sCharacter('eqfm_senusiyya_expedition_leader_scope').GetPrimaryRoleTitle] [SCOPE.sCharacter('eqfm_senusiyya_expedition_leader_scope').GetLastName]'s orders."
|                                                                                                                                                   ^^^^^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/07_eqfm/7-01_eqfm_senusiyya_events_l_english.yml
130 |  eqfm_senusiyya.311.d: "While surveying the area near a settlement in [GetPlayer.MakeScope.Var('eqfm_senusiyya_expedition_var').GetName], [SCOPE.sCharacter('eqfm_senusiyya_expedition_leader_scope').GetPrimaryRoleTitle] [SCOPE.sCharacter('eqfm_senusiyya_expedition_leader_scope').GetLastName] has become aware that local villagers have withheld critical information regarding $eqfm_senusiyya$ activities in the area. Worse, there is reason to suspect they have intentionally misdirected the $eqfm_senusiyya_expedition$."
|                                                                                                                                 ^^^^^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/07_eqfm/7-01_eqfm_senusiyya_events_l_english.yml
164 |  eqfm_senusiyya.317.d: "While navigating through the deserts in [GetPlayer.MakeScope.Var('eqfm_senusiyya_expedition_var').GetName], the $eqfm_senusiyya_expedition$ has been ambushed "
|                                                                                                                           ^^^^^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/07_eqfm/7-01_eqfm_senusiyya_events_l_english.yml
170 |  eqfm_senusiyya.318.d: "A settlement in [GetPlayer.MakeScope.Var('eqfm_senusiyya_expedition_var').GetName] has refused to provide lodging for the $eqfm_senusiyya_expedition$. As an act of defiance, this threatens the legitimacy of [ROOT.GetCountry.GetNameNoFlag]'s designs on the desert."
|                                                                                                   ^^^^^^^

warning(datafunctions): GetName cannot follow a Scope promote
--> [MOD] localization/english/07_eqfm/7-01_eqfm_senusiyya_l_english.yml
279 |  eqfm_complete_senusiyya_expedition: "The $eqfm_senusiyya_movement$ will be #bold expelled#! from [GetPlayer.MakeScope.Var('eqfm_senusiyya_expedition_var').GetName] never to return"
|                                                                                                                                                             ^^^^^^^

warning(datafunctions): GetName cannot follow a Character promote
--> [MOD] localization/english/07_eqfm/7-12_eqfm_karadag_events_l_english.yml
47 |  eqfm_karadag.014.d: "Our captives of the Border Conflict languish in our prisons. Their fates rest of the whims of the [ROOT.GetCountry.GetRuler.GetName]."
|                                                                                                                                                   ^^^^^^^

warning(localization): The substitution parameter $$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-12_eqfm_karadag_l_english.yml
20 |  je_eqfm_karadag_on_complete_montenegro: "If completed with a #v $MON_ADJ$#! victory, Triggers the Event #white #bold $$#!#!"
|                                                                                                                        ^

warning(localization): The substitution parameter $$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-12_eqfm_karadag_l_english.yml
21 |  je_eqfm_karadag_on_complete_bosnia: "If completed with a #v $BOS_ADJ$#! victory, Triggers the Event #white #bold $$#!#!"
|                                                                                                                    ^

warning(localization): The substitution parameter $$ is not defined anywhere as a key.
--> [MOD] localization/english/07_eqfm/7-12_eqfm_karadag_l_english.yml
22 |  je_eqfm_karadag_on_complete_ottomans: "If completed with a #v $TUR_ADJ$#! victory, Triggers the Event #white #bold $$#!#!"
|                                                                                                                      ^

warning(datafunctions): MakeScope cannot follow a Scope promote
--> [MOD] localization/english/07_eqfm/7-12_eqfm_karadag_l_english.yml
27 |  je_eqfm_karadag_captives_count: "\n@information! [ROOT.GetCountry.GetNameNoFlag] is currently holding [ROOT.MakeScope.Var('eqfm_captured_nobles_var').GetValue] nobles captive."
|                                                                                                              ^^^^^^^^^

warning(logic): OR with only one item inside is probably not what you intended
--> [MOD] events/1-00_grefm_greece_events.txt
339 |                 OR = {
|                      ^
^^^^^^^^^^^^^^^^^

warning(logic): OR with only one item inside is probably not what you intended
--> [MOD] events/1-00_grefm_greece_events.txt
496 |                 OR = {
^^^^^^^^^^^^^^^^^

warning(logic): OR with only one item inside is probably not what you intended
--> [MOD] events/1-00_grefm_greece_events.txt
1033 |                 OR = {
|                      ^
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

untidy(modifiers): script only modifier does not use a valid prefix
--> [MOD] common/character_traits/gbbf_skill_traits.txt
12 |         ship_ship_type_submarine_hull_damage_mult = 0.1
|         ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
= Info: consider using a prefix to ensure the modifier flows to the intended scope
= Wiki: https://vic3.paradoxwikis.com/Modifier_types#Modifier_type_flow

fatal: 0, error: 145, warning: 380, untidy: 1, tips: 0

# Lyrics-aligned solo singing dataset

## Link to the dataset: 
https://drive.google.com/open?id=1hGuE0Drv3tbN-YNRDzJJMHfzKH6e4O2A

===========================================================================

### Dataset used for the paper:
Chitralekha Gupta, Rong Tong, Haizhou Li, and Ye Wang, "Semi-supervised lyrics and solo-singing alignment", ISMIR 2018.
Please cite this paper if you happen to use this dataset for your research. Thanks!

Code for generating this dataset is at: https://github.com/chitralekha18/AutomaticSungLyricsAnnotation_ISMIR2018.git

Note: This dataset has been made available only for research purposes.

### Description of the dataset:
The dataset folder contains Train and Test folders.
These folders contain audio segments extracted from Smule's DAMP dataset.
Train contains 35662 wavfiles, while Test contains 1697 wavfiles.
The files train.txt and test.txt contain the automatically generated lyric transcriptions of these audio files (please refer to the paper for further details of the procedure of obtaining them).

The Train folder now contains more files than reported in the paper, that can be used by the MIR community for further research.

For any queries, contact: chitralekha@u.nus.edu

===========================================================================
## TRAIN SET:
Contains 132 unique songs from DAMP dataset.
The list of unique songs:
['_losing_my_religion', '_apologize', '_seasons_of_love', '_broken_wings', '_friends_in_low_places', '_part_of_your_world', '_home_daughtry', '_ben', '_top_of_the_world', '_yesterday_once_more', '_one_of_us', '_head_over_feet', '_always_be_my_baby', '_burn', '_bad_romance', '_born_this_way', '_mamas_broken_heart', '_santeria', '_my_girl', '_locked_out_of_heaven', '_this_love', '_you_know_im_no_good', '_rehab', '_and_i_am_telling_you', '_somebody_to_love', '_adore_you', '_achy_breaky_heart', '_worshipper', '_making_memories_of_us', '_landslide', '_wanted', '_you_make_me_feel_brand', '_can_you_feel_love_tngt', '_airplanes', '_hit_me_wth_your_best_sht', '_baby_one_more_time', '_glad_you_came', '_bed_intruder', '_runaway_train', '_twinkle_twinkle', '_the_worst', '_when_a_man_loves_a_woman', '_merry_christmas_darling', '_brave', '_you_raise_me_up', '_dont_rain_on_my_parade', '_boyfriend', '_disturbia', '_i_believe_i_can_fly', '_god_bless_the_usa', '_counting_stars', '_im_yours', '_ironic', '_heart_attack', '_all_the_small_things', '_kiss_me_', '_wont_go_home_without_you', '_girls_just_want_have_fun', '_the_way_you_look_tony', '_whatcha_say', '_dark_side', '_you_are_not_alone', '_weve_only_just_begun', '_billionaire', '_eye_of_the_tiger', '_baby_bieber', '_give_your_heart_a_break', '_cooler_than_me', '_a_holly_jolly_christmas', '_didnt_we_almost_have_it', '_i_wanna_dance_with_smbdy', '_she_will_be_loved', '_baby_love', '_happy', '_adorn', '_my_heart_will_go_on', '_ill_be', '_circle_of_life', '_best_song_ever', '_as_long_as_you_love_me', '_all_out_of_love', '_alone_heart', '_paparazzi', '_dont_know_why', '_shes_always_a_woman', '_just_the_way_you_are', '_wherever_you_will_go', '_kiss_the_girl', '_want_u_back', '_hand_in_my_pocket', '_under_the_sea', '_luka', '_forget_you', '_two_black_cadillacs', '_a_whole_new_world', '_you_are_so_beautiful', '_let_it_go', '_zombie', '_summer', '_hey_brother', '_newyork_newyork', '_hallelujah', '_stay_rihanna', '_poker_face', '_all_i_want_for_christmas', '_more_than_this', '_i_will_survive', '_bye_bye_bye', '_say_somethin', '_frere_jacques', '_treasure_bm', '_radioactive', '_i_look_to_you', '_what_makes_you_beautiful', '_closing_time', '_just_the_way_you_are_bm', '_o_holy_night', '_summertime_gershwin', '_grenade', '_blue_christmas', '_blurred_lines', '_how_great_thou_art', '_just_a_kiss', '_i_want_to_hold_your_hand', '_climax', '_true_colors', '_hashtag_that_power', '_bingo', '_if_i_aint_got_you', '_all_american_girl', '_how_you_remind_me', '_gorilla']


Number of 10 seconds segments of each song respectively:
[534,210, 175, 194, 322, 288, 413, 84, 303, 285, 372, 466, 131, 465, 502, 702, 460, 321, 168, 267, 462, 243, 503, 199, 231, 195, 396, 151, 280, 89, 417, 121, 182, 348, 243, 395, 283, 571, 422, 100, 705, 147, 170, 185, 160, 217, 137, 399, 493, 374, 529, 314, 340, 285, 255, 190, 394, 99, 59, 447, 146, 307, 136, 461, 288, 474, 418, 363, 185, 23, 213, 461, 218, 540, 223, 40, 244, 226, 353, 418, 499, 160, 291, 84, 304, 175, 146, 244, 612, 274, 297, 314, 478, 355, 116, 8, 123, 130, 224, 243, 186, 236, 369, 500, 161, 446, 322, 469, 337, 76, 415, 291, 23, 543, 226, 319, 6, 6, 371, 42, 273, 13, 395, 6, 4, 8, 273, 34, 3, 8, 64, 31]

==============================================================================

## TEST SET:
Contains 25 unique songs from DAMP dataset (different from the train set)
['_true_colors', '_hashtag_that_power', '_drink_a_beer', '_never_say_never', '_i_look_to_you', '_say_something_great_big', '_faith', '_gorilla', '_summertime_gershwin', '_all_i_want_for_christmas', '_blurred_lines', '_if_i_aint_got_you', '_i_want_to_hold_your_hand', '_how_you_remind_me', '_counting_stars', '_didnt_we_almost_have_it', '_let_it_go', '_all_american_girl', '_you_know_im_no_good', '_boyfriend', '_climax', '_and_i_am_telling_you', '_cooler_than_me', '_a_whole_new_world', '_airplanes']

Number of 10 seconds segments of each song respectively:
[54, 73, 94, 81, 38, 43, 200, 59, 61, 4, 103, 18, 137, 175, 3, 21, 81, 68, 7, 100, 67, 22, 71, 34, 83]

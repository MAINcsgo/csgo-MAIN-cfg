# csgo-MAIN-cfg
Updated version of my csgo config 


>> UPDATED 2.DEC 2018

RESOLUTION   		  1024x768 (stretched)
ASPECT RATIO          	  4:3

MOUSE                        SS Rival 300   - 400 CPI (both profiles)

POLLING RATE-              1000Hz
  
  Enhance Pointer Precision: No (Windows mouse settings)
  
  LAUNCH OPTIONS
  
  -tickrate 128 -novid -high +mat_queue_mode 2 +fps_max unlimited -nod3d9ex -nojoy +exec main -panorama -freq 75


// CROSSHAIR

  	cl_crosshairalpha 255;
 	cl_crosshaircolor 1; 
	cl_crosshairdot 0;
 	cl_crosshairgap -2;
 	cl_crosshairsize 3;
 	cl_crosshairstyle 6;
 	cl_crosshairusealpha 1;
 	cl_crosshairthickness 0;
 	cl_crosshair_drawoutline 0;
	
  // Mouse
  
  	 sensitivity "1.95";
 	 zoom_sensitivity_ratio_mouse "1.0";
  	 m_rawinput "1";
 	 m_pitch "0.022";
 	 m_customaccel "0";
 	 m_mouseaccel1 "0";
 	 m_mouseaccel2 "0";
 	 m_mousespeed "0" ;
  
  //Audio
  
  	 snd_deathcamera_volume "0.000000";	
 	 snd_duckerattacktime "0.5";
 	 snd_duckerreleasetime "2.5";
  	 snd_duckerthreshold "0.15";
  	 snd_ducking_off "1";
  	 snd_ducktovolume "0.55";
 	 snd_hrtf_distance_behind "100";
 	 snd_hwcompat "0";
 	 snd_mapobjective_volume "0";
 	 snd_menumusic_volume "0.000000";
 	 snd_mix_async "1";
 	 snd_mix_async_onetime_reset "1";
 	 snd_mixahead "0.025" ;
 	 snd_music_selection "0";
	 snd_music_volume_onetime_reset_2 "1";
	 snd_musicvolume_multiplier_inoverlay "0.000000";
	 snd_mute_losefocus "1";
 	 snd_mvp_volume "0.000000";
	 snd_pitchquality "1";
 	 snd_roundend_volume "0";
 	 snd_roundstart_volume "0";
 	 snd_tensecondwarning_volume "0";
 	 snd_use_hrtf_onetime_reset "0";
 	 sound_device_override "";
  
  // BUY BINDs

	bind "kp_end" "buy deagle;";
	bind "kp_downarrow" "buy ak47; buy m4a1;";
	bind "kp_pgdn" "buy awp;";
	bind "kp_leftarrow" "buy p250;";
	bind "kp_5" "buy tec9; buy fiveseven;";
	bind "kp_multiply" " buy molotov; buy incgrenade;";
	bind "kp_home" " buy hegrenade;";
	bind "kp_uparrow" " buy flashbang;";
	bind "kp_pgup" " buy smokegrenade;";
	bind "kp_plus" " buy vesthelm; buy vest;";
	bind "kp_minus" " buy vest;";
	bind "kp_INS" " buy DEFUSER;";
	
	
 // OTHER BINDs
	
	bind "CapsLock" "R_cleardecals";
	bind "C" "+voicerecord";
	bind "v" "BindToggle" "cl_righthand";
	
	
// JUMPTHROW
	
	alias "+jumpthrow" "+jump;-attack";
	alias "-jumpthrow" "-jump";
	bind "x" "+jumpthrow";
	
// VIEWMODEL
	
	viewmodel_fov "67"
	viewmodel_offset_x "2"
	viewmodel_offset_y "2"
	viewmodel_offset_z "-2"
	cl_viewmodel_shift_left_amt "0"
	cl_viewmodel_shift_right_amt "0"
	cl_bob_lower_amt "0"
	cl_bobamt_lat "0"
	cl_bobamt_vert "0"
	cl_bobcycle "0.98"
	cl_bob_lower_amt "0"
	cl_bobamt_lat "0"
	cl_bobamt_vert "0"
	
	cl_righthand 0;
	
// REST

	fps_max unlimited;
	net_graph "1";
	cl_autohelp "0";
	cl_showhelp "0";
	r_Dynamic 0;
	r_dynamiclighNing 0
	


	
	

host_writeconfig




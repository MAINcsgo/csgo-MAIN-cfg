# csgo-MAIN-cfg
Updated version of my csgo config 


>> UPDATED 15.JAN 2019

RESOLUTION   		  1280x960 (stretched)
ASPECT RATIO          	  4:3

MOUSE                        SS Rival 300   - 400 CPI (both profiles)

POLLING RATE-              1000Hz
  
  Enhance Pointer Precision: No (Windows mouse settings)
  
  LAUNCH OPTIONS
  
  -tickrate 128 -novid -high +mat_queue_mode -1 +fps_max unlimited -nod3d9ex -nojoy +exec main -panorama -freq 75


// CROSSHAIR

  	cl_crosshairalpha 255;
 	cl_crosshaircolor 2; 
	cl_crosshairdot 0;
 	cl_crosshairgap -2;
 	cl_crosshairsize 3;
 	cl_crosshairstyle 4;
 	cl_crosshairusealpha 1;
 	cl_crosshairthickness 0;
 	cl_crosshair_drawoutline 0;
	
  // Mouse
  
  	 sensitivity "2";
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

// Bind are customized for non-numpad keyboards in ENGLISH (USA) Layout

	bind "Uparrow"   "buy deagle;"
	bind "Downarrow" "buy p250;"
	bind "O"   "buy ak47; buy m4a1;"
	bind "I"   "buy awp;"
	bind "J"   "buy molotov; buy incgrenade;"
	bind "H"   "buy hegrenade;"
	bind "K"   "buy flashbang;buy flashbang;"
	bind "L"   "buy smokegrenade;"
	bind "P"   "buy vesthelm; buy vest;"
	bind "  "   "buy vest;"
	bind "n"   "buy DEFUSER;"
	
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
	viewmodel_recoil 0	
	
	cl_righthand 0;
	
// REST

	fps_max unlimited;
	net_graph "1";
	cl_autohelp "0";
	cl_showhelp "0";
	r_Dynamic 0;
	r_dynamiclighNing 0
	+cl_show_team_equipment 1;
	


	
	

host_writeconfig




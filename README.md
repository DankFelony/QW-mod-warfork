# QW-mod-warfork
Warfork QW mod to get this physics work need to have this Command in the pk3.

uint feats = ent.client.get_pmoveFeatures();     uint qw = PMFEAT_DASH | PMFEAT_WALLJUMP | PMFEAT_FWDBUNNY;     ent.client.set_pmoveFeatures(feats &amp; ~qw); 

In void GT_PlayerRespawn

------

If you use hiss hud on discord cyberemperor use this command For to get fully working con_fontSystemFamily FreeSans

------
You can Keep the wallJump if you want just delete the PMFEAT_WALLJUMP from the Parameter, To Enable Walljump back.

Copy And Paste Code into source/gameshared

VQ3# QW mod is done in basewf folder. :D with my custom stuff.

Made Extra stuff custom Crosshair that i am thinking thats missing from this game. an pro quakeworld crosshair like inter2.

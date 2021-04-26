# QW-mod-warfork
Warfork QW mod to get this physics work need to have this Command in the pk3.

uint feats = ent.client.get_pmoveFeatures();     uint qw = PMFEAT_DASH | PMFEAT_WALLJUMP | PMFEAT_FWDBUNNY;     ent.client.set_pmoveFeatures(feats &amp; ~qw); 

In void GT_PlayerRespawn

You can Keep the wallJump if you want just delete the PMFEAT_WALLJUMP from the Parameter

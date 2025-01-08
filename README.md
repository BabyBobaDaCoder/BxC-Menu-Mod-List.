            new ButtonInfo[] { // Main Mods
                new ButtonInfo { buttonText = "Settings", method =() => SettingsMods.EnterSettings(), isTogglable = false, toolTip = "Opens the main settings page for the menu."},
                    new ButtonInfo { buttonText = "Join Discord", method =() => JoinDiscord.JoinDiscordMod(), toolTip = "Joins My Discord Server.", isTogglable = false,},
                    new ButtonInfo { buttonText = "Movement", method =() => Global.MovementMods(), toolTip = "Movement Folder.", isTogglable = false},
                    new ButtonInfo { buttonText = "Ghost Trolling", method =() => Global.GhostTrolling(), toolTip = "Ghost Troll Folder.", isTogglable = false},
                    new ButtonInfo { buttonText = "World Mods", method =() => Global.WorldMods(), toolTip = "World Mods Folder.", isTogglable = false},
                    new ButtonInfo { buttonText = "Rig Mods", method =() => Global.RigMods(), toolTip = "Ghost Troll Folder.", isTogglable = false},
                    new ButtonInfo { buttonText = "Visual Mods", method =() => Global.VisualMods(), toolTip = "World Mods Folder.", isTogglable = false},
                    new ButtonInfo { buttonText = "Advantage Mods", method =() => Global.AdvantageMods(), toolTip = "Advantage Mods Folder.", isTogglable = false},
                    new ButtonInfo { buttonText = "Projectile Mods", method =() => Global.ProjectileMods(), toolTip = "Projectile Mods Folder.", isTogglable = false},
            },

            new ButtonInfo[] { // Settings
                new ButtonInfo { buttonText = "Return to Main", method =() => Global.ReturnHome(), isTogglable = false, toolTip = "Returns to the main page of the menu."},
                new ButtonInfo { buttonText = "Menu", method =() => SettingsMods.MenuSettings(), isTogglable = false, toolTip = "Opens the settings for the menu."},
                new ButtonInfo { buttonText = "World", method =() => SettingsMods.ProjectileSettings(), isTogglable = false, toolTip = "Opens the world settings for the menu."},
            },

            new ButtonInfo[] { // Menu Settings
                new ButtonInfo { buttonText = "Return to Settings", method =() => SettingsMods.EnterSettings(), isTogglable = false, toolTip = "Returns to the main settings page for the menu."},
                new ButtonInfo { buttonText = "Right Hand", enableMethod =() => SettingsMods.RightHand(), disableMethod =() => SettingsMods.LeftHand(), toolTip = "Puts the menu on your right hand."},
                new ButtonInfo { buttonText = "Notifications", enableMethod =() => SettingsMods.EnableNotifications(), disableMethod =() => SettingsMods.DisableNotifications(), enabled = !disableNotifications, toolTip = "Toggles the notifications."},
                new ButtonInfo { buttonText = "FPS Counter", enableMethod =() => SettingsMods.EnableFPSCounter(), disableMethod =() => SettingsMods.DisableFPSCounter(), enabled = fpsCounter, toolTip = "Toggles the FPS counter."},
                new ButtonInfo { buttonText = "Disconnect Button", enableMethod =() => SettingsMods.EnableDisconnectButton(), disableMethod =() => SettingsMods.DisableDisconnectButton(), enabled = disconnectButton, toolTip = "Toggles the disconnect button."},
            },

            new ButtonInfo[] { // Movement Settings
                new ButtonInfo { buttonText = "Return to Main", method =() => Global.ReturnHome(), isTogglable = false, toolTip = "Returns to the main page of the menu."},
            },

            new ButtonInfo[] { // World Settings
                new ButtonInfo { buttonText = "Return to Settings", method =() => SettingsMods.MenuSettings(), isTogglable = false, toolTip = "Opens the settings for the menu."},
                new ButtonInfo { buttonText = "Change Banned Text", method =() => ChangeBannedText.ChangeBannedTextMod(), toolTip = "Changes The Text On Banned Signs."},
                new ButtonInfo { buttonText = "Custom COC", method =() => COC.COCMod(), isTogglable = false, toolTip = "Changes The Text On The COC."},
            },

            new ButtonInfo[] { // Movement Folder
                new ButtonInfo { buttonText = "Return", method =() => Global.ReturnHome(), isTogglable = false, toolTip = "Returns To Main Page Of The Menu."},
                new ButtonInfo { buttonText = "Speed Boost", method =() => SpeedBoost.SpeedBoostMod(), toolTip = "Enables A Slight Speed Boost When Active."},
                new ButtonInfo { buttonText = "Noclip", method =() => Noclip.NoclipMod(), toolTip = "Allows You To Clip Through Things."},
                new ButtonInfo { buttonText = "TP Gun", method =() => TPGun.TPGunMod(), toolTip = "Teleport Gun."},
                new ButtonInfo { buttonText = "Platforms", method =() => Platforms.PlatformMod(), toolTip = "Platforms."},
                new ButtonInfo { buttonText = "Car Monke", method =() => CarMonke.CarMonkeMod(), toolTip = "Become A Car."},
                new ButtonInfo { buttonText = "Spam Platforms", method =() => InvisPlats.InvisPlatformsMod(), toolTip = "Spam Platforms."},
                new ButtonInfo { buttonText = "Fly", method =() => Fly.Flymod(), toolTip = "Enables Flight."},
                new ButtonInfo { buttonText = "PBBV Walk", method =() => PBBVWalk.PBBVWalkMod(), toolTip = "Walk Like PBBV."},
                new ButtonInfo { buttonText = "No Tag Freeze", method =() => NoTagFreeze.NoTagFreezeMod(), toolTip = "Disables Tag Freeze."},
            },

            new ButtonInfo[] { // Ghost Trolling Folder
                new ButtonInfo { buttonText = "Return", method =() => Global.ReturnHome(), isTogglable = false, toolTip = "Returns To Main Page Of The Menu."},
                new ButtonInfo { buttonText = "Spaz", method =() => Spaz.SpazMod(), toolTip = "Spaz Out."},
                new ButtonInfo { buttonText = "Ghost Monke", method =() => GhostMonkey.GhostMonkemod(), toolTip = "Freezes Your Rig."},
                new ButtonInfo { buttonText = "Invis Monke", method =() => InvisMonke.invismonkey(), toolTip = "Makes You Invisible."},
                new ButtonInfo { buttonText = "Anti Report", method =() => AntiReport.AntiReportmod(), toolTip = "Disconnect When Someone Tries To Report You."},
                new ButtonInfo { buttonText = "Long Arms", method =() => LongArms.LongArmsMod(), toolTip = "Makes Your Arms Longer."},
                new ButtonInfo { buttonText = "No Name", method =() => NoName.NoNameMod(), toolTip = "Removes Your Name."},
                new ButtonInfo { buttonText = "No Finger Movement", method =() => NoFingerMovement.NoFinger(), toolTip = "Stops Fingers From Moving."},
                new ButtonInfo { buttonText = "Spaz Head", method =() => SpazHead.SpazHeadMod(), toolTip = "Spaz Out Your Head."},
            },

            new ButtonInfo[] { // World Mods
                new ButtonInfo { buttonText = "Return", method =() => Global.ReturnHome(), isTogglable = false, toolTip = "Returns To Main Page Of The Menu."},
                    new ButtonInfo { buttonText = "Join Code BxCMenu", method =() => JoinCode.JoinCodeBxCMenuMod(), toolTip = "Joins The Menu Code."},
                    new ButtonInfo { buttonText = "Ride Bug", method =() => RideBug.RideBugMod(), toolTip = "Ride Doug The Bug."},
                    new ButtonInfo { buttonText = "Ride Bat", method =() => RideBat.RideBatMod(), toolTip = "Ride Matt The Bat."},
                    new ButtonInfo { buttonText = "Grab Bug", method =() => GrabBug.GrabBugMod(), toolTip = "Grab Doug The Bug."},
                    new ButtonInfo { buttonText = "Grab Bat", method =() => GrabBat.GrabBatMod(), toolTip = "Grab Matt The Bat."},
                    new ButtonInfo { buttonText = "Draw", method =() => Draw.DrawMod(), toolTip = "Draw."},
                    new ButtonInfo { buttonText = "Mute All", method =() => MuteAll.MuteallPlayers(), toolTip = "Mutes Everyone.", isTogglable = false,},
                    new ButtonInfo { buttonText = "Report All", method =() => ReportAll.ReportAllForToxicity(), toolTip = "Reports Everyone.", isTogglable = false,},
                    new ButtonInfo { buttonText = "Bat Size Changer", method =() => BatSizeChanger.BatSizeChangermod(), toolTip = "Changes The Size Of The Bat."},
                    new ButtonInfo { buttonText = "Bug Size Changer", method =() => BugSizeChanger.BugSizeChangermod(), toolTip = "Changes The Size Of The Bug."},
                    new ButtonInfo { buttonText = "Inf Shiny Roxx", method =() => InfShinyRoxx.ManyShinyRocks(), toolTip = "Infinite Shiny Roxx.", isTogglable = false,},
                    new ButtonInfo { buttonText = "Time Set Night", method =() => SetNight.TimeSetNight(), toolTip = "Sets It To Night Time.", isTogglable = false,},
                    new ButtonInfo { buttonText = "Oculus Report Menu", method =() => ReportMenu.OculusReportMenu(), toolTip = "Opens The Oculus Report Menu."},
                    new ButtonInfo { buttonText = "Check If Master", method =() => CheckIfMaster.CheckIFMasterMod(), toolTip = "Checks if your master.", isTogglable = false,},
                    new ButtonInfo { buttonText = "Grab LIV Camera", method =() => GrabCamera.GrabCameraMod(), toolTip = "Grabs LIV Camera."},
                    new ButtonInfo { buttonText = "Disable Network Triggers", method =() => DisableNetworkTriggers.DisableNetworkTriggersMod(), toolTip = "Disables The Network Triggers."},
                    new ButtonInfo { buttonText = "Disable Quit Box", method =() => DisableQuitBox.DisableQuitBoxMod(), toolTip = "Disables The Quit Box Below The Map."},
                    new ButtonInfo { buttonText = "Enable Network Triggers", method =() => EnableNetworkTriggers.EnabledNetworkTriggers(), toolTip = "Enables The Network Triggers."},
                    new ButtonInfo { buttonText = "Enable Quit Box", method =() => EnableQuitBox.EnableQuitBoxMod(), toolTip = "Enables The Quit Box Below The Map."},
            },

            new ButtonInfo[] { // Visual Mods
                new ButtonInfo { buttonText = "Return", method =() => Global.ReturnHome(), isTogglable = false, toolTip = "Returns To Main Page Of The Menu."},
                new ButtonInfo { buttonText = "Tracers", method =() => Tracers.TracersMod(), toolTip = "Tracers Pointing To Every Player."},
                new ButtonInfo { buttonText = "Box Esp", method =() => BoxEspMod.BoxESP(), toolTip = "An ESP In The Shape Of A Box."},
                new ButtonInfo { buttonText = "Xray", method =() => Xray.XrayMod(), toolTip = "See Through Walls.", isTogglable = false,},
                new ButtonInfo { buttonText = "Disable Xray", method =() => DisableXray.DisableXrayMod(), toolTip = "Disables Xray.", isTogglable = false,},
                new ButtonInfo { buttonText = "Beacons", method =() => Beacons.BeaconsMod(), toolTip = "Beacons Above Everyones Heads."},
            },

            new ButtonInfo[] { // Rig Mods
                new ButtonInfo { buttonText = "Return", method =() => Global.ReturnHome(), isTogglable = false, toolTip = "Returns To Main Page Of The Menu."},
                new ButtonInfo { buttonText = "Punch Mod", method =() => PunchMod.BetterPunchMod(), toolTip = "Talk Shit Get Hit."},
                new ButtonInfo { buttonText = "Pregnant", method =() => Pregnant.PregnantMod(), toolTip = "Become Pregnant."},
            },
            
            new ButtonInfo[] { // Projectile Mods
                new ButtonInfo { buttonText = "Return", method =() => Global.ReturnHome(), isTogglable = false, toolTip = "Returns To Main Page Of The Menu."},
                new ButtonInfo { buttonText = "Cum", method =() => Cum.CUMMod(), toolTip = "Cum On People."},
                new ButtonInfo { buttonText = "Pee", method =() => PeeMod.GoBathroom(), toolTip = "Piss On People."},
                new ButtonInfo { buttonText = "Apple Spammer", method =() => AppleSpammer.Applespammmer(), toolTip = "Apple Spammer."},
                new ButtonInfo { buttonText = "Candy Cane Spammer", method =() => CandyCaneGiftSpammer.candycanegiftpammmer(), toolTip = "Candy Cane Spammer."},
                new ButtonInfo { buttonText = "Cloud Spammer", method =() => CloudSpammer.cloudspammmerMod(), toolTip = "Cloud Spammer."},
                new ButtonInfo { buttonText = "Coal Spammer", method =() => CoalGiftSpammer.coalgiftpammmer(), toolTip = "Coal Spammer."},
                new ButtonInfo { buttonText = "Cupid Spammer", method =() => CupidSpammer.cupidspammmerMod(), toolTip = "Cupid Spammer."},
                new ButtonInfo { buttonText = "DeadShot Spammer", method =() => DeadShotSpammer.DeadShotSpammerMod(), toolTip = "DeadShot Spammer."},
                new ButtonInfo { buttonText = "Elf Spammer", method =() => ElfSpammer.elfspammmer(), toolTip = "Elf Spammer."},
                new ButtonInfo { buttonText = "Ice Spammer", method =() => IceSpammer.IceSpammmerMod(), toolTip = "Ice Spammer."},
                new ButtonInfo { buttonText = "Pepper Spammer", method =() => PepperSpammer.pepperspammmer(), toolTip = "Pepper Spammer."},
                new ButtonInfo { buttonText = "Rock Spammer", method =() => RockSpammer.rockspammmer(), toolTip = "Rock Spammer."},
                new ButtonInfo { buttonText = "Roll Gift Spammer", method =() => RollGiftSpammer.rollgiftpammmer(), toolTip = " Roll Gift Spammer."},
                new ButtonInfo { buttonText = "Round Gift Spammer", method =() => RoundGiftSpammer.roundgiftpammmer(), toolTip = "Round Gift Spammer."},
                new ButtonInfo { buttonText = "SlingShot Spammer", method =() => SlingShotSpammer.slingshotspammmermod(), toolTip = "SlingShot Spammer."},
                new ButtonInfo { buttonText = "SnowBall Spammer", method =() => SnowBallSpammer.Snowballspammmer(), toolTip = "SnowBall Spammer."},
                new ButtonInfo { buttonText = "Spider Spammer", method =() => SpiderSpammer.spiderpammmer(), toolTip = "Spider Spammer."},
                new ButtonInfo { buttonText = "Square Gift Spammer", method =() => SquareGiftSpammer.sqaregiftpammmer(), toolTip = "Square Gift Spammer."},
                new ButtonInfo { buttonText = "Water Balloon Spammer", method =() => WaterBalloonSpammer.WaterBallonSpammmerMod(), toolTip = "Water Balloon Spammer."},
            },

            new ButtonInfo[] { // Advantage Mods
                new ButtonInfo { buttonText = "Return", method =() => Global.ReturnHome(), isTogglable = false, toolTip = "Returns To Main Page Of The Menu."},
                new ButtonInfo { buttonText = "Tag All", method =() => TagAll.TagAllMod(), toolTip = "Tags Everyone In The Lobby."},
                new ButtonInfo { buttonText = "Tag Aura", method =() => TagAura.TagAuraMod(), toolTip = "Tags Everyone Around You."},
                new ButtonInfo { buttonText = "Wall Walk", method =() => WallWalk.WallWalkMod(), toolTip = "Walk On Walls."},
            },
        };
    }
}
// All Mods Coded By BabyBoba

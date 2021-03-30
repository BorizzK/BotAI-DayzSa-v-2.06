# BotAI-DayzSa-v-2.11



    Completely redesigned bot orientation system
    Improved bot behavior.
    Improved optimization
    Missions reworked
    Added the ability to open doors (the bot may not open some doors, it cannot open locked doors)

    It is necessary to update all files, server side, client side, as well as mission files.
    Note that the init.c file also contains changes.


	Bot Config
	
	protected int m_botAcuracy = 10;											
	
	protected int BotSolderCountMin =4;  										
	protected int BotSolderCountMax = 6;										
	
	protected int botLootCountMin = 5; 											
	protected int botLootCountMax = 15; 										
	
	protected float Zone_Radius = 1100;										
	
	protected bool isUseCheckPoints = true;										
	protected bool isBotKaratist = false;										
	protected bool onRespawnBot = true;											
	protected bool canUseTrigger = true;										
	protected bool useKilFeed = true;											
	protected bool m_Frendly = true;											
	protected bool onVoice = true;												
	protected int m_spawnBotRadius = 100;										
	protected int m_SpeedPatrol = 2;											
	
	protected int m_TargetDist = 200;

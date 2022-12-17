The UserPermissions.json file contains the base set of user groups and permissions. The UserPermissions.json can be changed while the server is offline in order to setup ranks and their perms. 

By default base user groups such as 'User' (All general users) right through to 'Owner' status is setup. Any user group that has the permission '*' has access to ALL in game commands and this should be used sparingly.

Editing: The most important thing when editing is to ensure that the json architecture is maintained.  Otherwise the server will fail to read the file and not run.

List of all perms. Note that some may not work as expect or work at all.

    BasicUser, 
    DropAllSelf,
    DropAllOthers,
    DeleteAllSelf,
    DeleteAllOthers,
    SpawnAI,
    KillAI,
    SetTime,
    SetMonth,
    SetWeather,
    WeatherOnOff,
    TpToLocation,
    TpToPlayer,
    TpPlayerToMe,
    TpPlayerToPlayer,
    TpPresets,
    GodSelf,
    SuperSprint,
    ServerInfo,
    Give,
    Mute,
    Kick,
    Ban,
    UnBan,
    SetStatsSelf,
    SetStatsOthers,
    KillPlayer,
    SetRank,
    CleanUp,
    Up,
    AlwaysSafeLogOff,
    StuckOthers,
    ChatOff,
    Video,
    Restart
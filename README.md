-- They can't even make configs auto save on GUI, so you gotta config in text manualy :joy_cat::thumbsdown:

_BuyFruitSinper = true -- true / false
_SelectDevil = {"Human-Human: Buddha","Rumble-Rumble","Dragon-Dragon","Soul-Soul","Quake-Quake","String-String","Venom-Venom",'Dark-Dark'}--,"Dragon-Dragon","Soul-Soul","Quake-Quake","String-String","Venom-Venom"
-- _BestSheetUrl= "https://sheet.best/api/sheets/25f4a337-64c0-4c3b-a403-6c47218098db"
_Team = "Pirates"
_FPS_Boost = false
_AutoFarm = false --"Level , Bone"   "Level"  "Bone"
_Fullystats = false
_AutoMeleeWeapon = false
_Make_Melee = {"Superhuman","Electric Claw","Dargon Talon","Sharkman Karate","Death Step"}
_AutoRedeem = false
_RedeemOnLv = 900
_BuyHaki = false
_RandomFruit = false
_StoreFruit = false
_BringFruit = false
_BuyBisento = false
_BuyCommon = false
_Mastery_Farm = false
_Mastery_Mode = "Fruit on 2300"
if game.PlaceId == 2753915549 then -- sea1
   _Farm_Mode = "Level"
   _autoSea2 = false
   _Open_Saber = false
   _Pole_v1 = false
elseif game.PlaceId == 4442272183 then -- sea2
   _AutoMeleeWeapon = false
   _Farm_Mode = "Level"
   _autoSea3 = false
   _Bartilo = false
   _AutoFlower = false
   _AutoDarkbeard = false
   _BuyEctoplasItem = false
   _BuyKabcha = false
   _AutoRaid = false
   _RaidMode = "Awake Skill"-- "Raid Normal" , "Awake Skill"
   _GetFruit_Method = "FruitInventory + BringFruit + Hop"-- "BringFruit" , "BringFruit + Hop" , "FruitInventory" , "FruitInventory + BringFruit" , "FruitInventory + BringFruit + Hop"
elseif game.PlaceId == 7449423635 then -- sea3
   _AutoMeleeWeapon = false
   _Farm_Mode = "Level"
   _BoneTrade = false
   _AutoRaid = false
   _RaidMode = "Awake Skill"-- "Raid Normal" , "Awake Skill"
   _GetFruit_Method = "FruitInventory + BringFruit + Hop"-- "BringFruit" , "BringFruit + Hop" , "FruitInventory" , "FruitInventory + BringFruit" , "FruitInventory + BringFruit + Hop"
   _BuyEctoplasItem = false
   _BuyKabcha = false
   _BuddySword = false
   _AutoScythe = false
   _AutoRipIndra = false
   _Canvander = false
   _AutoCakePrince = false
   _EliteHunt = false
   _Tushita = false
   _Elite_mode = "Yama"
end
_HideUI = false

loadstring(game:HttpGet("https://raw.githubusercontent.com/AltsegoD/scripts/egoD/TableHubCracked.lua"))()

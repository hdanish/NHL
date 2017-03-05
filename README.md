# Description
I initially decided to write a script in order to automate building a recap of a given day's NHL scores and highlights to post on Reddit. Having successfully done that, my next step (TBC) would be to write a bot to automate this posting. Subsequently, I have considering writing a script to scrape more data and store it in a database for future use. Possible ideas include attempting to cluster players based on their stats and salaries (cap hit).

# Sample Output
The following is a sample output that is generated using my script on NHL games for March 4th, 2017 (see notebook). The headings have been slightly modified for this page.

___
##NEW JERSEY DEVILS @ BOSTON BRUINS
### Final score: 2-3


Period|Time|Team|Point getters
|:-:|:-:|:-:|:-:|
2|07:06|BOS|[(PPG) Torey Krug (6) Slap Shot, assists: David Pastrnak (28), Patrice Bergeron (25)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/e899cc94-b38e-45de-a80a-644050b568c3/1488676762822/asset_1800k.mp4)
2|11:48|NJD|[Devante Smith-Pelly (4) Backhand, assists: Steven Santini (5), Kyle Palmieri (22)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/832c0daa-f55e-4e3e-9332-d4480a983c7d/1488677644743/asset_1800k.mp4)
2|18:25|BOS|[Brandon Carlo (6) Backhand, assists: Patrice Bergeron (26), David Backes (18)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/acaa7072-87c7-4073-b9e8-5d903b49d238/1488678532516/asset_1800k.mp4)
3|05:51|NJD|[Kyle Palmieri (20) Snap Shot, assists: Taylor Hall (28)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/9c8f5402-dee6-4450-9184-9bbce718016c/1488680562894/asset_1800k.mp4)
3|08:18|BOS|[Ryan Spooner (11) Wrist Shot, assists: Drew Stafford (10), Frank Vatrano (7)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/42969c92-6176-4d69-b4ae-4991471ef77b/1488680906886/asset_1800k.mp4)


___
##TAMPA BAY LIGHTNING @ BUFFALO SABRES
### Final score: 2-1


Period|Time|Team|Point getters
|:-:|:-:|:-:|:-:|
1|19:48|BUF|[(PPG) Ryan O'Reilly (15) Slap Shot, assists: Rasmus Ristolainen (35), Jack Eichel (26)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/95179922-d842-4098-9085-e4aa35df0833/1488674998947/asset_1800k.mp4)
2|02:37|TBL|[Tyler Johnson (19) Tip-In, assists: Victor Hedman (43), Nikita Kucherov (35)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/6244c59e-b451-402d-b6c7-ba536117cc8f/1488676274710/asset_1800k.mp4)


___
##COLUMBUS BLUE JACKETS @ OTTAWA SENATORS
### Final score: 2-3


Period|Time|Team|Point getters
|:-:|:-:|:-:|:-:|
1|02:17|CBJ|[Brandon Saad (20) Wrist Shot, assists: Zach Werenski (29), Seth Jones (25)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/cf199a2a-9350-45ce-8eb4-7e64618aad36/1488673363036/asset_1800k.mp4)
1|13:25|OTT|[Viktor Stalberg (10) Wrist Shot, assists: Chris Kelly (6), Tommy Wingels (4)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/c19331e5-4e20-4b71-98f6-6be469e6d574/1488674766938/asset_1800k.mp4)
2|08:59|OTT|[Erik Karlsson (11) Wrist Shot, assists: Mark Stone (26), Marc Methot (10)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/06a8289d-6fb6-48b3-bd43-c03feae39045/1488677484799/asset_1800k.mp4)
3|16:58|OTT|[(SHG) Zack Smith (16) Wrist Shot, assists: Jean-Gabriel Pageau (16)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/9adf6a6d-cda1-4e18-98ab-769dcbeca3f1/1488681598653/asset_1800k.mp4)
3|17:38|CBJ|[(PPG) Sam Gagner (15) Snap Shot, assists: Zach Werenski (30), Cam Atkinson (25)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/1b3dd22c-ef5d-4b3a-80db-f23214a40f23/1488681698756/asset_1800k.mp4)


___
##DALLAS STARS @ FLORIDA PANTHERS
### Final score: 2-1


Period|Time|Team|Point getters
|:-:|:-:|:-:|:-:|
1|11:01|DAL|[Jamie Benn (24) Wrist Shot, assists: Tyler Seguin (42), Jason Spezza (27)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/21fd1143-cb01-44e1-8124-bc5578084780/1488674028770/asset_1800k.mp4)
1|16:20|FLA|[(PPG) Jonathan Huberdeau (5) Snap Shot, assists: Jonathan Marchessault (19), Aleksander Barkov (23)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/65322358-deb5-454c-a8d5-34a0b816c546/1488674676039/asset_1800k.mp4)
3|18:53|DAL|[John Klingberg (11) Slap Shot, assists: Tyler Seguin (43), Jamie Benn (38)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/f61135a0-7598-48d4-af3d-26816ffdb5b2/1488681210310/asset_1800k.mp4)


___
##MONTREAL CANADIENS @ NY RANGERS RANGERS
### Final score: 4-1


Period|Time|Team|Point getters
|:-:|:-:|:-:|:-:|
1|12:51|MTL|[Shea Weber (15) Deflected, assists: Max Pacioretty (26), Steve Ott (4)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/debfefca-bb9c-4146-9aae-4188179ccad1/1488675027026/asset_1800k.mp4)
2|08:48|MTL|[Artturi Lehkonen (12) Snap Shot, assists: Phillip Danault (21), Max Pacioretty (27)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/556619b6-81e8-447c-9d73-4ab5484e7301/1488677164901/asset_1800k.mp4)
2|18:37|MTL|[Andrew Shaw (10) Wrap-around, assists: Alex Galchenyuk (21), Andrei Markov (24)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/8c2b5d43-560b-452e-a5a7-a35dab378f63/1488678366201/asset_1800k.mp4)
3|01:44|NYR|Chris Kreider (24) Wrist Shot, assists: Derek Stepan (32), Mats Zuccarello (33)
3|06:58|MTL|[Jordie Benn (3) Slap Shot, assists: Nathan Beaulieu (21), Alex Galchenyuk (22)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/9b1d3831-4448-4fda-aae0-c2dd60dd6610/1488680593116/asset_1800k.mp4)


___
##COLORADO AVALANCHE @ WINNIPEG JETS
### Final score: 1-6


Period|Time|Team|Point getters
|:-:|:-:|:-:|:-:|
1|04:22|WPG|[Patrik Laine (32) Slap Shot, assists: Mathieu Perreault (21), Dustin Byfuglien (34)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/b6c3d2b1-395a-4cd0-b4a5-c61f3a88a38c/1488673960206/asset_1800k.mp4)
1|09:47|WPG|[(PPG) Blake Wheeler (20) Wrist Shot, assists: Bryan Little (16), Dustin Byfuglien (35)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/81b97af0-c704-4822-89bf-999de8a435a3/1488674104422/asset_1800k.mp4)
1|10:02|WPG|[Mark Scheifele (27) Slap Shot, assists: Patrik Laine (26), Nikolaj Ehlers (30)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/1c69a9a6-a8e8-40e7-bcd5-415d0ff7c6c4/1488674718749/asset_1800k.mp4)
2|07:03|WPG|[Ben Chiarot (1) Backhand, assists: Nikolaj Ehlers (31), Blake Wheeler (35)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/bdf1e56d-8f16-4241-9685-0224fbfa8be4/1488677459096/asset_1800k.mp4)
2|09:05|WPG|[Nikolaj Ehlers (21) Tip-In, assists: Blake Wheeler (36)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/b7cdeace-ed7c-4307-a0eb-beae9e26aee2/1488677671085/asset_1800k.mp4)
3|13:54|WPG|[Jacob Trouba (6) Slap Shot, assists: none](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/bbd5855a-548f-4671-bb00-ce195880f4d8/1488681259054/asset_1800k.mp4)
3|19:44|COL|[Gabriel Landeskog (14) Deflected, assists: Cody Goloubef (4), Rene Bourque (5)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/04a3b311-30ea-48dd-a0e9-c90ddf23cafd/1488682286918/asset_1800k.mp4)


___
##PHILADELPHIA FLYERS @ WASHINGTON CAPITALS
### Final score: 1-2


Period|Time|Team|Point getters
|:-:|:-:|:-:|:-:|
3|01:19|PHI|[Sean Couturier (10) Tip-In, assists: Matt Read (7), Nick Cousins (9)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/e5e918c0-149c-486e-a69d-d5532eb99a64/1488681450775/asset_1800k.mp4)
3|02:40|WSH|[Dmitry Orlov (5) Slap Shot, assists: Matt Niskanen (31)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/e87a511b-a148-48e5-ad42-3439ea3f687a/1488681630672/asset_1800k.mp4)
4|03:25|WSH|[(PPG) Nicklas Backstrom (20) Wrist Shot, assists: Kevin Shattenkirk (32), Alex Ovechkin (28)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/43bf2015-e08b-4a00-95a0-157cb58e8c64/1488683728954/asset_1800k.mp4)


___
##CHICAGO BLACKHAWKS @ NASHVILLE PREDATORS
### Final score: 5-3


Period|Time|Team|Point getters
|:-:|:-:|:-:|:-:|
1|16:23|CHI|[(PPG) Patrick Kane (28) Snap Shot, assists: Brent Seabrook (29), Richard Panik (18)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/05661886-a13c-4f0c-878c-bfa0f09eed13/1488678127068/asset_1800k.mp4)
2|11:03|CHI|[Jordin Tootoo (1) Wrist Shot, assists: Brent Seabrook (30), Duncan Keith (40)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/6a28ee00-03b9-4d1c-aa09-9f9d41a94ee9/1488680630811/asset_1800k.mp4)
2|12:20|NSH|[Viktor Arvidsson (22) Wrist Shot, assists: Ryan Johansen (40), P.K. Subban (24)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/6bf70a5a-f4b6-49ca-a0e0-a87f09e346a4/1488680833069/asset_1800k.mp4)
2|19:03|CHI|[(PPG) Jonathan Toews (17) Wrist Shot, assists: none](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/8331c74b-34dc-4fa1-8231-eedbd22f2c16/1488681805129/asset_1800k.mp4)
2|19:17|NSH|[Calle Jarnkrok (13) Wrist Shot, assists: none](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/5b8039f4-7143-4653-ae7a-178265233175/1488682241004/asset_1800k.mp4)
3|04:13|NSH|[Viktor Arvidsson (23) Wrist Shot, assists: Ryan Johansen (41), Filip Forsberg (24)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/bd3bb071-62f6-45f8-89d5-050a03f8ad5a/1488683091038/asset_1800k.mp4)
3|18:55|CHI|[Brian Campbell (5) Wrist Shot, assists: Jonathan Toews (31), Richard Panik (19)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/774dd537-f9d8-4763-88da-091bb6a3e85b/1488685491079/asset_1800k.mp4)
3|19:21|CHI|[Patrick Kane (29) Snap Shot, assists: Artemi Panarin (38)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/4db05985-a7d4-48be-9b73-1d33351d6353/1488685656553/asset_1800k.mp4)


___
##DETROIT RED WINGS @ EDMONTON OILERS
### Final score: 3-4


Period|Time|Team|Point getters
|:-:|:-:|:-:|:-:|
1|01:41|EDM|[Connor McDavid (22) Backhand, assists: Adam Larsson (13)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/d40655a7-386f-4d39-8dcf-7ab8b2931460/1488683920813/asset_1800k.mp4)
1|15:04|DET|[Anthony Mantha (14) Wrist Shot, assists: Henrik Zetterberg (36)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/d3ecf0a7-24b7-46d4-a288-d15551f212e8/1488685638595/asset_1800k.mp4)
1|19:38|EDM|[Zack Kassian (6) Wrist Shot, assists: Adam Larsson (14), David Desharnais (7)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/b13a3017-ef6a-475a-9859-c36e8bf2769e/1488686110774/asset_1800k.mp4)
3|06:58|EDM|[Jordan Eberle (14) Backhand, assists: Milan Lucic (22)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/3aa79819-a56d-4c3d-b5c4-0eb35a36680c/1488691027143/asset_1800k.mp4)
3|10:26|DET|[Darren Helm (8) Wrist Shot, assists: Dylan Larkin (8)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/29d5b86f-dc4c-4289-b969-2437f547a22c/1488691244734/asset_1800k.mp4)
3|14:02|EDM|[Patrick Maroon (21) Wrist Shot, assists: Leon Draisaitl (32), Connor McDavid (52)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/b00f9e5b-7301-4fb2-b49b-3424e640242a/1488691728757/asset_1800k.mp4)
3|19:25|DET|[Dylan Larkin (13) Wrist Shot, assists: Justin Abdelkader (12), Henrik Zetterberg (37)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/1659b0a6-96df-4f2e-8f6a-d4202a821b66/1488692452895/asset_1800k.mp4)


___
##VANCOUVER CANUCKS @ LOS ANGELES KINGS
### Final score: 4-3


Period|Time|Team|Point getters
|:-:|:-:|:-:|:-:|
1|11:37|VAN|[Sven Baertschi (14) Wrist Shot, assists: Loui Eriksson (12), Bo Horvat (23)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/90b2dd84-063f-4070-8495-c7292b701ff2/1488685080369/asset_1800k.mp4)
1|18:28|VAN|[Henrik Sedin (13) Wrist Shot, assists: Bo Horvat (24), Christopher Tanev (6)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/37bbff8a-5906-470b-a31a-aeb07312807a/1488685935176/asset_1800k.mp4)
2|06:38|VAN|[Sven Baertschi (15) Wrist Shot, assists: Bo Horvat (25), Loui Eriksson (13)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/d30a9bda-1ddf-4ba9-a522-4be6a5b7f8b9/1488687892903/asset_1800k.mp4)
2|12:43|VAN|[Nikolay Goldobin (1) Wrist Shot, assists: Ben Hutton (13), Brandon Sutter (13)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/fe8ec1a5-1b44-4b3a-958b-d153a2ebc10a/1488688591180/asset_1800k.mp4)
2|16:40|LAK|[(PPG) Anze Kopitar (8) Snap Shot, assists: Alec Martinez (24), Drew Doughty (28)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/ecd994e0-2497-4c24-aaeb-c43bc2d628f4/1488689200956/asset_1800k.mp4)
3|12:03|LAK|[(PPG) Trevor Lewis (9) Wrist Shot, assists: Adrian Kempe (3), Paul LaDue (3)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/c66f02b4-2b20-4983-bb21-b8d95e9cb46a/1488692058929/asset_1800k.mp4)
3|18:39|LAK|[(SHG) Alec Martinez (8) Wrist Shot, assists: Adrian Kempe (4), Derek Forbort (13)](http://md-akc.med.nhl.com/mp4/nhl/2017/03/05/7c859480-d8d8-4972-a610-a1e9f16f5196/1488692814726/asset_1800k.mp4)

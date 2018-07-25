# Vampy
<!doctype html>
<html>
	<head>
		<title>Vampy Bot for Granbluefantasy International</title>
		<link rel="stylesheet" href="css/bootstrap-flex.min.css">
		<link rel="stylesheet" href="css/styles.css">
		<script src="js/bootstrap.min.js"></script>
		
	</head>
	<body>
	<div class="jumbotron jumbotron-fluid">
	  <div class="container">
		<h1 class="display-3" id="about"><img src="images/vampy.png" class="circular"/> Vampy <span class="tag tag-default">BOT</span></h1>
		<p class="lead">Vampy is a bot made for Granbluefantasy International Discord server. It is also currently running on a few other servers in beta. This will serve as a list of commands available for users of the bot.</p>
	  </div>
	</div>
	<div class="container">
		<div class="row">
			<div class="col-xs-12">
				
				<h2>Commands</h2>
				<p>List of available commands for vampy</p>
				
				<h4 id="commands">General commands</h4>
				<table class="table table-inverse table-striped table-hover table-bordered">
				  <thead>
				    <tr>
				      <th>Command</th>
				      <th>Description</th>
				      <th>Example</th>
				    </tr>
				  </thead>
				  <tbody>
				    <tr>
				      <th scope="row">!guide</th>
				      <td>Brings up a specific guide based on given keyword. Can use <code>!guide list</code> for all available guides.</td>
				      <td>!guide whale</td>
				    </tr>
				    <tr>
				      <th scope="row">!events</th>
				      <td>Upcoming events for the month.</td>
				      <td>!events</td>
				    </tr>
				    <tr>
				      <th scope="row">!choose</th>
				      <td>Can't make up your mind? Ask vampy to pick for you.</td>
				      <td>!choose eat, sleep, grind</td>
				    </tr>
				    <tr>
				      <th scope="row">!roll10</th>
				      <td>Try your luck rolling gacha. Simulates a 10x gacha roll.</td>
				      <td>!roll10</td>
				    </tr>
				    <tr>
				      <th scope="row">!roll</th>
				      <td>A single roll for when you can't bear 10.</td>
				      <td>!roll</td>
				    </tr>
				    <tr>
				      <th scope="row">!emo</th>
				      <td>Use emotes for when words can't quite explain how you feel. <a href="#emojis">Full list of emojis</a></td>
				      <td>!emo shock</td>
				    </tr>
				    <tr>
				      <th scope="row">!addrole</th>
				      <td>Add an available role to yourself. Check out the full <a href="#roles">list of roles.</a></td>
				      <td>!addrole water</td>
				    </tr>
				    <tr>
				      <th scope="row">!removerole</th>
				      <td>Remove a role when you no longer want it. Check out the full <a href="#roles">list of roles.</a></td>
				      <td>!removerole water</td>
				    </tr>
				    <tr>
				      <th scope="row">!listroles</th>
				      <td>Will give you list of currently available roles in discord. Check out the full <a href="#roles">list of roles.</a></td>
				      <td>!listroles</td>
				    </tr>
				    <tr>
				      <th scope="row">!joined</th>
				      <td>Says when a member joined</td>
				      <td>!joined @Name</td>
				    </tr>
				    <tr>
				      <th scope="row">!help</th>
				      <td>Gives you a link to this page.</td>
				      <td>!help</td>
				    </tr>
				  </tbody>
				</table>

				<h4>Guild War commands</h4>
				<table class="table table-inverse table-striped table-hover table-bordered">
				  <thead>
				    <tr>
				      <th>Command</th>
				      <th>Description</th>
				      <th>Example</th>
				    </tr>
				  </thead>
				  <tbody>
				    <tr>
				      <th scope="row">!gw</th>
				      <td>Looks up a guild in preliminary rankings. Will also search seeded and superseeded guilds.</td>
				      <td>!gw guild_name</td>
				    </tr>
				    <tr>
				      <th scope="row">!player_name</th>
				      <td>Looks up a player's score in top 80k.* Currently limited to top 3 searches.</td>
				      <td>!player_name name</td>
				    </tr>
				    <tr>
				      <th scope="row">!player_id</th>
				      <td>Same as !player_name, but uses their id instead.</td>
				      <td>!player_id 99999999</td>
				    </tr>
				  </tbody>
			      <tfoot>
			         <tr>
			            <td colspan="3"><em>*Scores are periodically updated during intervals.</em></td>
			         </tr>
			      </tfoot>
				</table>
				
				<h4>Action commands</h4>
				<table class="table table-inverse table-striped table-hover table-bordered">
				  <thead>
				    <tr>
				      <th>Command</th>
				      <th>Description</th>
				      <th>Example</th>
				    </tr>
				  </thead>
				  <tbody>
				    <tr>
				      <th scope="row">!slap</th>
				      <td>Slaps someone with bunny meme.</td>
				      <td>!slap @Name</td>
				    </tr>
				    <tr>
				      <th scope="row">!poke</th>
				      <td>Poke someone's avatar with Lyria.</td>
				      <td>!poke @Name</td>
				    </tr>
				    <tr>
				      <th scope="row">!suplex</th>
				      <td>Use Djeeta in wrestler form to suplex someone's avatar.</td>
				      <td>!suplex @Name</td>
				    </tr>
				    <tr>
				      <th scope="row">!slam</th>
				      <td>Mad at someone? Slam them with Chaos Lewder.</td>
				      <td>!slam @Name</td>
				    </tr>
				    <tr>
				      <th scope="row">!buttblow</th>
				      <td>For when words aren't enough. Attack them with Djeeta's butt.</td>
				      <td>!buttblow @Name</td>
				    </tr>
				  </tbody>
				</table>
				
				<h3 id="roles">Roles</h3>
				
				<div class="card card-block">
					<p>
						Elements' roles open up their respective channels so you can discuss about it. Mainly used for weapon builds or sharing salt. Raid roles are used to get notified when someone is hosting a raid. Leeching on HL raids are discouraged (this includes Grande).
					</p>
					<p>
						Groups aren't being used much now since Defend Order was disabled, but they said they would rework it so I am leaving it here for now.
					</p>
					<dl class="row">
	  				  <dt class="col-sm-3">Groups</dt>
	  				  <dd class="col-sm-9">GroupA, GroupB, GroupC, GroupD, GroupE, GroupF, GroupG, GroupH</dd>
				  
					  <dt class="col-sm-3">Elements</dt>
					  <dd class="col-sm-9">Fire, Earth, Water, Wind, Light, Dark</dd>

					  <dt class="col-sm-3">Raids</dt>
					  <dd class="col-sm-9">ColossusHL, YggHL, LeviHL, TiamatHL, ChevHL, CelesteHL, DaoHL, MedusaHL, NezhaHL, ApolloHL, TwinelementsHL, MaculaHL, JkHL, Grande, Bahamut, BahamutHL, Kirin, Kirintrain, Ouryuu, DAOlivia, Athena, Odin, Baal, GilgameshHL, PrometheusHL, CaOngHL, Coop</dd>

					  <dt class="col-sm-3">Events</dt>
					  <dd class="col-sm-9">EventRaidEx, GWRaidEx, GWRaidHell</dd>
					</dl>
				</div>
				
				<h3 id="emojis">Emojis</h3>
				<div class="card card-block">
					<p>
						Compiled list of currently available emojis on Vampy that you can use with the <code>!emo</code> command. A lot of official work as well as fanart. Sources will be compiled later. I don't own any of this.
					</p>
				</div>
				
				<h4>Aoshi's works</h4>
				<p class="details">
					For more of Aoshi's work, please check out her twitter at <a href="https://twitter.com/AoshiArt">https://twitter.com/AoshiArt</a>
				</p>
				<div class='emoji-grid'>
					<figure class="figure">
					  	<img src="images/vira.png" class="figure-img img-fluid" alt="!emo vira" data-toggle="tooltip" data-placement="bottom" title="!emo vira">
					  	<figcaption class="figure-caption text-xs-center">!emo vira</figcaption>
					</figure>
					<figure class="figure">
					  	<img src="images/wanpan.png" class="figure-img img-fluid" alt="!emo wanpan" data-toggle="tooltip" data-placement="bottom" title="!emo vira">
					  	<figcaption class="figure-caption text-xs-center">!emo wanpan</figcaption>
					</figure>
					<figure class="figure">
					  	<img src="images/whale.png" class="figure-img img-fluid" alt="!emo whale" data-toggle="tooltip" data-placement="bottom" title="!emo vira">
					  	<figcaption class="figure-caption text-xs-center">!emo whale</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/bingo.png" class="figure-img img-fluid" alt="!emo bingo">
						<figcaption class="figure-caption text-xs-center">!emo bingo</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/christmas.png" class="figure-img img-fluid" alt="!emo christmas">
						<figcaption class="figure-caption text-xs-center">!emo christmas</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/claris2.png" class="figure-img img-fluid" alt="!emo claris2">
						<figcaption class="figure-caption text-xs-center">!emo claris2</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/confuseray.png" class="figure-img img-fluid" alt="!emo confuseray">
						<figcaption class="figure-caption text-xs-center">!emo confuseray</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/ferry.png" class="figure-img img-fluid" alt="!emo ferry">
						<figcaption class="figure-caption text-xs-center">!emo ferry</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/goodmorning.png" class="figure-img img-fluid" alt="!emo goodmorning">
						<figcaption class="figure-caption text-xs-center">!emo goodmorning</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/goodnight.png" class="figure-img img-fluid" alt="!emo goodnight">
						<figcaption class="figure-caption text-xs-center">!emo goodnight</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/hohoho.png" class="figure-img img-fluid" alt="!emo hohoho">
						<figcaption class="figure-caption text-xs-center">!emo hohoho</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/hrt.png" class="figure-img img-fluid" alt="!emo hrt">
						<figcaption class="figure-caption text-xs-center">!emo hrt</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/keepcalm.png" class="figure-img img-fluid" alt="!emo keepcalm">
						<figcaption class="figure-caption text-xs-center">!emo keepcalm</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/keepcalm2.png" class="figure-img img-fluid" alt="!emo keepcalm2">
						<figcaption class="figure-caption text-xs-center">!emo keepcalm2</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/wtf.png" class="figure-img img-fluid" alt="!emo wtf">
						<figcaption class="figure-caption text-xs-center">!emo wtf</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/helpme.png" class="figure-img img-fluid" alt="!emo helpme">
						<figcaption class="figure-caption text-xs-center">!emo helpme</figcaption>
					</figure>
					<figure class="figure">
					<img src="images/kmr.png" class="figure-img img-fluid" alt="!emo kmr">
						<figcaption class="figure-caption text-xs-center">!emo kmr</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/letsgo.png" class="figure-img img-fluid" alt="!emo letsgo">
						<figcaption class="figure-caption text-xs-center">!emo letsgo</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/lowain.png" class="figure-img img-fluid" alt="!emo lowain">
						<figcaption class="figure-caption text-xs-center">!emo lowain</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/mvp.png" class="figure-img img-fluid" alt="!emo mvp">
						<figcaption class="figure-caption text-xs-center">!emo mvp</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/naru.png" class="figure-img img-fluid" alt="!emo naru">
						<figcaption class="figure-caption text-xs-center">!emo naru</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/nomnom.png" class="figure-img img-fluid" alt="!emo nomnom">
						<figcaption class="figure-caption text-xs-center">!emo nomnom</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/peace.png" class="figure-img img-fluid" alt="!emo peace">
						<figcaption class="figure-caption text-xs-center">!emo peace</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/pewpew.png" class="figure-img img-fluid" alt="!emo pewpew">
						<figcaption class="figure-caption text-xs-center">!emo pewpew</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/salt.png" class="figure-img img-fluid" alt="!emo salt">
						<figcaption class="figure-caption text-xs-center">!emo salt</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/saltlord.png" class="figure-img img-fluid" alt="!emo saltlord">
						<figcaption class="figure-caption text-xs-center">!emo saltlord</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/stronk.png" class="figure-img img-fluid" alt="!emo stronk">
						<figcaption class="figure-caption text-xs-center">!emo stronk</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/ygg.png" class="figure-img img-fluid" alt="!emo ygg">
						<figcaption class="figure-caption text-xs-center">!emo ygg</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/coop.png" class="figure-img img-fluid" alt="!emo coop">
						<figcaption class="figure-caption text-xs-center">!emo coop</figcaption>
					</figure>

                    <figure class="figure">
                        <img src="images/ris.png" class="figure-img img-fluid" alt="!emo ris">
                        <figcaption class="figure-caption text-xs-center">!emo ris</figcaption>
                    </figure>
                    <figure class="figure">
                        <img src="images/shhh.png" class="figure-img img-fluid" alt="!emo shhh">
                        <figcaption class="figure-caption text-xs-center">!emo shhh</figcaption>
                    </figure>
                    <figure class="figure">
                        <img src="images/daonao.png" class="figure-img img-fluid" alt="!emo daonao">
                        <figcaption class="figure-caption text-xs-center">!emo daonao</figcaption>
                    </figure>

<figure class="figure">
	<img src="images/bewbs.png" class="figure-img img-fluid" alt="!emo bewbs">
	<figcaption class="figure-caption text-xs-center">!emo bewbs</figcaption>
</figure>
<figure class="figure">
	<img src="images/cheers.png" class="figure-img img-fluid" alt="!emo cheers">
	<figcaption class="figure-caption text-xs-center">!emo cheers</figcaption>
</figure>
<figure class="figure">
	<img src="images/fight.png" class="figure-img img-fluid" alt="!emo fight">
	<figcaption class="figure-caption text-xs-center">!emo fight</figcaption>
</figure>
<figure class="figure">
	<img src="images/food.png" class="figure-img img-fluid" alt="!emo food">
	<figcaption class="figure-caption text-xs-center">!emo food</figcaption>
</figure>
<figure class="figure">
	<img src="images/hmm.png" class="figure-img img-fluid" alt="!emo hmm">
	<figcaption class="figure-caption text-xs-center">!emo hmm</figcaption>
</figure>
<figure class="figure">
	<img src="images/kill.png" class="figure-img img-fluid" alt="!emo kill">
	<figcaption class="figure-caption text-xs-center">!emo kill</figcaption>
</figure>
<figure class="figure">
	<img src="images/kmrwhy.png" class="figure-img img-fluid" alt="!emo kmrwhy">
	<figcaption class="figure-caption text-xs-center">!emo kmrwhy</figcaption>
</figure>
<figure class="figure">
	<img src="images/sofat.png" class="figure-img img-fluid" alt="!emo sofat">
	<figcaption class="figure-caption text-xs-center">!emo sofat</figcaption>
</figure>
				</div>
				
				<h4>Vyrn</h4>
				
				<div class="emoji-grid">
					<figure class="figure">
						<img src="images/ball.png" class="figure-img img-fluid" alt="!emo ball">
						<figcaption class="figure-caption text-xs-center">!emo ball</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/bow.png" class="figure-img img-fluid" alt="!emo bow">
						<figcaption class="figure-caption text-xs-center">!emo bow</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/chill.png" class="figure-img img-fluid" alt="!emo chill">
						<figcaption class="figure-caption text-xs-center">!emo chill</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/cold.png" class="figure-img img-fluid" alt="!emo cold">
						<figcaption class="figure-caption text-xs-center">!emo cold</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/creep.png" class="figure-img img-fluid" alt="!emo creep">
						<figcaption class="figure-caption text-xs-center">!emo creep</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/cry.png" class="figure-img img-fluid" alt="!emo cry">
						<figcaption class="figure-caption text-xs-center">!emo cry</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/despair.png" class="figure-img img-fluid" alt="!emo despair">
						<figcaption class="figure-caption text-xs-center">!emo despair</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/despair2.png" class="figure-img img-fluid" alt="!emo despair2">
						<figcaption class="figure-caption text-xs-center">!emo despair2</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/embarass.png" class="figure-img img-fluid" alt="!emo embarass">
						<figcaption class="figure-caption text-xs-center">!emo embarass</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/fail.png" class="figure-img img-fluid" alt="!emo fail">
						<figcaption class="figure-caption text-xs-center">!emo fail</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/frolic.png" class="figure-img img-fluid" alt="!emo frolic">
						<figcaption class="figure-caption text-xs-center">!emo frolic</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/full.png" class="figure-img img-fluid" alt="!emo full">
						<figcaption class="figure-caption text-xs-center">!emo full</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/ganbare.png" class="figure-img img-fluid" alt="!emo ganbare">
						<figcaption class="figure-caption text-xs-center">!emo ganbare</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/go.png" class="figure-img img-fluid" alt="!emo go">
						<figcaption class="figure-caption text-xs-center">!emo go</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/hee.png" class="figure-img img-fluid" alt="!emo hee">
						<figcaption class="figure-caption text-xs-center">!emo hee</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/love.png" class="figure-img img-fluid" alt="!emo love">
						<figcaption class="figure-caption text-xs-center">!emo love</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/morning_vee.png" class="figure-img img-fluid" alt="!emo morning_vee">
						<figcaption class="figure-caption text-xs-center">!emo morning_vee</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/muscles.png" class="figure-img img-fluid" alt="!emo muscles">
						<figcaption class="figure-caption text-xs-center">!emo muscles</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/nice.png" class="figure-img img-fluid" alt="!emo nice">
						<figcaption class="figure-caption text-xs-center">!emo nice</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/night.png" class="figure-img img-fluid" alt="!emo night">
						<figcaption class="figure-caption text-xs-center">!emo night</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/read.png" class="figure-img img-fluid" alt="!emo read">
						<figcaption class="figure-caption text-xs-center">!emo read</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/relax.png" class="figure-img img-fluid" alt="!emo relax">
						<figcaption class="figure-caption text-xs-center">!emo relax</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/sigh2.png" class="figure-img img-fluid" alt="!emo sigh2">
						<figcaption class="figure-caption text-xs-center">!emo sigh2</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/sparkle.png" class="figure-img img-fluid" alt="!emo sparkle">
						<figcaption class="figure-caption text-xs-center">!emo sparkle</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/surprise.png" class="figure-img img-fluid" alt="!emo surprise">
						<figcaption class="figure-caption text-xs-center">!emo surprise</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/thanks_vee.png" class="figure-img img-fluid" alt="!emo thanks_vee">
						<figcaption class="figure-caption text-xs-center">!emo thanks_vee</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/thumbsup.png" class="figure-img img-fluid" alt="!emo thumbsup">
						<figcaption class="figure-caption text-xs-center">!emo thumbsup</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/tremble.png" class="figure-img img-fluid" alt="!emo tremble">
						<figcaption class="figure-caption text-xs-center">!emo tremble</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/twirl.png" class="figure-img img-fluid" alt="!emo twirl">
						<figcaption class="figure-caption text-xs-center">!emo twirl</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/vee.png" class="figure-img img-fluid" alt="!emo vee">
						<figcaption class="figure-caption text-xs-center">!emo vee</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/what.png" class="figure-img img-fluid" alt="!emo what">
						<figcaption class="figure-caption text-xs-center">!emo what</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/zen.png" class="figure-img img-fluid" alt="!emo zen">
						<figcaption class="figure-caption text-xs-center">!emo zen</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/zzz.png" class="figure-img img-fluid" alt="!emo zzz">
						<figcaption class="figure-caption text-xs-center">!emo zzz</figcaption>
					</figure>
				</div>
				
				<h4>Stickers</h4>
				<div class="emoji-grid">
					<figure class="figure">
						<img src="images/bully.png" class="figure-img img-fluid" alt="!emo bully">
						<figcaption class="figure-caption text-xs-center">!emo bully</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/callshots.png" class="figure-img img-fluid" alt="!emo callshots">
						<figcaption class="figure-caption text-xs-center">!emo callshots</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/calmdown.png" class="figure-img img-fluid" alt="!emo calmdown">
						<figcaption class="figure-caption text-xs-center">!emo calmdown</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/canihelp.png" class="figure-img img-fluid" alt="!emo canihelp">
						<figcaption class="figure-caption text-xs-center">!emo canihelp</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/chance.png" class="figure-img img-fluid" alt="!emo chance">
						<figcaption class="figure-caption text-xs-center">!emo chance</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/cool.png" class="figure-img img-fluid" alt="!emo cool">
						<figcaption class="figure-caption text-xs-center">!emo cool</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/doit.png" class="figure-img img-fluid" alt="!emo doit">
						<figcaption class="figure-caption text-xs-center">!emo doit</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/dying.png" class="figure-img img-fluid" alt="!emo dying">
						<figcaption class="figure-caption text-xs-center">!emo dying</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/eh.png" class="figure-img img-fluid" alt="!emo eh">
						<figcaption class="figure-caption text-xs-center">!emo eh</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/flirt.png" class="figure-img img-fluid" alt="!emo flirt">
						<figcaption class="figure-caption text-xs-center">!emo flirt</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/focus.png" class="figure-img img-fluid" alt="!emo focus">
						<figcaption class="figure-caption text-xs-center">!emo focus</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/funfu.png" class="figure-img img-fluid" alt="!emo funfu">
						<figcaption class="figure-caption text-xs-center">!emo funfu</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/goahead.png" class="figure-img img-fluid" alt="!emo goahead">
						<figcaption class="figure-caption text-xs-center">!emo goahead</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/goodjob.png" class="figure-img img-fluid" alt="!emo goodjob">
						<figcaption class="figure-caption text-xs-center">!emo goodjob</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/goodwork.png" class="figure-img img-fluid" alt="!emo goodwork">
						<figcaption class="figure-caption text-xs-center">!emo goodwork</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/help.png" class="figure-img img-fluid" alt="!emo help">
						<figcaption class="figure-caption text-xs-center">!emo help</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/helpwait.png" class="figure-img img-fluid" alt="!emo helpwait">
						<figcaption class="figure-caption text-xs-center">!emo helpwait</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/igotit.png" class="figure-img img-fluid" alt="!emo igotit">
						<figcaption class="figure-caption text-xs-center">!emo igotit</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/igotyou.png" class="figure-img img-fluid" alt="!emo igotyou">
						<figcaption class="figure-caption text-xs-center">!emo igotyou</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/igotyourback.png" class="figure-img img-fluid" alt="!emo igotyourback">
						<figcaption class="figure-caption text-xs-center">!emo igotyourback</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/judgement.png" class="figure-img img-fluid" alt="!emo judgement">
						<figcaption class="figure-caption text-xs-center">!emo judgement</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/ntrhero.png" class="figure-img img-fluid" alt="!emo ntrhero">
						<figcaption class="figure-caption text-xs-center">!emo ntrhero</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/percy.png" class="figure-img img-fluid" alt="!emo percy">
						<figcaption class="figure-caption text-xs-center">!emo percy</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/phalanx.png" class="figure-img img-fluid" alt="!emo phalanx">
						<figcaption class="figure-caption text-xs-center">!emo phalanx</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/radish.png" class="figure-img img-fluid" alt="!emo radish">
						<figcaption class="figure-caption text-xs-center">!emo radish</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/rakamuuu.png" class="figure-img img-fluid" alt="!emo rakamuuu">
						<figcaption class="figure-caption text-xs-center">!emo rakamuuu</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/siero.png" class="figure-img img-fluid" alt="!emo siero">
						<figcaption class="figure-caption text-xs-center">!emo siero</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/siete.png" class="figure-img img-fluid" alt="!emo siete">
						<figcaption class="figure-caption text-xs-center">!emo siete</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/siete2.png" class="figure-img img-fluid" alt="!emo siete2">
						<figcaption class="figure-caption text-xs-center">!emo siete2</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/sigh.png" class="figure-img img-fluid" alt="!emo sigh">
						<figcaption class="figure-caption text-xs-center">!emo sigh</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/six.png" class="figure-img img-fluid" alt="!emo six">
						<figcaption class="figure-caption text-xs-center">!emo six</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/sneeze.png" class="figure-img img-fluid" alt="!emo sneeze">
						<figcaption class="figure-caption text-xs-center">!emo sneeze</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/soiya.png" class="figure-img img-fluid" alt="!emo soiya">
						<figcaption class="figure-caption text-xs-center">!emo soiya</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/soiya1.png" class="figure-img img-fluid" alt="!emo soiya1">
						<figcaption class="figure-caption text-xs-center">!emo soiya1</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/soiya2.png" class="figure-img img-fluid" alt="!emo soiya2">
						<figcaption class="figure-caption text-xs-center">!emo soiya2</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/soya3.png" class="figure-img img-fluid" alt="!emo soya3">
						<figcaption class="figure-caption text-xs-center">!emo soya3</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/stopit.png" class="figure-img img-fluid" alt="!emo stopit">
						<figcaption class="figure-caption text-xs-center">!emo stopit</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/thanks.png" class="figure-img img-fluid" alt="!emo thanks">
						<figcaption class="figure-caption text-xs-center">!emo thanks</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/uno.png" class="figure-img img-fluid" alt="!emo uno">
						<figcaption class="figure-caption text-xs-center">!emo uno</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/victory.png" class="figure-img img-fluid" alt="!emo victory">
						<figcaption class="figure-caption text-xs-center">!emo victory</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/wait.png" class="figure-img img-fluid" alt="!emo wait">
						<figcaption class="figure-caption text-xs-center">!emo wait</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/whoa.png" class="figure-img img-fluid" alt="!emo whoa">
						<figcaption class="figure-caption text-xs-center">!emo whoa</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/wink.png" class="figure-img img-fluid" alt="!emo wink">
						<figcaption class="figure-caption text-xs-center">!emo wink</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/yes.png" class="figure-img img-fluid" alt="!emo yes">
						<figcaption class="figure-caption text-xs-center">!emo yes</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/yoroshiku.png" class="figure-img img-fluid" alt="!emo yoroshiku">
						<figcaption class="figure-caption text-xs-center">!emo yoroshiku</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/quatre.png" class="figure-img img-fluid" alt="!emo quatre">
						<figcaption class="figure-caption text-xs-center">!emo quatre</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/sorn.png" class="figure-img img-fluid" alt="!emo sorn">
						<figcaption class="figure-caption text-xs-center">!emo sorn</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/yum.png" class="figure-img img-fluid" alt="!emo yum">
						<figcaption class="figure-caption text-xs-center">!emo yum</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/altair.png" class="figure-img img-fluid" alt="!emo altair">
						<figcaption class="figure-caption text-xs-center">!emo altair</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/ashes.png" class="figure-img img-fluid" alt="!emo ashes">
						<figcaption class="figure-caption text-xs-center">!emo ashes</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/congrats.png" class="figure-img img-fluid" alt="!emo congrats">
						<figcaption class="figure-caption text-xs-center">!emo congrats</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/hai.png" class="figure-img img-fluid" alt="!emo hai">
						<figcaption class="figure-caption text-xs-center">!emo hai</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/help.png" class="figure-img img-fluid" alt="!emo help">
						<figcaption class="figure-caption text-xs-center">!emo help</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/morning.png" class="figure-img img-fluid" alt="!emo morning">
						<figcaption class="figure-caption text-xs-center">!emo morning</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/lyria.png" class="figure-img img-fluid" alt="!emo lyria">
						<figcaption class="figure-caption text-xs-center">!emo lyria</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/morning.png" class="figure-img img-fluid" alt="!emo morning">
						<figcaption class="figure-caption text-xs-center">!emo morning</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/yummy.png" class="figure-img img-fluid" alt="!emo yummy">
						<figcaption class="figure-caption text-xs-center">!emo yummy</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/okto.png" class="figure-img img-fluid" alt="!emo okto">
						<figcaption class="figure-caption text-xs-center">!emo okto</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/percy_sexy.png" class="figure-img img-fluid" alt="!emo percy_sexy">
						<figcaption class="figure-caption text-xs-center">!emo percy_sexy</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/lecia.png" class="figure-img img-fluid" alt="!emo lecia">
						<figcaption class="figure-caption text-xs-center">!emo lecia</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/go2.png" class="figure-img img-fluid" alt="!emo go2">
						<figcaption class="figure-caption text-xs-center">!emo go2</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/cake.png" class="figure-img img-fluid" alt="!emo cake">
						<figcaption class="figure-caption text-xs-center">!emo cake</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/yikes.png" class="figure-img img-fluid" alt="!emo yikes">
						<figcaption class="figure-caption text-xs-center">!emo yikes</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/letsgo2.png" class="figure-img img-fluid" alt="!emo letsgo2">
						<figcaption class="figure-caption text-xs-center">!emo letsgo2</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/yay.png" class="figure-img img-fluid" alt="!emo yay">
						<figcaption class="figure-caption text-xs-center">!emo yay</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/drool.png" class="figure-img img-fluid" alt="!emo drool">
						<figcaption class="figure-caption text-xs-center">!emo drool</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/hi.png" class="figure-img img-fluid" alt="!emo hi">
						<figcaption class="figure-caption text-xs-center">!emo hi</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/grats.png" class="figure-img img-fluid" alt="!emo grats">
						<figcaption class="figure-caption text-xs-center">!emo grats</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/ok.png" class="figure-img img-fluid" alt="!emo ok">
						<figcaption class="figure-caption text-xs-center">!emo ok</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/hello.png" class="figure-img img-fluid" alt="!emo hello">
						<figcaption class="figure-caption text-xs-center">!emo hello</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/letmehelp.png" class="figure-img img-fluid" alt="!emo letmehelp">
						<figcaption class="figure-caption text-xs-center">!emo letmehelp</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/yessir.png" class="figure-img img-fluid" alt="!emo yessir">
						<figcaption class="figure-caption text-xs-center">!emo yessir</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/letme.png" class="figure-img img-fluid" alt="!emo letme">
						<figcaption class="figure-caption text-xs-center">!emo letme</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/onit.png" class="figure-img img-fluid" alt="!emo onit">
						<figcaption class="figure-caption text-xs-center">!emo onit</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/there.png" class="figure-img img-fluid" alt="!emo there">
						<figcaption class="figure-caption text-xs-center">!emo there</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/amazing.png" class="figure-img img-fluid" alt="!emo amazing">
						<figcaption class="figure-caption text-xs-center">!emo amazing</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/legend.png" class="figure-img img-fluid" alt="!emo legend">
						<figcaption class="figure-caption text-xs-center">!emo legend</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/rackaam.png" class="figure-img img-fluid" alt="!emo rackaam">
						<figcaption class="figure-caption text-xs-center">!emo rackaam</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/rackaam2.png" class="figure-img img-fluid" alt="!emo rackaam2">
						<figcaption class="figure-caption text-xs-center">!emo rackaam2</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/rackaam3.png" class="figure-img img-fluid" alt="!emo rackaam3">
						<figcaption class="figure-caption text-xs-center">!emo rackaam3</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/rackaam4.png" class="figure-img img-fluid" alt="!emo rackaam4">
						<figcaption class="figure-caption text-xs-center">!emo rackaam4</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/bullseye.png" class="figure-img img-fluid" alt="!emo bullseye">
						<figcaption class="figure-caption text-xs-center">!emo bullseye</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/pandemonium.png" class="figure-img img-fluid" alt="!emo pandemonium">
						<figcaption class="figure-caption text-xs-center">!emo pandemonium</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/loot.png" class="figure-img img-fluid" alt="!emo loot">
						<figcaption class="figure-caption text-xs-center">!emo loot</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/gravity.png" class="figure-img img-fluid" alt="!emo gravity">
						<figcaption class="figure-caption text-xs-center">!emo gravity</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/crackshot.png" class="figure-img img-fluid" alt="!emo crackshot">
						<figcaption class="figure-caption text-xs-center">!emo crackshot</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/gowild.png" class="figure-img img-fluid" alt="!emo gowild">
						<figcaption class="figure-caption text-xs-center">!emo gowild</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/heal.png" class="figure-img img-fluid" alt="!emo heal">
						<figcaption class="figure-caption text-xs-center">!emo heal</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/backup.png" class="figure-img img-fluid" alt="!emo backup">
						<figcaption class="figure-caption text-xs-center">!emo backup</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/arsenal.png" class="figure-img img-fluid" alt="!emo arsenal">
						<figcaption class="figure-caption text-xs-center">!emo arsenal</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/letsdoit.png" class="figure-img img-fluid" alt="!emo letsdoit">
						<figcaption class="figure-caption text-xs-center">!emo letsdoit</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/striketime.png" class="figure-img img-fluid" alt="!emo striketime">
						<figcaption class="figure-caption text-xs-center">!emo striketime</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/igiveup.png" class="figure-img img-fluid" alt="!emo igiveup">
						<figcaption class="figure-caption text-xs-center">!emo igiveup</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/potsplz.png" class="figure-img img-fluid" alt="!emo potsplz">
						<figcaption class="figure-caption text-xs-center">!emo potsplz</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/here.png" class="figure-img img-fluid" alt="!emo here">
						<figcaption class="figure-caption text-xs-center">!emo here</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/summon.png" class="figure-img img-fluid" alt="!emo summon">
						<figcaption class="figure-caption text-xs-center">!emo summon</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/awesome.png" class="figure-img img-fluid" alt="!emo awesome">
						<figcaption class="figure-caption text-xs-center">!emo awesome</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/hurray.png" class="figure-img img-fluid" alt="!emo hurray">
						<figcaption class="figure-caption text-xs-center">!emo hurray</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/whoops.png" class="figure-img img-fluid" alt="!emo whoops">
						<figcaption class="figure-caption text-xs-center">!emo whoops</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/tada.png" class="figure-img img-fluid" alt="!emo tada">
						<figcaption class="figure-caption text-xs-center">!emo tada</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/achoo.png" class="figure-img img-fluid" alt="!emo achoo">
						<figcaption class="figure-caption text-xs-center">!emo achoo</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/boom.png" class="figure-img img-fluid" alt="!emo boom">
						<figcaption class="figure-caption text-xs-center">!emo boom</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/chomp.png" class="figure-img img-fluid" alt="!emo chomp">
						<figcaption class="figure-caption text-xs-center">!emo chomp</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/aww.png" class="figure-img img-fluid" alt="!emo aww">
						<figcaption class="figure-caption text-xs-center">!emo aww</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/foryou.png" class="figure-img img-fluid" alt="!emo foryou">
						<figcaption class="figure-caption text-xs-center">!emo foryou</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/nice2.png" class="figure-img img-fluid" alt="!emo nice2">
						<figcaption class="figure-caption text-xs-center">!emo nice2</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/aboutthat.png" class="figure-img img-fluid" alt="!emo aboutthat">
						<figcaption class="figure-caption text-xs-center">!emo aboutthat</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/ohno.png" class="figure-img img-fluid" alt="!emo ohno">
						<figcaption class="figure-caption text-xs-center">!emo ohno</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/bop.png" class="figure-img img-fluid" alt="!emo bop">
						<figcaption class="figure-caption text-xs-center">!emo bop</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/drip.png" class="figure-img img-fluid" alt="!emo drip">
						<figcaption class="figure-caption text-xs-center">!emo drip</figcaption>
					</figure>
          <figure class="figure">
            <img src="images/thump.png" class="figure-img img-fluid" alt="!emo thump">
            <figcaption class="figure-caption text-xs-center">!emo thump</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/whyme.png" class="figure-img img-fluid" alt="!emo whyme">
            <figcaption class="figure-caption text-xs-center">!emo whyme</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/mission.png" class="figure-img img-fluid" alt="!emo mission">
            <figcaption class="figure-caption text-xs-center">!emo mission</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/saidtoomuch.png" class="figure-img img-fluid" alt="!emo saidtoomuch">
            <figcaption class="figure-caption text-xs-center">!emo saidtoomuch</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/what2.png" class="figure-img img-fluid" alt="!emo what2">
            <figcaption class="figure-caption text-xs-center">!emo what2</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/huh2.png" class="figure-img img-fluid" alt="!emo huh2">
            <figcaption class="figure-caption text-xs-center">!emo huh2</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/nocando.png" class="figure-img img-fluid" alt="!emo nocando">
            <figcaption class="figure-caption text-xs-center">!emo nocando</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/ten.png" class="figure-img img-fluid" alt="!emo ten">
            <figcaption class="figure-caption text-xs-center">!emo ten</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/toocool.png" class="figure-img img-fluid" alt="!emo toocool">
            <figcaption class="figure-caption text-xs-center">!emo toocool</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/fail2.png" class="figure-img img-fluid" alt="!emo fail2">
            <figcaption class="figure-caption text-xs-center">!emo fail2</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/slap.png" class="figure-img img-fluid" alt="!emo slap">
            <figcaption class="figure-caption text-xs-center">!emo slap</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/nooo.png" class="figure-img img-fluid" alt="!emo nooo">
            <figcaption class="figure-caption text-xs-center">!emo nooo</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/heyo.png" class="figure-img img-fluid" alt="!emo heyo">
            <figcaption class="figure-caption text-xs-center">!emo heyo</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/nope.png" class="figure-img img-fluid" alt="!emo nope">
            <figcaption class="figure-caption text-xs-center">!emo nope</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/whatsup.png" class="figure-img img-fluid" alt="!emo whatsup">
            <figcaption class="figure-caption text-xs-center">!emo whatsup</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/poke.png" class="figure-img img-fluid" alt="!emo poke">
            <figcaption class="figure-caption text-xs-center">!emo poke</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/commandme.png" class="figure-img img-fluid" alt="!emo commandme">
            <figcaption class="figure-caption text-xs-center">!emo commandme</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/wiggle.png" class="figure-img img-fluid" alt="!emo wiggle">
            <figcaption class="figure-caption text-xs-center">!emo wiggle</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/yea.png" class="figure-img img-fluid" alt="!emo yea">
            <figcaption class="figure-caption text-xs-center">!emo yea</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/pft.png" class="figure-img img-fluid" alt="!emo pft">
            <figcaption class="figure-caption text-xs-center">!emo pft</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/siero2.png" class="figure-img img-fluid" alt="!emo siero2">
            <figcaption class="figure-caption text-xs-center">!emo siero2</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/quiet.png" class="figure-img img-fluid" alt="!emo quiet">
            <figcaption class="figure-caption text-xs-center">!emo quiet</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/bye.png" class="figure-img img-fluid" alt="!emo bye">
            <figcaption class="figure-caption text-xs-center">!emo bye</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/peace2.png" class="figure-img img-fluid" alt="!emo peace2">
            <figcaption class="figure-caption text-xs-center">!emo peace2</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/yummy2.png" class="figure-img img-fluid" alt="!emo yummy2">
            <figcaption class="figure-caption text-xs-center">!emo yummy2</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/easy.png" class="figure-img img-fluid" alt="!emo easy">
            <figcaption class="figure-caption text-xs-center">!emo easy</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/nailedit.png" class="figure-img img-fluid" alt="!emo nailedit">
            <figcaption class="figure-caption text-xs-center">!emo nailedit</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/please.png" class="figure-img img-fluid" alt="!emo please">
            <figcaption class="figure-caption text-xs-center">!emo please</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/lily.png" class="figure-img img-fluid" alt="!emo lily">
            <figcaption class="figure-caption text-xs-center">!emo lily</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/rainbow.png" class="figure-img img-fluid" alt="!emo rainbow">
            <figcaption class="figure-caption text-xs-center">!emo rainbow</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/rip.png" class="figure-img img-fluid" alt="!emo rip">
            <figcaption class="figure-caption text-xs-center">!emo rip</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/swordplz.png" class="figure-img img-fluid" alt="!emo swordplz">
            <figcaption class="figure-caption text-xs-center">!emo swordplz</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/pout.png" class="figure-img img-fluid" alt="!emo pout">
            <figcaption class="figure-caption text-xs-center">!emo pout</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/sara.png" class="figure-img img-fluid" alt="!emo sara">
            <figcaption class="figure-caption text-xs-center">!emo sara</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/ohhh.png" class="figure-img img-fluid" alt="!emo ohhh">
            <figcaption class="figure-caption text-xs-center">!emo ohhh</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/rose.png" class="figure-img img-fluid" alt="!emo rose">
            <figcaption class="figure-caption text-xs-center">!emo rose</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/fenrir.png" class="figure-img img-fluid" alt="!emo fenrir">
            <figcaption class="figure-caption text-xs-center">!emo fenrir</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/potato.png" class="figure-img img-fluid" alt="!emo potato">
            <figcaption class="figure-caption text-xs-center">!emo potato</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/djeanne.png" class="figure-img img-fluid" alt="!emo djeanne">
            <figcaption class="figure-caption text-xs-center">!emo djeanne</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/kawaii.png" class="figure-img img-fluid" alt="!emo kawaii">
            <figcaption class="figure-caption text-xs-center">!emo kawaii</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/djeeta.png" class="figure-img img-fluid" alt="!emo djeeta">
            <figcaption class="figure-caption text-xs-center">!emo djeeta</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/lyria2.png" class="figure-img img-fluid" alt="!emo lyria2">
            <figcaption class="figure-caption text-xs-center">!emo lyria2</figcaption>
          </figure>
          <figure class="figure">
            <img src="images/sen.png" class="figure-img img-fluid" alt="!emo sen">
            <figcaption class="figure-caption text-xs-center">!emo sen</figcaption>
          </figure>
				</div>
				
				<h4>Emotes</h4>
				<div class="emoji-grid">
					<figure class="figure">
						<img src="images/attack.png" class="figure-img img-fluid" alt="!emo attack">
						<figcaption class="figure-caption text-xs-center">!emo attack</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/blush.png" class="figure-img img-fluid" alt="!emo blush">
						<figcaption class="figure-caption text-xs-center">!emo blush</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/bow2.png" class="figure-img img-fluid" alt="!emo bow2">
						<figcaption class="figure-caption text-xs-center">!emo bow2</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/claris.png" class="figure-img img-fluid" alt="!emo claris">
						<figcaption class="figure-caption text-xs-center">!emo claris</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/confuse.png" class="figure-img img-fluid" alt="!emo confuse">
						<figcaption class="figure-caption text-xs-center">!emo confuse</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/esser.png" class="figure-img img-fluid" alt="!emo esser">
						<figcaption class="figure-caption text-xs-center">!emo esser</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/fish.png" class="figure-img img-fluid" alt="!emo fish">
						<figcaption class="figure-caption text-xs-center">!emo fish</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/happy.png" class="figure-img img-fluid" alt="!emo happy">
						<figcaption class="figure-caption text-xs-center">!emo happy</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/hug.png" class="figure-img img-fluid" alt="!emo hug">
						<figcaption class="figure-caption text-xs-center">!emo hug</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/huh.png" class="figure-img img-fluid" alt="!emo huh">
						<figcaption class="figure-caption text-xs-center">!emo huh</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/hungry.png" class="figure-img img-fluid" alt="!emo hungry">
						<figcaption class="figure-caption text-xs-center">!emo hungry</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/arigatou.png" class="figure-img img-fluid" alt="!emo arigatou">
						<figcaption class="figure-caption text-xs-center">!emo arigatou</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/lewd.png" class="figure-img img-fluid" alt="!emo lewd">
						<figcaption class="figure-caption text-xs-center">!emo lewd</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/like.png" class="figure-img img-fluid" alt="!emo like">
						<figcaption class="figure-caption text-xs-center">!emo like</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/menace.png" class="figure-img img-fluid" alt="!emo menace">
						<figcaption class="figure-caption text-xs-center">!emo menace</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/no.png" class="figure-img img-fluid" alt="!emo no">
						<figcaption class="figure-caption text-xs-center">!emo no</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/nobully.png" class="figure-img img-fluid" alt="!emo nobully">
						<figcaption class="figure-caption text-xs-center">!emo nobully</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/nervous.png" class="figure-img img-fluid" alt="!emo nervous">
						<figcaption class="figure-caption text-xs-center">!emo nervous</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/nohelp.png" class="figure-img img-fluid" alt="!emo nohelp">
						<figcaption class="figure-caption text-xs-center">!emo nohelp</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/nohelp2.png" class="figure-img img-fluid" alt="!emo nohelp2">
						<figcaption class="figure-caption text-xs-center">!emo nohelp2</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/nio.png" class="figure-img img-fluid" alt="!emo nio">
						<figcaption class="figure-caption text-xs-center">!emo nio</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/parrot.png" class="figure-img img-fluid" alt="!emo parrot">
						<figcaption class="figure-caption text-xs-center">!emo parrot</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/pain.png" class="figure-img img-fluid" alt="!emo pain">
						<figcaption class="figure-caption text-xs-center">!emo pain</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/rainbowplz.png" class="figure-img img-fluid" alt="!emo rainbowplz">
						<figcaption class="figure-caption text-xs-center">!emo rainbowplz</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/rainbowplz2.png" class="figure-img img-fluid" alt="!emo rainbowplz2">
						<figcaption class="figure-caption text-xs-center">!emo rainbowplz2</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/rawr.png" class="figure-img img-fluid" alt="!emo rawr">
						<figcaption class="figure-caption text-xs-center">!emo rawr</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/sarasa.png" class="figure-img img-fluid" alt="!emo sarasa">
						<figcaption class="figure-caption text-xs-center">!emo sarasa</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/secret.png" class="figure-img img-fluid" alt="!emo secret">
						<figcaption class="figure-caption text-xs-center">!emo secret</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/shock.png" class="figure-img img-fluid" alt="!emo shock">
						<figcaption class="figure-caption text-xs-center">!emo shock</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/shy.png" class="figure-img img-fluid" alt="!emo shy">
						<figcaption class="figure-caption text-xs-center">!emo shy</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/wut.png" class="figure-img img-fluid" alt="!emo wut">
						<figcaption class="figure-caption text-xs-center">!emo wut</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/stare.png" class="figure-img img-fluid" alt="!emo stare">
						<figcaption class="figure-caption text-xs-center">!emo stare</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/stopit.png" class="figure-img img-fluid" alt="!emo stopit">
						<figcaption class="figure-caption text-xs-center">!emo stopit</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/bam.png" class="figure-img img-fluid" alt="!emo bam">
						<figcaption class="figure-caption text-xs-center">!emo bam</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/bear.png" class="figure-img img-fluid" alt="!emo bear">
						<figcaption class="figure-caption text-xs-center">!emo bear</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/cheers.png" class="figure-img img-fluid" alt="!emo cheers">
						<figcaption class="figure-caption text-xs-center">!emo cheers</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/run.png" class="figure-img img-fluid" alt="!emo run">
						<figcaption class="figure-caption text-xs-center">!emo run</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/sorry.png" class="figure-img img-fluid" alt="!emo sorry">
						<figcaption class="figure-caption text-xs-center">!emo sorry</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/umbrella.png" class="figure-img img-fluid" alt="!emo umbrella">
						<figcaption class="figure-caption text-xs-center">!emo umbrella</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/starving.png" class="figure-img img-fluid" alt="!emo starving">
						<figcaption class="figure-caption text-xs-center">!emo starving</figcaption>
					</figure>
					<figure class="figure">
						<img src="images/gong.png" class="figure-img img-fluid" alt="!emo gong">
						<figcaption class="figure-caption text-xs-center">!emo gong</figcaption>
					</figure>
                    <figure class="figure">
                        <img src="images/twirl2.png" class="figure-img img-fluid" alt="!emo twirl2">
                        <figcaption class="figure-caption text-xs-center">!emo twirl2</figcaption>
                    </figure>
                    <figure class="figure">
                        <img src="images/rawr2.png" class="figure-img img-fluid" alt="!emo rawr2">
                        <figcaption class="figure-caption text-xs-center">!emo rawr2</figcaption>
                    </figure>
                    <figure class="figure">
                        <img src="images/centrumplz.png" class="figure-img img-fluid" alt="!emo centrumplz">
                        <figcaption class="figure-caption text-xs-center">!emo centrumplz</figcaption>
                    </figure>

				</div>
				
			</div>
		</div>

	  </div>
	</div>
	</body>
</html>

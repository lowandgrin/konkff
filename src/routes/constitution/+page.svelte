<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneTwo;
    let two, twoOne, twoTwo;
    let three, threeOne;
    let four, fourOne, fourTwo, fourThree, fourFour, fourFive, fourSix;
    let five, fiveOne, fiveTwo, fiveThree, fiveFour, fiveFive;
    let six;
    let seven, sevenOne, sevenOneOne, sevenTwo;
    let eight;
    let nine;
    let ten;
    let eleven;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">Kick Off - No Kickers Bylaws (Under Construction)</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>Section 1: Important Dates</h3>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneOne)}>1.1 League Renewal Deadline</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneTwo)}>1.2 Annual Rookie Draft</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>Section 2: Fees and Payouts</h3>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoOne)}>2.1 Yearly Dues</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(twoTwo)}>2.2 Payouts</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>Section 3: Standard Scoring System</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Section 4: Rosters</h3>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourOne)}>4.1 Starting Lineup Requirements</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourTwo)}>4.2 Bench Spots</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourThree)}>4.3 IR Spots</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourFour)}>4.4 Taxi Squad</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourFive)}>4.5 Weekly Starting Lineup</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourSix)}>4.6 Roster Freezes</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Section 5: Trading</h3>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>5.1 Trading Basic Rules</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveTwo)}>5.2 Trade Deadline</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveThree)}>5.3 Protesting Trades / Reversals</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fivefive)}>5.4 Trade/Roster Accidents</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveFive)}>5.5 Taxi Trades</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Section 6: Playoffs</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 7: Rookie Drafts</h3>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenOne)}>7.1 Rookie Draft Order</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenOneOne)}>7.1.1 Tiebreakers</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sevenTwo)}>7.2 Draft Rules</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(eight)}>Section 8: Abandoned Teams / Refunds</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(nine)}>Section 9: Illegal Starting Lineups / Throwing Games / Tanking</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(ten)}>Section 10: Collusion</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(eleven)}>Section 11: Blanket Clauses</h3>

    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>Section 1: Important Dates</h2>
    
        <h3 class="subSectionHeading" bind:this={oneOne}>1.1 League Renewal Deadline: Prior to Annual Rookie Draft</h3>
            <p>Each team manager must make their payment for the upcoming season prior to the above listed deadline. If payment has not been received by the above listed deadline, the offending team will be forced to auto draft the entirety of the current Rookie Draft. 
            <p>This restriction can be altered at the discretion of the league commissioner (technical issues, extenuating circumstances, etc)</p>

        <h3 class="subSectionHeading" bind:this={oneTwo}>1.2 Annual Rookie Draft: TBD following NFL Draft</h3>
            p>The annual rookie draft will be held after all league members have renewed for the upcoming season and/or after all open team slots have been filled. This will be approximately within 2 weeks following the NFL Draft. On the occasion that scheduling does not permit the Rookie Draft to commence as stated above, a new date will be discussed and set by managers within the league.
            </p>

    <h2 class="sectionHeading" bind:this={two}>Section 2: Fees and Payouts</h2>
            <p>All league finances will be administered by the league commissioner.</p>
    <div class="subBlock">        
        
        <h3 class="subSectionHeading" bind:this={twoOne}>2.1 Yearly Dues</h3>
            <p>Each manager is required to make the necessary payment of $10 per season in order to remain as an active owner.</p>
        
        <h3 class="subSectionHeading" bind:this={twoTwo}>2.2 Payouts</h3>
            <p>The league is a “winner takes all” format. The champion each year shall receive the total of fees collected for the given year, in the amount of $100.</p>
    </div>

    <h2 class="sectionHeading" bind:this={three}>Section 3: Standard Scoring System</h2>
    <div class="subBlock">
            <table class="positionMaximums">
                <tr><td>Passing TD</td><td class="right">4 for each</td></tr>
                <tr><td>Passing Yards</td><td class="right">.04 for 1 yard (1 point for every 25 yards)</td></tr>
                <tr><td>Passing 2-point Conversion</td><td class="right">2 for each</td></tr>
                <tr><td>Interceptions Thrown</td><td class="right">-2 for each</td></tr>
                <tr><td>Pick 6 Thrown</td><td class="right">-1 for each</td></tr>
                <tr><td>Receiving TD</td><td class="right">6 for each</td></tr>
                <tr><td>Receiving Yards</td><td class="right">.1 for each (1 point for every 10 yards)</td></tr>
                <tr><td>Receptions</td><td class="right">.5 point for each</td></tr>
                <tr><td>Receptions (TE Premium)</td><td class="right">.5 additional to TE for each</td></tr>
                <tr><td>Receiving 2-point Conversion</td><td class="right">2 for each</td></tr>
                <tr><td>Rushing TD</td><td class="right">6 for each</td></tr>
                <tr><td>Rushing Yards</td><td class="right">.1 for each (1 point for every 10 yards)</td></tr>
                <tr><td>Rushing 2-point Conversion</td><td class="right">2 for each</td></tr>
                <tr><td>Fumble</td><td class="right">-1 for each</td></tr>
                <tr><td>Fumbles Lost</td><td class="right">-1 for each</td></tr>
                <tr><td>Kickoff or Punt Return TD</td><td class="right">6 for each</td></tr>
                <tr><td>Offensive Fumble Recoveries for TD</td><td class="right">6 for each</td></tr>
              <tr><td>BONUS: 100-199 Yard Rushing Game</td><td class="right">+2 per game</td></tr>
                <tr><td>BONUS: 200+ Yard Rushing Game</td><td class="right">+2 per game</td></tr>
                <tr><td>BONUS: 100-199 Yard Receiving Game</td><td class="right">+2 per game</td></tr>
                <tr><td>BONUS: 200+ Yard Receiving Game</td><td class="right">+2 per game</td></tr>
                <tr><td>BONUS: 300-399 Yard Passing Game</td><td class="right">+2 per game</td></tr>
                <tr><td>BONUS: 400+ Yard Passing Game</td><td class="right">+2 per game</td></tr>
            </table>
        </div>

    <h2 class="sectionHeading" bind:this={four}>Section 4: Rosters</h2>
    <div class="subBlock">
        <h3 class="subSectionHeading" bind:this={fourOne}>4.1 Starting Lineup Requirements</h3>
            <ul>
            <li>QB</li>
            <li>QB</li>
            <li>RB</li>
            <li>RB</li>
            <li>WR</li>
            <li>WR</li>
            <li>WR</li>
            <li>WR</li>
            <li>TE</li>
            <li>FLEX (RB/WR/TE)</li>
            <li>FLEX (RB/WR/TE)</li>
            <li>FLEX (RB/WR/TE)</li>
            </ul>

        <h3 class="subSectionHeading" bind:this={fourTwo}>4.2 Bench Spots</h3>
            <p>Each team has 16 Bench Spots.  *ADDED SPOTS DURING OFFSEASON*</p>

        <h3 class="subSectionHeading" bind:this={fourThree}>4.2 Injured Reserve Spots</h3>
            <p>3 IR Spots (Player must be labeled as IR, Out, Suspended or Covid in the Sleeper App)</p>
    
        <h3 class="subSectionHeading" bind:this={fourFour}>4.3 Taxi Squad</h3>
            <p>Each team has 5 Taxi Squad spots, which may be filled with players entering their rookie seasons. Players may remain on the Taxi for an additional year beyond their rookie season, but must be removed in the subsequent season.</p>
            <p>Players must be declared on the Taxi Squad prior to the beginning of Week 1 of their rookie season. Once Week 1 has begun, rookies will no longer be able to be added to the Taxi, per Sleeper rules.</p>
        <h3 class="subSectionHeading" bind:this={fourFour}>4.4 Weekly Starting Lineup</h3>
            <p>You must submit a valid starting lineup weekly.</p>
            <p>Team managers may adjust lineups up until kickoff of each player's game. Team managers that swap out players for injured or obviously inferior players may forfeit future draft picks or be removed from the league.</p>
            <p>Starting lineups are not allowed to have players on BYE or players who had been listed as OUT with a reasonable amount of time for the team manager to correct the lineup. This is usually only done if the starting of such a player appears to be an attempt to intentionally tank or if the team is potentially abandoned. See “Article IX: Illegal Starting Lineups / Throwing Games / Tanking” for more detailed information.</p>
            <p>Extenuating circumstances do apply, e.g. a plethora of injuries, majority of players on bye, etc which restrict a reasonable lineup to be set. Picking up Free Agents and/or trading to field a full roster is very strongly encouraged in order to keep the league competitive.</p>
        <h3 class="subSectionHeading" bind:this={fourFive}>4.5 Roster Freeze (**UNDER REVIEW**)</h3>
            <p>No free agent pickups are allowed between the conclusion of the fantasy season and the annual rookie draft. Trading is still allowed during this period.* Free agency will be opened at the conclusion of the rookie draft.</p>
            <p>* The commissioner may need to be contacted in order to open the league for a trade to be completed in the offseason.</p>
    </div>

    <h2 class="sectionHeading" bind:this={five}>Section 5: Trading</h2>
  <div class="subBlock">
    <h3 class="subSectionHeading" bind:this={fiveThree}>5.1 Trading Basic Rules</h3>
      <p>3 IR Spots (Player must be labeled as IR, Out, Suspended or Covid in the Sleeper App)</p>
    <h3 class="subSectionHeading" bind:this={fiveThree}>5.2 Trade Deadline **UNDER REVIEW**</h3>
      <p>The trade deadline each season will be week 13.</p>
    <h3 class="subSectionHeading" bind:this={fiveThree}>5.3 Protesting Trades / Reversals</h3>
      <p>If you believe that there is collusion involving a trade, contact the commissioner. If possible, provide evidence as to why you think the trade may be collusive.</p>
      <p>Opinions on unbalanced trades are naturally subjective. Any trade which you believe to be egregiously unbalanced should be brought to the attention of the commissioner for review. If possible, provide evidence as to why you think the trade may be egregiously unbalanced (trade calculator, player value sheets, etc).</p>
    <h3 class="subSectionHeading" bind:this={fiveThree}>5.4 Trade/Roster Accidents</h3>
      <p>If a team manager contacts the commissioner within a reasonable amount of time and says a deal was accepted in error or made an accident in the trade they offered</p>
      <p>If a trade is made while a pick is on the clock and accepted by a team trading away a pick where there isn’t a reasonable amount of time for the team getting the on-the-clock pick to make their selection, a pick may be reverted.</p>
      <p>On rare occasion moves (trade/waiver/move/pick) may be undone as well when reversing another move. This would be due to a transaction being made that either includes assets in the move being reversed or made due to the belief the move being reversed would stand.</p>
      <p>It is always best to alert the other party and the league along with the commissioner as well as trying to trade back with the other party.</p>
    <h3 class="subSectionHeading" bind:this={fiveThree}>5.5 Taxi Trades **UNDER REVIEW**</h3>
      <p>Players which have been placed on a team's taxi squad may be traded. The receiving team may opt to keep the player on their own taxi squad, provided space is available. If no spots are available, the receiving manager may drop a player in order to add the newly acquired player.</p>
      <p>Any transactions which include Taxi to Taxi trades need to be immediately reported to the commissioner. Sleeper by default does not allow for traded players to be added to a team’s taxi squad once the season has started and will have to be handled manually. If notification does not take place within a reasonable time period, the player may not be added to the receiving team’s Taxi Squad.</p>
  </div>

  <h2 class="subSectionHeading" bind:this={six}>Section 6: Playoffs</h2>
      <p>Playoff seeding and bracket are handled by Sleeper. Please see league app/site for details.</p>

  <h2 class="subSectionHeading" bind:this={seven}>Section 7: Rookie Drafts</h2>
  <div class="subBlock">
      <p>Each subsequent year after the startup draft, a draft will be held to distribute rookies. This draft will be held after the NFL Draft.</p>

    <h3 class="subSectionHeading" bind:this={sevenOne}>7.1 Draft Order</h3>
      <ul>
        <li>Picks 1-4 will be decided by fantasy regular season standings (not including fantasy playoffs). They will go in order of lowest win percentage to highest win percentage with points scored on the season as tiebreaker and reverse order of opponent total points scored as a secondary tiebreaker.</li>
        <li>Picks 5 & 6 will be decided between the 2 teams eliminated from Round 1 of the playoffs*</li>
        <li>Picks 7 & 8 will be decided between the 2 teams eliminated from Round 2 of the playoffs*</li>
        <li>Pick 9 goes to the league championship runner-up</li>
        <li>Pick 10 goes to the league champion.</p></li>
      </ul>

      <p>* Determination between picks 5/6 & 7/8 will go in order of lowest win percentage to highest win percentage with points scored on the season as tiebreaker and reverse order of opponent total points scored as a secondary tiebreaker.</p>
        <div class="subBlock">
          <h4 class="subSectionHeading" bind:this={sevenOneOne}>7.1.1 Draft Order Tiebreakers</h3>
            <ul><li>Total Points Scored (fewest gets the higher pick)</li>
              <li>Reverse Order of Opponent Total Points Scored (highest gets the higher pick)</li>
            </ul> 
        </div>
    <h3 class="subSectionHeading" bind:this={sevenTwo}>7.2 Draft Rules</h3>
      <p>The annual rookie draft is an NFL-style linear draft, meaning the draft order will be the same as described above for all rounds.
        Trades are allowed before and during the rookie draft.</p>
  </div>

  <h2 class="subSectionHeading" bind:this={eight}>Section 8: Abandoned Teams / Refunds</h2>
    <p>A team may be deemed abandoned for several reasons including but not limited to failure to actively manage the team (set lineups, make moves required at certain deadlines, etc) or a non-responsive team manager who has not responded to attempts to contact. A team may be deemed abandoned even if they respond, but still do not begin actively managing their team.</p>
    <ul>
      <li>There will be no refunds available once the Rookie Draft has taken place.</li>
      <li>When a team has been deemed abandoned, either because of a suspected cheating owner, being a non-responsive owner, and/or no longer actively managing their team, the commissioner will look for a team manager to take over that team for the remainder of the season. If no manager is immediately available, the commissioner is deemed the owner and will set the lineup weekly according to projections available from Sleeper. No additions, trades or changes beyond setting the best projected lineup available for the team will be made once the commissioner has taken control.</li>
      <li>When a team is abandoned or the owner removed, recent transactions (add/drops, picks, trades, etc) may be reverted. This is done as they may have been made in bad faith and also so the new owner has the right to make these decisions on the team.</li>
    </ul>

  <h2 class="subSectionHeading" bind:this={nine}>Section 9: Illegal Starting Lineups / Throwing Games / Tanking</h2>
    <p>The act of “throwing games” (i.e. losing on purpose by submitting a lineup containing injured players, inactive players, free agents, players on bye, or obviously under-performing players) is strictly prohibited. Although you may prefer a better draft position, intentional tanking creates a win-loss imbalance amongst teams and impacts the competitive integrity of the entire league.</p>
      <ol>
        <li>All determinations of illegal starting lineups, throwing/tanking games will be decided at the sole discretion of the league commissioner and on a case by case basis. Penalties per season may be assessed as described below.</li>
          <ul>
            <li>First Infraction: Warning.</li>
            <li>Second Infraction: Loss of teams 2nd round pick in the following year’s rookie draft. If no 2nd round pick is available the following year, the next available year's second round pick will be lost.</li>
            <li>Third Infraction: Loss of teams 1st round pick in the following year’s rookie draft. If no 1st round pick is available the following year, the next available year's first round pick will be lost. This is in addition to the second infraction 2nd round pick.</li>
          </ul>
        <li>Players on a team’s Taxi Squad are exempt from allegations of throwing or tanking.</li>
        <li>The selling/trading of assets does not constitute throwing/tanking.</li>
        <li>If an offending manager is eventually removed as owner of a team, any lost draft picks may be reinstated by the commissioner. Alterations to the offending team’s draft spot may also be made to compensate for abuses resulting from above infractions.</li>
      </ol>
    <p>Examples of tanking or throwing games which may lead to above infractions being imposed: consistently sitting a known quality player for a lesser quality player, e.g. sitting a top 10 player at any position for a significantly lower generally performing player.</p>
    <p>Don’t Be An Asshole Clause: Player projections are unreliable at best and should not be used as an end all be all for setting lineups. Forcing teams to play the best lineup based on projections would be counterproductive in many cases. So simply, don’t be an asshole, set a competitive lineup.</p>

  <h2 class="subSectionHeading" bind:this={ten}>Section 10: Collusion</h2>
      <p>Player renting is always collusion in any league. It is two teams working together at the detriment of one other team and/or the league. Player renting can be trading a player or players for picks or players and then trading back within the same season. Even if one team acquires slightly more benefit. An example. Team A trades the #1 RB for a 1st and 4th to team B. A week or two later Team B trades said RB back for that 1st. Team A keeps the 4th. Even with benefit, player rentals are always collusion in any league. Trading players not on bye for players on bye and then trading back also falls under this. Trading players to one team making a playoff run and then trading those players back after the season also falls under this. Player rentals are always collusion in any league and can not be allowed even once.</p>
      <p>Offering anything: money, food, goods, or services, or benefits of any kind outside of the actual league in exchange for assets within the league constitutes collusion as well. Such trades will be reversed and owners may be removed from the league without refund. Only trading available picks, players, and FAAB money is allowed.</p>
      <p>Intentionally and knowingly trading better assets in a trade they know is bad to load up another team can be considered collusion.</p>
      <p>Behavior of dropping and adding players between two teams may be considered collusion.</p>
      <p>Behavior of routinely having most or all trades with one other franchise and generally favored towards one team.</p>
      <p>Any working together between two teams in move(s) to help another team win their matchup or the league may be considered collusion.</p>

  <h2 class="subSectionHeading" bind:this={eleven}>Section 11: Blanket Clauses</h2>
      <ol>
        <li>Any league specific rules not outlined in the above document may be covered by Sleeper default rules. Please see league app/site for more details.</li>
        <li>Best Interest Clause: Should circumstances, issues or problems arise for which a remedy is not stated in the rules or bylaws, the commissioner reserves the right to take whatever action deemed necessary in the best interest of the league.</li>
        <li>Any amendments to the preceding document beyond procedural changes, may be brought to a vote (e.g. roster requirement changes, scoring changes. A  supermajority of 7 votes in the affirmative will be required for any bylaw or league rule change to be made.</li>
      </ol>
</div>
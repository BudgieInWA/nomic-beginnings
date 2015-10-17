Rules of Play
=============

**101.** *immutable.* All players must always abide by all the rules listed in the RULES.md file in the master branch of the Game Repository as it appears after the latest change made in the proper way.  


**102.** *immutable.* Initially rules in the 100's are immutable and rules in the 200's are mutable. Rules subsequently enacted or transmuted (that is, changed from immutable to mutable or vice versa) may be immutable or mutable regardless of their numbers, and rules in the Initial Set may be transmuted regardless of their numbers.


**103.** *immutable.* A rule-change is any of the following: (1) the enactment, repeal, or amendment of a mutable rule; (2) the enactment, repeal, or amendment of an amendment of a mutable rule; or (3) the transmutation of an immutable rule into a mutable rule or vice versa.

(Note: This definition implies that, at least initially, all new rules are mutable; immutable rules, as long as they are immutable, may not be amended or repealed; mutable rules, as long as they are mutable, may be amended or repealed; any rule of any status may be transmuted; no rule is absolutely immune to change.)


**104.** *immutable.* All rule-changes proposed in the proper way shall be voted on. They will be adopted if and only if they receive the required number of votes.


**105.** *immutable.* Every player is an eligible voter. Every eligible voter must participate in every vote on rule-changes.


**106.** *immutable.* All proposed rule-changes shall be made in the form of a pull request and voting shall take place in the comments of the pull request. The vote shall be concluded by merging or closing the pull request when the result is for or against adoption respectively.


**107.** *immutable.* No rule-change may take effect earlier than the moment it is reflected in the master branch, even if its wording explicitly states otherwise. No rule-change may have retroactive application.


**108.** *immutable.* When a rule is enacted or modified by a proposal it shall receive a new number equal to the number of the pull request plus 300.


**109.** *immutable.* Rule-changes that transmute immutable rules into mutable rules may be adopted if and only if the vote is unanimous among the eligible voters. Transmutation shall not be implied, but must be stated explicitly in a proposal to take effect.


**110.** *immutable.* In a conflict between a mutable and an immutable rule, the immutable rule takes precedence and the mutable rule shall be entirely void. For the purposes of this rule a proposal to transmute an immutable rule does not "conflict" with that immutable rule.


**111.** *immutable.* If a rule-change as proposed is unclear, ambiguous, paradoxical, or destructive of play, or if it arguably consists of two or more rule-changes compounded or is an amendment that makes no difference, or if it is otherwise of questionable value, then the other players may suggest amendments or argue against the proposal before the vote. A reasonable time must be allowed for this debate. The proponent decides the final form in which the proposal is to be voted on and, unless the Judge has been asked to do so, also decides the time to end debate and vote.


**112.** *immutable.* The state of affairs that constitutes winning may not be altered from achieving n points to any other state of affairs. The magnitude of n and the means of earning points may be changed, and rules that establish a winner when play cannot continue may be enacted and (while they are mutable) be amended or repealed.


**113.** *immutable.* A player always has the option to forfeit the game rather than continue to play or incur a game penalty. No penalty worse than losing, in the judgment of the player to incur it, may be imposed.


**114.** *immutable.* There must always be at least one mutable rule. The adoption of rule-changes must never become completely impermissible.


**115.** *immutable.* Rule-changes that affect rules needed to allow or apply rule-changes are as permissible as other rule-changes. Even rule-changes that amend or repeal their own authority are permissible. No rule-change or type of move is impermissible solely on account of the self-reference or self-application of a rule.


**116.** *immutable.* Whatever is not prohibited or regulated by a rule is permitted and unregulated, with the sole exception of changing the rules (or the contents of the RULES.md in the master branch), which is permitted only when a rule or set of rules explicitly or implicitly permits it.


**201.** *mutable.* Players shall alternate in alphabetical order by username, taking one whole turn apiece. Turns may not be skipped or passed, and parts of turns may not be omitted. All players begin with zero points.


**202.** *mutable.* One turn consists of two parts in this order: (1) proposing one rule-change and having it voted on, and (2) adding the value of the first digit of the merge commit to one's score.


**203.** *mutable.* A rule-change is adopted if and only if the vote is unanimous among the eligible voters. If this rule is not amended by the end of the second complete circuit of turns, it automatically changes to require only a simple majority.


**204.** *mutable.* If and when rule-changes can be adopted without unanimity, the players who vote against winning proposals shall receive 10 points each.


**205.** *mutable.* An adopted rule-change takes full effect at the moment its pull request is merged.


**206.** *mutable.* When a proposed rule-change is defeated, the player who proposed it loses 10 points.


**207.** *mutable.* Each player always has exactly one vote.


**208.** *mutable.* The winner is the first player to achieve 200 (positive) points.


**209.** *mutable.* At no time may there be more than 25 mutable rules.


**210.** *mutable.* Players may not conspire or consult on the making of future rule-changes outside of the repository or in secret unless they are team-mates.


**211.** *mutable.* If two or more mutable rules conflict with one another, or if two or more immutable rules conflict with one another, then the rule with the lowest ordinal number takes precedence.

If at least one of the rules in conflict explicitly says of itself that it defers to another rule (or type of rule) or takes precedence over another rule (or type of rule), then such provisions shall supersede the numerical method for determining precedence.

If two or more rules claim to take precedence over one another or to defer to one another, then the numerical method again governs.


**212.** *mutable.* If players disagree about the legality of a move or the interpretation or application of a rule, then the player preceding the one moving is to be the Judge and decide the question. Disagreement for the purposes of this rule may be created by the insistence of any player. This process is called invoking Judgment.

When Judgment has been invoked, the next player may not begin his or her turn without the consent of a majority of the other players.

The Judge's Judgment may be overruled only by a unanimous vote of the other players taken before the next turn is begun. If a Judge's Judgment is overruled, then the player preceding the Judge in the playing order becomes the new Judge for the question, and so on, except that no player is to be Judge during his or her own turn or during the turn of a team-mate.

Unless a Judge is overruled, one Judge settles all questions arising from the game until the next turn is begun, including questions as to his or her own legitimacy and jurisdiction as Judge.

New Judges are not bound by the decisions of old Judges. New Judges may, however, settle only those questions on which the players currently disagree and that affect the completion of the turn in which Judgment was invoked. All decisions by Judges shall be in accordance with all the rules then in effect; but when the rules are silent, inconsistent, or unclear on the point at issue, then the Judge shall consider game-custom and the spirit of the game before applying other standards.


**213.** *mutable.* If the rules are changed so that further play is impossible, or if the legality of a move cannot be determined with finality, or if by the Judge's best reasoning, not overruled, a move appears equally legal and illegal, then the first player unable to complete a turn is the winner.

This rule takes precedence over every other rule determining the winner. 

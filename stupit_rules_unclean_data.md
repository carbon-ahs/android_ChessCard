
## Colected From: http://elostealo.com/
```
            const databaseRules = [
                // New Rules
                { elo: 750, type: "—New Rule—", title: "The People's Monarch", description: "You can only capture your opponent's pawns with a pawn or&nbsp;king." },
                { elo: 'Magnus', type: "—New Rule—", title: "Hungry Hungry Monarch", description: "You can only capture your opponent's pawns with your&nbsp;king." },

                { elo: 'Magnus', type: "—New Rule—", title: "No Jail Can Hold Me", description: "Your opponent's pawns cannot be captured." },

                { elo: 1000, type: "—New Rule—", title: "Offside Rule", description: "Your attacking pieces can't push ahead of your furthest&nbsp;pawn.<br><br>This lasts as long as you have&nbsp;pawns." },
                { elo: 1000, type: "—New Rule—", title: "Canadian Rules", description: "If you think your opponent has blundered, give them the option to change their move by saying, \"You sure about that,&nbsp;bud?\"<br><br>Only say this once per move." },
                // { elo: 250, type: "—New Rule—", title: "The Anti-'chist", description: "You refuse to take en passant on principal because you think r/anarchychess is an&nbsp;abomination." },

                { elo: 'Magnus', type: "—New Rule—", title: "I Can't Even", description: "You can't capture on even-numbered turns." },
                { elo: 'Magnus', type: "—New Rule—", title: "That's Odd", description: "You can't capture on odd-numbered turns." },

                { elo: 500, type: "—New Rule—", title: "No Take Backsies", description: "You can't immediately recapture after losing a piece or&nbsp;pawn.<br><br>Expires after one lost piece." },
                { elo: 750, type: "—New Rule—", title: "No Take Backsies, Double&nbsp;Stamped&nbsp;It", description: "You can't immediately recapture after losing a piece or&nbsp;pawn.<br><br>Expires after two lost pieces." },
                { elo: 1000, type: "—New Rule—", title: "No Take Backsies, Triple&nbsp;Stamped&nbsp;It", description: "You can't immediately recapture after losing a piece or&nbsp;pawn.<br><br>Expires after three lost pieces." },
                { elo: 'Magnus', type: "—New Rule—", title: "No Take Backsies Times&nbsp;Infinity", description: "You can't immediately recapture after losing a piece or&nbsp;pawn.<br><br>Doesn't Expire." },

                { elo: 750, type: "—New Rule—", title: "Jail", description: "If you have any pieces on the |1st| / ~8th~ rank on turn 20, they're now stuck&nbsp;there." },
                { elo: 1000, type: "—New Rule—", title: "Right To Jail, Right Away", description: "If you have any pieces on the |1st| / ~8th~ rank on turn 15, they're now stuck&nbsp;there." },
                { elo: 'Magnus', type: "—New Rule—", title: "Believe It Or Not, Jail", description: "If you have any pieces on the |1st| / ~8th~ rank on turn 10, they're now stuck&nbsp;there." },

                { elo: 1000, type: "—New Rule—", title: "Enlightened", description: "You must always end your turn with an equal number or more chess pieces on light squares than dark&nbsp;squares." },
                { elo: 1000, type: "—New Rule—", title: "Unenlightened", description: "You must always end your turn with an equal number or more chess pieces on dark squares than light&nbsp;squares." },

                { elo: 500, type: "—New Rule—", title: "Spectrophobia", description: "If your bishop, rook, or queen can capture its same piece, it must run away to a square where it no&nbsp;longer&nbsp;can." },
                { elo: 750, type: "—New Rule—", title: "Unique Snowflake", description: "You can't move the same piece your opponent just moved unless you legally&nbsp;have&nbsp;to.<br><br>This includes pawns." },
                { elo: 250, type: "—New Rule—", title: "Over The Shoulder", description: "<i>Read this rule aloud.</i><br><br>You have to play from the same side as your opponent. If playin online, flip the&nbsp;board." },

                { elo: 250, type: "—New Rule—", title: "Touch-Move", description: "<i>Read this rule aloud.</i><br><br>As soon as your turn is done, you have to touch five chess pieces that you're considering moving on your next turn. You can only choose a different piece if you can't legally move any&nbsp;of&nbsp;them." },
                { elo: 500, type: "—New Rule—", title: "Touch-Move", description: "<i>Read this rule aloud.</i><br><br>As soon as your turn is done, you have to touch four chess pieces that you're considering moving on your next turn. You can only choose a different piece if you can't legally move any&nbsp;of&nbsp;them." },
                { elo: 750, type: "—New Rule—", title: "Touch-Move", description: "<i>Read this rule aloud.</i><br><br>As soon as your turn is done, you have to touch three chess pieces that you're considering moving on your next turn. You can only choose a different piece if you can't legally move any&nbsp;of&nbsp;them." },
                { elo: 1000, type: "—New Rule—", title: "Touch-Move", description: "<i>Read this rule aloud.</i><br><br>As soon as your turn is done, you have to touch two chess pieces that you're considering moving on your next turn. You can only choose a different piece if you can't legally move either&nbsp;one." },
                { elo: 'Magnus', type: "—New Rule—", title: "Touch-Move", description: "<i>Read this rule aloud.</i><br><br>As soon as your turn is done, you have to touch one chess piece that you're considering moving on your next turn. You can only choose a different piece if your opponent captures the piece you've touched, or if you can't legally move&nbsp;it." },


                // Castling Rules
                { elo: 500, type: "—Castling Rule—", title: "Practically Regicide", description: "You can't castle." },
                { elo: 250, type: "—Castling Rule—", title: "You Gotta Fight. For Your Right. To&nbsp;Caaaaastle.", description: "You can only castle if you have a piece or pawn on |ƒ®(4-5)|." },


                // Piece Restriction Categories
                { elo: 750, type: "—King Rule—", title: "Figurehead", description: "Your king can't actually capture anything." },
                { elo: 750, type: "—Queen Rule—", title: "Trophy Wife", description: "Your queen can't actually capture anything." },
                { elo: 750, type: "—Rook Rule—", title: "Fool Of A Rook", description: "Your rooks can't actually capture anything." },
                { elo: 500, type: "—Bishop Rule—", title: "False Prophets", description: "Your bishops can't actually capture anything." },
                { elo: 500, type: "—Knight Rule—", title: "Two Guys In A Cheap Costume", description: "Your knights can't actually capture anything." },

                { elo: 750, type: "—King Rule—", title: "The King of Darkness", description: "Aside from castling, your king can only move to dark&nbsp;squares." },
                { elo: 750, type: "—King Rule—", title: "The King of Light", description: "Aside from castling, your king can only move to light&nbsp;squares." },
                { elo: 750, type: "—Queen Rule—", title: "The Queen of Darkness", description: "Your queen can only move to dark&nbsp;squares." },
                { elo: 750, type: "—Queen Rule—", title: "The Queen of Light", description: "Your queen can only move to light&nbsp;squares." },

                { elo: 500, type: "—Queen Rule—", title: "Before The Clock Strikes&nbsp;12", description: "Your queen can't move after turn&nbsp;12." },
                { elo: 750, type: "—Queen Rule—", title: "Sleeping Beauty", description: "Your queen can't move after turn&nbsp;9." },
                { elo: 1000, type: "—Queen Rule—", title: "Poisoned Apple", description: "Your queen can't move after turn&nbsp;6." },

                { elo: 500, type: "—Rook Rule—", title: "Wrong Permits", description: "Your rooks can't move after turn&nbsp;25." },
                { elo: 750, type: "—Rook Rule—", title: "Not To Code", description: "Your rooks can't move after turn&nbsp;20." },
                { elo: 1000, type: "—Rook Rule—", title: "Condemnable", description: "Your rooks can't move after turn&nbsp;15." },

                { elo: 250, type: "—Bishop Rule—", title: "Long Service", description: "Your bishops can't move after turn&nbsp;20." },
                { elo: 500, type: "—Bishop Rule—", title: "A Sermon Or Two", description: "Your bishops can't move after turn&nbsp;15." },
                { elo: 750, type: "—Bishop Rule—", title: "Quick Prayer", description: "Your bishops can't move after turn&nbsp;10." },

                { elo: 250, type: "—Knight Rule—", title: "Good Night", description: "Your knights can't move after turn&nbsp;20." },
                { elo: 500, type: "—Knight Rule—", title: "Sleep Tight", description: "Your knights can't move after turn&nbsp;15." },
                { elo: 750, type: "—Knight Rule—", title: "Don't Let The Bedbugs&nbsp;Bite", description: "Your knights can't move after turn&nbsp;10." },

                { elo: 500, type: "—Queen Rule—", title: "Queen On Ice", description: "When moving your queen, it must continue forward until it either captures a piece or pawn, is stopped by one of your pieces, or reaches the edge of the&nbsp;board." },
                { elo: 500, type: "—Rook Rule—", title: "Rooks On Ice", description: "When moving your rook, it must continue forward until it either captures a piece or pawn, is stopped by one of your pieces, or reaches the edge of the&nbsp;board." },
                { elo: 500, type: "—Bishop Rule—", title: "Bishops On Ice", description: "When moving your bishop, it must continue forward until it either captures a piece or pawn, is stopped by one of your pieces, or reaches the edge of the&nbsp;board." },

                { elo: 750, type: "—Queen Rule—", title: "The Avenger", description: "You can only move your queen when you're down&nbsp;material." },
                { elo: 500, type: "—Rook Rule—", title: "Sentinels", description: "You can only move your rooks when you're down&nbsp;material." },
                { elo: 500, type: "—Bishop Rule—", title: "Lazari", description: "You can only move your bishops when you're down&nbsp;material." },
                { elo: 500, type: "—Knight Rule—", title: "And They're Off!", description: "You can only move your knights when you're down&nbsp;material." },

                { elo: 500, type: "—Queen Rule—", title: "Short Queen", description: "Your queen can only move a maximum distance of 4 squares at&nbsp;a&nbsp;time." },
                { elo: 500, type: "—Rook Rule—", title: "Short Rook", description: "Your rooks can only move a maximum distance of 4 squares at&nbsp;a&nbsp;time." },
                { elo: 500, type: "—Bishop Rule—", title: "Short Bishop", description: "Your bishops can only move a maximum distance of 3 squares at&nbsp;a&nbsp;time." },

                { elo: 750, type: "—Queen Rule—", title: "Losing Steam", description: "Your queen can move up to 7 squares her first turn, 6 squares her second turn, 5 on her third, and so on until 0. Then she can't&nbsp;move." },
                { elo: 750, type: "—Rook Rule—", title: "Losing Bricks", description: "Your rooks can move up to 7 squares the first time you move a rook, 6 squares the second time, 5 the third, and so on until 0. Then they can't&nbsp;move.<br><br>Castling counts as a move." },
                { elo: 750, type: "—Bishop Rule—", title: "Losing Faith", description: "Your bishops can move up to 7 squares the first time you move a bishop (not really, but stay with me here), 6 squares the second time, 5 the third, and so on until 0. Then they can't&nbsp;move." },

                { elo: 500, type: "—Queen Rule—", title: "Building Steam", description: "Your queen can move 1 square on her first turn, up to 2 squares her second turn, up to 3 on her third, and so on until she gets to full&nbsp;strength." },
                { elo: 250, type: "—Rook Rule—", title: "Building Bricks", description: "Your rooks can move 1 square the first time you move a rook, up to 2 squares the second time, up to 3 the third, and so on until they're at full&nbsp;strength.<br><br>Castling counts as a move." },
                { elo: 250, type: "—Bishop Rule—", title: "Building Faith", description: "Your bishops can move 1 square the first time you move a bishop, up to 2 squares the second time, up to 3 the third, and so on until they're at full&nbsp;strength." },

                { elo: 1000, type: "—Rook Rule—", title: "You've Been Disconnected", description: "If you lose a rook, you can no longer move the other&nbsp;one." },
                { elo: 750, type: "—Bishop Rule—", title: "Apostasy", description: "If you lose a bishop, you can no longer move the other&nbsp;one." },
                { elo: 750, type: "—Knight Rule—", title: "Bonded Pair", description: "If you lose a knight, you can no longer move the other&nbsp;one." },
                { elo: 1000, type: "—Royal Rule—", title: "Bad Breakup", description: "If you lose your queen, you can no longer move your&nbsp;king." },

                { elo: 750, type: "—Queen Rule—", title: "Scaredy Queen", description: "Your queen can't move when threatened." },
                { elo: 750, type: "—Rook Rule—", title: "Scaredy Rook", description: "Your rooks can't move when threatened." },
                { elo: 500, type: "—Bishop Rule—", title: "Scaredy Bishop", description: "Your bishops can't move when threatened." },
                { elo: 500, type: "—Knight Rule—", title: "Scaredy Horse", description: "Your knights can't move when threatened." },

                { elo: 250, type: "—Knight Rule—", title: "Can't Stomp Her", description: "Your knights can't capture the opponent's&nbsp;queen." },
                { elo: 250, type: "—Bishop Rule—", title: "Can't Convert Her", description: "Your bishops can't capture the opponent's&nbsp;queen." },
                { elo: 250, type: "—Rook Rule—", title: "Can't Imprison Her", description: "Your rooks can't capture the opponent's&nbsp;queen." },

                { elo: 500, type: "—Rook Rule—", title: "Ambirookstrous", description: "You must alternate which rook you&nbsp;move.<br><br>Lasts until you lose a&nbsp;rook." },
                { elo: 250, type: "—Bishop Rule—", title: "Ambishopstrous", description: "You must alternate which bishop you&nbsp;move.<br><br>Lasts until you lose a&nbsp;bishop." },
                { elo: 250, type: "—Knight Rule—", title: "Ambiknightstrous", description: "You must alternate which knight you&nbsp;move.<br><br>Lasts until you lose a&nbsp;knight." },

                // King Restrictions
                { elo: 1000, type: "-King Rule—", title: "Immobile Noble", description: "You can't move your king." },
                { elo: 750, type: "—King Rule—", title: "Legal Regal", description: "Your king can only move if it's the only legal&nbsp;move." },

                { elo: 750, type: "—King Rule—", title: "Dancing King", description: "You can only respond to checks by moving your&nbsp;king. If your king can't move out of check or capture the attacking piece, it's&nbsp;mate." },
                { elo: 1000, type: "—King Rule—", title: "I Want To Live Like Common&nbsp;People", description: "Your king moves like a pawn, and can only capture&nbsp;diagonally. If it reaches the |8th| / ~1st~ rank, it can \"promote\" to a&nbsp;regular&nbsp;king." },

                { elo: 750, type: "—King Rule—", title: "f Is For \"Familiar\"", description: "Your king must always be touching the |f| pawn. If you lose the |f| pawn, your king can no longer&nbsp;move." },
                { elo: 750, type: "—King Rule—", title: "Heavy Is The Head That Wears The&nbsp;Crown", description: "Your king can't leave the |1st| / ~8th~&nbsp;rank." },


                // Queen Restrictions
                { elo: 500, type: "—Queen Rule—", title: "The Quook", description: "Alakazam, alakazook. Your queen now moves just like a rook." },
                { elo: 500, type: "—Queen Rule—", title: "The Quishop", description: "Alakazam, alakazishop. Your queen now moves just like a&nbsp;bishop." },
                { elo: 750, type: "—Queen Rule—", title: "The Quing", description: "Alakazam, alakazing. Your queen now moves just like a&nbsp;king." },
                { elo: 750, type: "—Queen Rule—", title: "The Quawn", description: "Alakazam, alakazawn. Your queen now moves just like a pawn, and can only capture&nbsp;diagonally.<br><br>If you reach the |8th| / ~1st~ rank, it can \"promote\" to a regular queen&nbsp;again." },

                { elo: 750, type: "—Queen Rule—", title: "Punching Down", description: "Your queen can only capture pawns." },
                { elo: 750, type: "—Queen Rule—", title: "Demolition Woman", description: "Your queen can only capture rooks." },
                { elo: 750, type: "—Queen Rule—", title: "Heiress To The Elmer's&nbsp;Fortune", description: "Your queen can only capture knights." },
                { elo: 750, type: "—Queen Rule—", title: "Anti-Theist", description: "Your queen can only capture bishops." },
                { elo: 500, type: "—Queen Rule—", title: "Bully", description: "Your queen can only capture chess pieces that aren't threatening&nbsp;it." },

                // { elo: 750, type: "—Queen Rule—", title: "Lone Wolf", description: "You can't move your queen to a defended square, and you can't move any chess pieces to where they would defend your&nbsp;queen." },
                // { elo: 750, type: "—Queen Rule—", title: "Support Structure", description: "You can't move your queen to an undefended square, and you can't move a piece or pawn if it would leave your queen&nbsp;undefended." },


                // Royal Restrictions
                { elo: 750, type: "—Royal Rule—", title: "Ball And Chain", description: "Your king and queen must be within two squares of each other, as long as your queen shall&nbsp;live." },
                { elo: 1000, type: "—Royal Rule—", title: "Mawwiage", description: "Your king and queen must always be next to each other, either directly or diagonally, as long as your queen shall&nbsp;live." },
                { elo: 'Magnus', type: "—Royal Rule—", title: "Wuv, Twue Wuv", description: "Your king and queen must always be next to each other, either directly or&nbsp;diagonally.<br><br>If you lose your queen, you&nbsp;must&nbsp;resign." },
                { elo: 'Magnus', type: "—Royal Rule—", title: "Immobile Nobles", description: "Your king and queen can't move.<br><br>If you lose your queen, you&nbsp;must&nbsp;resign." },


                // Rook Restrictions
                // { elo: 750, type: "—Rook Rule—", title: "Magnet In The Middle", description: "Every move you make with your rooks must bring them either an equal distance to or one square closer to |d4| / ~d5~ for your |a| rook, and |e4| / ~e5~ for your |h| rook. Once there, they can't&nbsp;escape." },
                { elo: 500, type: "—Rook Rule—", title: "No Look Rooks", description: "You can't connect your rooks.<br><br>If your opponent makes a move that connects them, you must disconnect them on your next&nbsp;move." },

                { elo: 1000, type: "—Rook Rule—", title: "Rooks On Rails", description: "Your rooks can't leave the |a| and |h| files." },
                { elo: 1000, type: "—Rook Rule—", title: "Galaga", description: "Your rooks can't leave the |1st| / ~8th~ rank." },
                { elo: 750, type: "—Rook Rule—", title: "Border Guards", description: "Your rooks can only move along the |a| and |h| files and the 1st and 8th&nbsp;rank." },

                { elo: 1000, type: "—Rook Rule—", title: "Sidesteppers", description: "Aside from castling, your rooks can only move left and right one square at a&nbsp;time." },
                { elo: 1000, type: "—Rook Rule—", title: "Space Invaders", description: "Your rooks can only move up and down one square at a&nbsp;time." },
                { elo: 'Magnus', type: "—Rook Rule—", title: "Brick By Brick", description: "Your rooks can only move one square at a&nbsp;time." },


                // Bishop Restrictions
                { elo: 750, type: "—Bishop Rule—", title: "Born To Snipe", description: "Your bishops cannot move to the |d| or |e| files except to&nbsp;capture." },
                { elo: 500, type: "—Bishop Rule—", title: "All The Angles", description: "Your bishops cannot move to the |a| or |h| files except to&nbsp;capture." },


                // Knight Restrictions
                { elo: 750, type: "—Knight Rule—", title: "You're Grounded, Mister!", description: "Your knights can't jump. They can only move if they have a clear diagonal or horizontal/vertical square next&nbsp;to&nbsp;them." },
                { elo: 500, type: "—Knight Rule—", title: "Show Ponies", description: "Knights can only move if it involves jumping over at least one piece or&nbsp;pawn." },

                { elo: 250, type: "—Knight Rule—", title: "Smart Knights Only", description: "Your knights cannot land on the |a| or |h| file, or the |1st| or&nbsp;|8th|&nbsp;rank." },

                { elo: 500, type: "—Knight Rule—", title: "Riders On The Storm", description: "You must always have a knight on a dark&nbsp;square.<br><br>Lasts until you lose a knight." },
                { elo: 500, type: "—Knight Rule—", title: "Knights In White Satin", description: "You must always have a knight on a light&nbsp;square.<br><br>Lasts until you lose a knight." },

                { elo: 500, type: "—Knight Rule—", title: "Centre Stable", description: "Once your knights enter the 4th and 5th ranks, they can no longer&nbsp;leave." },


                // { elo: 500, type: "—Knight Rule—", title: "Zombie Paper", description: "If you move your knight past the |5th| / ~4th~ rank, it becomes stuck and can't be moved&nbsp;again." },


                // Pawn Restrictions
                { elo: 500, type: "—Pawn Rule—", title: "Slowpokes", description: "Your pawns can only move one square on their first&nbsp;move." },
                { elo: 500, type: "—Pawn Rule—", title: "Double Time", description: "Your pawns <i>must</i> move two squares on their first&nbsp;move." },

                { elo: 500, type: "—Pawn Rule—", title: "Particular Pawns", description: "You can only move four of your pawns." },
                { elo: 750, type: "—Pawn Rule—", title: "'Portant Pawns", description: "You can only move three of your pawns." },
                { elo: 1000, type: "—Pawn Rule—", title: "Pair Of Pawns", description: "You can only move two of your pawns." },
                { elo: 'Magnus', type: "—Pawn Rule—", title: "Pick A Pawn, Any&nbsp;Pawn", description: "You can only move one of your pawns." },
                { elo: 1000, type: "—Pawn Rule—", title: "Red Rover", description: "You can only have one pawn off off the opening line at&nbsp;a&nbsp;time.<br><br>You can only move your next pawn if the previous one is promoted or&nbsp;captured." },

                { elo: 1000, type: "—Pawn Rule—", title: "Pawn v. Pawn", description: "You can only capture your opponent's pawns with your&nbsp;pawns." },
                { elo: 'Magnus', type: "—Pawn Rule—", title: "Wide Peepos", description: "You can only move your |a| and |h| pawns." },
                { elo: 250, type: "—Pawn Rule—", title: "Feingold is Forced", description: "You can't move your |f| pawn, not even to&nbsp;capture." },

                { elo: 500, type: "—Pawn Rule—", title: "Stick Together!", description: "You can only move a pawn if it's touching another pawn, either directly or&nbsp;diagonally." },
                { elo: 500, type: "—Pawn Rule—", title: "Emotional Support", description: "You can only move a pawn if it's touching another of your chess pieces, either directly or&nbsp;diagonally." },
                { elo: 250, type: "—Pawn Rule—", title: "Stranded", description: "Isolated pawns can't move." },

                { elo: 750, type: "—Pawn Rule—", title: "Centre Game", description: "You can only move the four centre&nbsp;pawns.<br><br>If a pawn captures its way into the 4 outside files, it can still&nbsp;move." },
                { elo: 1000, type: "—Pawn Rule—", title: "Wing Game", description: "You can only move the four outside&nbsp;pawns.<br><br>If a pawn captures its way into the 4 centre files, it can still&nbsp;move." },

                { elo: 500, type: "—Pawn Rule—", title: "To The Left", description: "Your pawns can only capture to the left." },
                { elo: 500, type: "—Pawn Rule—", title: "To The Right", description: "Your pawns can only capture to the right." },

                { elo: 750, type: "—Pawn Rule—", title: "Pawn Paralysis", description: "If your opponent takes a pawn, you can't move any pawns on the next&nbsp;turn." },

                { elo: 1000, type: "—Pawn Rule—", title: "De-fense!!", description: "Your pawns can't go into your opponent's territory." },
                { elo: 750, type: "—Pawn Rule—", title: "Follow The Leader", description: "Your pawns can only advance as far as your furthest attacking&nbsp;piece." },

                { elo: 'Magnus', type: "—Pawn Rule—", title: "Animosity", description: "Your pawns can only capture other&nbsp;pawns." },
                { elo: 'Magnus', type: "—Pawn Rule—", title: "Lepers", description: "Your pawns cannot capture other&nbsp;pawns." },

                { elo: 750, type: "—Pawn Rule—", title: "Just Passing Through", description: "Your pawns cannot capture any chess pieces on the ®(3-6)*&nbsp;rank." },
                { elo: 750, type: "—Pawn Rule—", title: "Just Crashing Through", description: "Your pawns can only reach the ®(3-6)* rank by&nbsp;capturing." },

                { elo: 250, type: "—Pawn Rule—", title: "John&<br>Paul&<br>Ringo&<br>George.", description: "Only your |ƒ(1-2)|, |ƒ(3-4)|, |ƒ(5-6)|, and |ƒ(7-8)| pawns can promote." },
                { elo: 500, type: "—Pawn Rule—", title: "The Three Amigos", description: "Only your |ƒ(1-3)|, |ƒ(4-5)|, and |ƒ(6-8)| pawns can promote." },
                { elo: 750, type: "—Pawn Rule—", title: "Sam & Frodo", description: "Only your |ƒ(1-4)| and |ƒ(5-8)| pawns can promote." },
                { elo: 1000, type: "—Pawn Rule—", title: "You Were The Chosen&nbsp;Pawn!", description: "Only your |ƒ| pawn can promote." },

                { elo: 'Magnus', type: "—Pawn Rule—", title: "Solidarity", description: "If you lose your |ƒ| pawn, the rest of your pawns can no longer&nbsp;move." },


                // Book Fair
                { elo: 250, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Meet&nbsp;Up", description: "<i>The Pawn Brahs make plans to grab a poutine after school, but their classroom portables are so far apart! Can they find their way to each other when everyone runs into the schoolyard after class? Or will they stay separated until they get picked up and miss out on their cheese curds and&nbsp;gravy?</i><br><br>Your |a| and |e| pawns can only capture towards each&nbsp;other." },
                { elo: 250, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Sleep&nbsp;In", description: "<i>Quel dommage! The Pawn Brahs slept through their alarms and now there isn't enough time to walk to hockey practice! Can they find enough loonies in the couch to pay for their bus ride to the rink? Or will Coach Rookerson have them skating laps to make up for being&nbsp;late?</i><br><br>Your |a| and |e| pawns can't move until turn 15." },
                { elo: 250, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Are&nbsp;Full", description: "<i>The Pawn Brahs are invited to grandma's for AAA prime Alberta Angus beef, but they went and spoiled their appetites by eating ketchup Ruffles all day! Will they fess up to grandma about their mistake and miss steak? Or will they find space in their stomachs to eat up&nbsp;anyway?</i><br><br>Your |a| and |e| pawns are too full to eat any&nbsp;pieces." },
                { elo: 250, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Go To An&nbsp;AYCE", description: "<i>The Pawn Brahs get invited to a friend's birthday party at the Mandarin, and there's so much food to try that they can't stop filling their plates. But will they be able to eat it all when they get back to their table? Or will their eyes have been too big for their&nbsp;stomachs?</i><br><br>If your |a| or |e| pawn can capture a piece or pawn, it&nbsp;must." },
                { elo: 250, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Get&nbsp;Even", description: "<i>\"Car!\" The Pawn Brahs invite the kids from the cul de sac one street over to come play street hockey, but they can't seem to win a game! Can they tie it up by wristing a couple orange balls up into the top shelf where Aunt Jemima keeps the peanut butter? Or will their neighbours take them to the cleaners for&nbsp;good?</i><br><br>Your |a| and |e| pawns can only move on even-numbered&nbsp;turns." },
                { elo: 250, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Act&nbsp;Odd", description: "<i>After the Pawn Brahs don't feel like eating their beavertails for dessert, skip Saturday Night Hockey on CBC, and won't listen to their favourite Tragically Hip CD, their parents drive them a few kilometres to see the family doctor. Are they coming down with something? Or are they just playing make believe for&nbsp;attention?</i><br><br>Your |a| and |e| pawns can only move on odd-numbered&nbsp;turns." },
                { elo: 250, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Stay Close To&nbsp;Home", description: "<i>The Pawn Brahs want to go off on an adventure with their friends, but it's already getting dark and mom says it'll be dinner time soon. Can they convince their friends to find adventure without leaving the neighbourhood? Or will they get left behind to play on their own until the streetlights come&nbsp;on?</i><br><br> Your |a| and |e| pawns can't go past the |5th| / ~4th~ rank." },
                // { elo: 250, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Take An Exam", description: "If you move your |a| or |e| pawn, the other one must copy the move on the next turn. If they can't copy it, then they fail and neither pawn can move&nbsp;anymore." },
                { elo: 250, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Take&nbsp;Turns", description: "<i>The Pawn Brahs got a new Nintendo game called Blades of Steel, but they only have one controller to play with. Will they be able to play nice and take turns with each other? Or will they act up and force mom to hide the Nintendo from&nbsp;them?</i><br><br>You must alternate moving your |a| and |e| pawns." },
                { elo: 250, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Stick&nbsp;Together", description: "<i>When the rep league scout Mrs. Queensly comes looking for star players for her hockey team, the Pawn Brahs lace up to impress her. But when she reveals that she can only take one of them, are the Pawn Brahs willing to split up for a shot at glory? Or will they refuse to abandon each other like a bag of&nbsp;pylons?</i><br><br>If you lose your |a| or |e| pawn, the other one can no longer&nbsp;move." },
                { elo: 500, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Rock 'Em and Sock&nbsp;'Em", description: "<i>Coach Rookerson thinks that the Pawn Brahs skate well enough to make rep, but if they're going to play hockey with the big kids from all around the province they'll need to practice their bodychecking first. Can the Pawn Brahs get good enough at playing rough before tryouts? Or will they get left behind like an old&nbsp;zamboni?</i><br><br>You can only move your |a| and |e| pawns by&nbsp;capturing." },
                { elo: 500, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Lead The&nbsp;Way", description: "<i>Sorry! When their boy scout troupe gets lost while portaging in Algonquin Park, only the Pawn Brahs can remember the way back. Now it's up to them to get everyone safely back to camp before they miss out on spider dogs at the bonfire. But do they have enough GORP to keep everyone energized for the hike?</i><br><br>No other pawn can be ahead of your |a| or |e|&nbsp;pawn." },
                { elo: 500, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Have&nbsp;Indigestion", description: "<i>Oh no! The Pawn Brahs ate some leftover Kraft Dinner that'd been out on the counter for too long, and now they've got upset stomachs. Will they find the Pepto in the medicine cupboard? Or will they be sick to their stomachs all&nbsp;day&nbsp;long?</i><br><br>If you capture a piece with your |a| or |e| pawn, it can no longer&nbsp;move." },
                { elo: 500, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Want To&nbsp;Rule", description: "<i>When their school has a model Parliament project, the Pawn Brahs are assigned to be local MPs. But that's not enough for them, and they decide that they're going to be the Premiers of their provinces. Can they prove to Mrs. Knightly that they're up to the task? Or will the other students get elected to mock Parliament&nbsp;instead?</i><br><br>You can only promote your |a| and |e| pawns." },
                { elo: 500, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Get In A&nbsp;Fight", description: "<i>After an argument over whose turn it is to do shovel the driveway, the Pawn Brahs decide that they don't want to hang out with each other anymore. Will they keep their feud up forever? Or will they learn to forgive each other and shovel the driveway&nbsp;together?</i><br><br>Your |a| pawn can't capture, and your |e| pawn can only capture toward the |h|&nbsp;file." },
                { elo: 500, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Stay Home Sick", description: "<i>Uh oh! The Pawn Brahs drank too much bagged milk and now they're sick to their stomachs. They ask to stay home from school, but are they really under the weather? Or are they pretending so they can avoid taking their test on the metric&nbsp;system?</i><br><br>Your |a| and |e| pawns can't move." },
                { elo: 750, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Go It&nbsp;Alone", description: "<i>The Pawn Brahs have to do an assignment about the Prime Minister with their classmates. But instead of working together as a team, they decide to go it alone. Will the Pawn Brahs be able to finish their project by themselves? Or will they learn a valuable lesson about&nbsp;teamwork?</i><br><br>You can only move your |a| and |e| pawns." },
                { elo: 750, type: "—Scholastic Book Fair—", title: "The Pawn Brahs Need&nbsp;Protection", description: "<i>Holy mackinaw! When a rival hockey team comes to town for a game of shinny on the pond, the Pawn Brahs are the only players who can stand in their way. Can the rest of the team protect them on the ice so they can clap a few biscuits into the basket? Or will their rivals deke past the enforcers to jersey them one-by-one?</i><br><br>If you lose your |a| and |e| pawns, you&nbsp;must&nbsp;resign." },


                // Piece Restrictions
                { elo: 1000, type: "—Piece Restriction—", title: "Poison Pawns", description: "Once you capture a pawn, you can no longer move that&nbsp;piece." },

                { elo: 750, type: "—Piece Restriction—", title: "Actual Zombies (Boyle)", description: "Your chess pieces must always move their maximum distance unless capturing a piece, colliding with a friendly piece, or hitting the edge of the&nbsp;board.<br><br>Knights move as normal because horses are immune to The&nbsp;Rage." },
                { elo: 'Magnus', type: "—Piece Restriction—", title: "Actual Zombies (Romero)", description: "Your chess pieces can only move one square at a time, and never&nbsp;backwards.<br><br>Knights move as normal because horses are immune to&nbsp;infection." },

                { elo: 1000, type: "—Piece Restriction—", title: "Everybody Take Turns", description: "You can't ever move the same piece or pawn twice in&nbsp;a&nbsp;row." },

                { elo: 250, type: "—Piece Restriction—", title: "Fight Or Flight", description: "If your bishop, rook, or queen can attack its same piece, it must either capture it, or run away to a square where it can no longer attack&nbsp;that&nbsp;piece." },
                { elo: 500, type: "—Piece Restriction—", title: "Self Destruct", description: "If your bishop, rook, or queen can attack its same piece, it&nbsp;must&nbsp;capture." },
                { elo: 500, type: "—Piece Restriction—", title: "Self Respect", description: "You can't capture a piece with that same type of&nbsp;piece.<br><br>Pawns are okay." },

                { elo: 500, type: "—King Rule—", title: "Progressive Ruler", description: "Your king cannot move backwards." },
                { elo: 500, type: "—Queen Rule—", title: "The Queen Wants To Queen", description: "Your queen cannot move backwards." },
                { elo: 750, type: "—Rook Rule—", title: "Rooks Ahead", description: "Your rooks cannot move backwards." },
                { elo: 500, type: "—Bishop Rule—", title: "Missionaries", description: "Your bishops cannot move backwards." },
                { elo: 500, type: "—Knight Rule—", title: "Chaaaaaarge!!", description: "Your knights cannot move backwards." },
                { elo: 'Magnus', type: "—Piece Rule—", title: "Burn The Boats!", description: "Your pieces cannot move backwards." },

                { elo: 750, type: "—King Rule—", title: "Close Quarters Combat", description: "Your king can only move if it's to capture a piece or pawn. This means no&nbsp;castling." },
                { elo: 750, type: "—Queen Rule—", title: "\"Her vision is based on&nbsp;movement.\"", description: "Your queen can only move if it's to capture a piece or&nbsp;pawn." },
                { elo: 750, type: "—Rook Rule—", title: "Straight Shooters", description: "Your rooks can only move if it's to capture a piece or pawn. This means no&nbsp;castling." },
                { elo: 500, type: "—Bishop Rule—", title: "\"26 conversions in A.D 46!\"", description: "Your bishops can only move if it's to capture a piece or&nbsp;pawn." },
                { elo: 500, type: "—Knight Rule—", title: "Pouncers Only", description: "Your knights can only move if it's to capture a piece or&nbsp;pawn." },

                { elo: 750, type: "—Piece Restriction—", title: "Sneak", description: "No piece can move more than four ranks forward at&nbsp;a&nbsp;time." },
                { elo: 1000, type: "—Piece Restriction—", title: "Creep", description: "No piece can move more than three ranks forward at&nbsp;a&nbsp;time." },
                { elo: 'Magnus', type: "—Piece Restriction—", title: "Crawl", description: "No piece can move more than two ranks forward at&nbsp;a&nbsp;time." },

                { elo: 750, type: "—Piece Restriction—", title: "Union Mandated Break", description: "A piece or pawn can't be moved again the turn after it captures&nbsp;something." },

                // { elo: 'Magnus', type: "—Piece Restriction—", title: "No Pacifists Allowed", description: "You can only move a knight, bishop, rook, or queen if they're checking, capturing, or moving into a position where they can attack another&nbsp;piece." },
                { elo: 500, type: "—Piece Restriction—", title: "Deer In The Headlights", description: "You can't move pinned pieces." },
                { elo: 1000, type: "—Piece Restriction—", title: "Shortsighted", description: "Your bishops, rooks, and queen can only move a maximum of four squares at&nbsp;once." },

                { elo: 500, type: "—Piece Restriction—", title: "Piece Repellent", description: "You can't place a piece or pawn next to your opponent's king, either directly or&nbsp;diagonally." },

                { elo: 1000, type: "—Piece Restriction—", title: "Stay On Your Side", description: "Your chess pieces can't cross the centre line between the |d| and |e|&nbsp;files." },

                // { elo: 'Magnus', type: "—Piece Restriction—", title: "Blunderbuss", description: "You cannot move a knight, bishop, or rook to a square where it will defend or be defended by a knight, bishop, or&nbsp;rook." },

                { elo: 250, type: "—Piece Restriction—", title: "Headstart", description: "You can't capture any chess pieces until you're down at least 1 point of material for a full&nbsp;turn." },
                { elo: 500, type: "—Piece Restriction—", title: "Rally Cap", description: "You can't capture any chess pieces until you're down at least 3 points of material for a full&nbsp;turn." },
                { elo: 750, type: "—Piece Restriction—", title: "Comeback Kid", description: "You can't capture any chess pieces until you're down at least 5 points of material for a full&nbsp;turn." },
                { elo: 1000, type: "—Piece Restriction—", title: "Back From The Dead", description: "You can't capture any chess pieces until you're down at least 7 points of material for a full&nbsp;turn." },
                { elo: 'Magnus', type: "—Piece Restriction—", title: "Back From The Dead", description: "You can't capture any chess pieces until you're down at least 7 points of material for a full&nbsp;turn." },


                // OP Opponent
                { elo: 1000, type: "—OP Opponent—", title: "Medusa", description: "If your opponent's queen can see a piece or pawn, that piece can't&nbsp;move.<br><br>Your knight is the only hero who can capture&nbsp;it." },
                { elo: 1000, type: "—OP Opponent—", title: "Panopticon", description: "If your opponent's rook can see a piece or pawn, that piece can't&nbsp;move." },
                { elo: 750, type: "—OP Opponent—", title: "God Sees All", description: "If your opponent's bishop can see a piece or pawn, that piece can't&nbsp;move." },
                { elo: 750, type: "—OP Opponent—", title: "Warhorse", description: "If your opponent's knight can attack a piece or pawn, that piece can't&nbsp;move." },

                { elo: 1000, type: "—OP Opponent—", title: "Stonework Enjoyer", description: "You can't capture rooks." },
                { elo: 1000, type: "—OP Opponent—", title: "Sacred", description: "You can't capture bishops." },
                { elo: 1000, type: "—OP Opponent—", title: "No Animals Were Harmed In The Playing Of This Chess&nbsp;Game", description: "You can't capture knights." },

                { elo: 750, type: "—OP Opponent—", title: "Venomous Pawns", description: "If your knight, bishop, rook, queen, or king is being attacked by a pawn, that piece cannot&nbsp;move." },
                { elo: 'Magnus', type: "—OP Opponent—", title: "Sticky Pawns", description: "If your knight, bishop, rook, queen, or king is touching an opponent's pawn, either directly or diagonally, that piece cannot&nbsp;move." },


                // Endgame Rules
                { elo: 500, type: "—Endgame Rule—", title: "Hunker Down", description: "Once castled, your king cannot move until the&nbsp;<div class='tooltip'>endgame<span class='tooltiptext'>Fittingly, we'll define this as around the time your king feels safe enough to come out of his&nbsp;castle.</span></div>." },
                { elo: 500, type: "—Endgame Rule—", title: "Reactionary", description: "When you reach the <div class='tooltip'>endgame<span class='tooltiptext'>About the time when the queens have been traded and each side only has a couple pieces&nbsp;left.</span></div>, the king can only be moved when it's in check or it is the only legal&nbsp;move." },
                { elo: 500, type: "—Endgame Rule—", title: "Stingy", description: "If you reach the <div class='tooltip'>endgame<span class='tooltiptext'>We'll say it's when both players have less than 10 points of material&nbsp;left.</span></div>, you lose." },
                { elo: 500, type: "—Endgame Rule—", title: "Friendgame", description: "When you reach the <div class='tooltip'>endgame<span class='tooltiptext'>Let's call it when either player has one of the following: a) 1 queen, b) 2 rooks, c) 1 rook and 1 minor piece, or d) 3 or fewer minor pieces.</span></div>, you must offer a draw." },


                // Board Restrictions
                { elo: 500, type: "—Board Restriction—", title: "There Is No Square", description: "You can't put any chess pieces on—nor travel through—the&nbsp;|ƒ®(3-6)|&nbsp;square." },
                { elo: 1000, type: "—Board Restriction—", title: "There Are No Squares", description: "You can't put any chess pieces on—nor travel through—the |ƒ®(3-4)| or |ƒ®(5-6)|&nbsp;square." },

                { elo: 250, type: "—Board Restriction—", title: "The Centre Is Icky", description: "You can only have two chess pieces on the four centre squares at any given&nbsp;time." },
                { elo: 500, type: "—Board Restriction—", title: "The Centre Is Toxic", description: "You can only have one piece or pawns on the four centre squares at any given&nbsp;time." },
                { elo: 1000, type: "—Board Restriction—", title: "The Centre Is Lava", description: "You can't place any chess pieces on the four centre&nbsp;squares." },
                { elo: 'Magnus', type: "—Board Restriction—", title: "The Centre Is Radioactive", description: "You can't place any chess pieces on—nor travel through—the four centre&nbsp;squares." },

                // { elo: 1000, type: "—Board Restriction—", title: "Inner Space", description: "If you land a piece or pawn between |b2| and |g7|, it cannot leave that inner&nbsp;space." },
                // { elo: 'Magnus', type: "—Board Restriction—", title: "Outer Space", description: "If you land a piece or pawn on the |a| or |h| file, or the 1st or 8th rank, it cannot leave that outer&nbsp;space." },
                { elo: 'Magnus', type: "—Board Restriction—", title: "Black Hole", description: "If you land a piece or pawn in any of the centre four squares, it can no longer&nbsp;move." },

                { elo: 'Magnus', type: "—Board Restriction—", title: "The Nightman", description: "You can only capture chess pieces on dark coloured&nbsp;squares.<br><br>You can still mate a king on a light&nbsp;square." },
                { elo: 'Magnus', type: "—Board Restriction—", title: "The Dayman", description: "You can only capture chess pieces on light coloured&nbsp;squares.<br><br>You can still mate a king on a dark&nbsp;square." },

                { elo: 250, type: "—Board Restriction—", title: "Square Trap!", description: "If you land a piece or pawn on |ƒ®(3-6)|, that piece can no longer&nbsp;move." },
                { elo: 500, type: "—Board Restriction—", title: "Square Trap!!", description: "If you land a piece or pawn on |ƒ(1-4)®(3-6)| or |ƒ(5-8)®(3-6)|, that piece can no longer&nbsp;move." },
                { elo: 750, type: "—Board Restriction—", title: "Square Trap!!!", description: "If you land a piece or pawn on |ƒ(1-3)®(3-6)|, |ƒ(4-5)®(3-6)|, or |ƒ(6-8)®(3-6)|, that piece can no longer&nbsp;move." },
                { elo: 1000, type: "—Board Restriction—", title: "Square Trap!!!!", description: "If you land a piece or pawn on |ƒ(1-2)®(3-6)|, |ƒ(3-4)®(3-6)|, |ƒ(5-6)®(3-6)|, or |ƒ(7-8)®(3-6)|, that piece can no longer&nbsp;move." },
                { elo: 'Magnus', type: "—Board Restriction—", title: "Square Trap!!!!!", description: "If you land a piece or pawn on |ƒ(1-3)®(3-4)|, |ƒ(1-3)®(5-6)|, |ƒ(4-5)®(3-6)|, |ƒ(6-8)®(3-4)|, or |ƒ(6-8)®(5-6)|, that piece can no longer&nbsp;move." },

                // { elo: 750, type: "—Board Restriction—", title: "Cover Me", description: "You must always have a piece or pawn on the |3rd| or ~6th~ rank of the |ƒ| file at the end of your turn." },

                { elo: 1000, type: "—Board Restriction—", title: "A River Runs Through&nbsp;It", description: "You can't land any chess pieces on the |3rd| / ~6th~&nbsp;rank." },

                // { elo: 'Magnus', type: "—Board Restriction—", title: "The Grand Canyon", description: "You can't land any chess pieces on the |3rd| or |4th| rank.<br><br>Your pawns can climb through." },


                // Forced Move
                // { elo: 500, type: "—Forced Move—", title: "Use The Fork", description: "If your knight can move to a square where it forks multiple pieces, it must go there.<br><br>You must also say, \"May the fork be with you,\" each&nbsp;time.<br><br><br><i><font size=-1>Credit to Reddit user hella070</font></i>" },
                // { elo: 500, type: "—Forced Move—", title: "Just Checking", description: "If you can sacrifice a bishop to check the king, you have to.<br><br>You must say, \"Juuuuust checkin',\" each&nbsp;time." },

                { elo: 500, type: "—Forced Move—", title: "Easing the Tension, Baby", description: "Your pawns always capture pawns when they&nbsp;can.<br><br>This includes en passant." },
                { elo: 750, type: "—Forced Move—", title: "The Simplifier", description: "If you can trade for a piece of equal or greater value, you&nbsp;must.<br><br>Knights and bishops count as equal. But this doesn't include&nbsp;pawns." },
                { elo: 1000, type: "—Forced Move—", title: "The Simplifier II: Even&nbsp;Simpler", description: "If you can trade for a piece of equal or greater value, you&nbsp;must.<br><br>Knights and bishops count as equal, and this does include&nbsp;pawns." },

                { elo: 250, type: "—Forced Move—", title: "Wooden Magnet", description: "If you can take a piece or pawn, you have to take the&nbsp;piece.<br><br>Expires after one capture." },
                { elo: 500, type: "—Forced Move—", title: "Electromagnet", description: "If you can take a piece or pawn, you have to take the&nbsp;piece.<br><br>Expires after two captures." },
                { elo: 750, type: "—Forced Move—", title: "Chess Magnetic", description: "If you can take a piece or pawn, you have to take the&nbsp;piece.<br><br>Expires after three captures." },
                { elo: 1000, type: "—Forced Move—", title: "Straight-Up Antichess", description: "If you can take a piece or pawn, you have to take&nbsp;the piece.<br><br>Does not expire." },

                // { elo: 250, type: "—Forced Move—", title: "The Anarchist", description: "En passant is forced." },
                { elo: 500, type: "—Forced Move—", title: "Counterpunch", description: "If your opponent captures a piece or pawn, you must retaliate by capturing a piece back if you&nbsp;can.<br><br>If there's a choice, you can choose which piece to&nbsp;capture." },
                { elo: 750, type: "—Forced Move—", title: "Cheap Shot", description: "If your opponent captures a piece or pawn, you must retaliate by capturing a piece back if you&nbsp;can.<br><br>If there's a choice, you must capture the least important&nbsp;piece." },
                { elo: 1000, type: "—Forced Move—", title: "Pawn's Revenge!", description: "If your opponent takes a pawn, you must move a pawn on the next turn unless it's not a legal&nbsp;move." },

                { elo: 'Magnus', type: "—Forced Move—", title: "Duck, Duck, Duck, Duck, Goose!", description: "Every fifth move must be a king move." },
                { elo: 1000, type: "—Forced Move—", title: "Rampage!", description: "Every time you capture a piece or pawn, if you can use that piece on your next turn to capture again, you&nbsp;must." },


                // Promotional Rules
                { elo: 250, type: "—Promotional—", title: "The Master Builder", description: "You can only promote to a rook." },
                { elo: 500, type: "—Promotional—", title: "The Stablehand", description: "You can only promote to a knight." },
                { elo: 500, type: "—Promotional—", title: "The Pious", description: "You can only promote to a bishop." },

                { elo: 500, type: "—Promotional—", title: "Nepotism", description: "You can only promote if your king or queen is guarding the promotion&nbsp;square." },
                { elo: 500, type: "—Promotional—", title: "Cronyism", description: "You can only promote if a knight, bishop, or rook is guarding the promotion&nbsp;square." },
                { elo: 500, type: "—Promotional—", title: "Solidarity", description: "You can only promote if another pawn is guarding the promotion&nbsp;square." },
                { elo: 500, type: "—Promotional—", title: "Self-Made Pawn", description: "You can only promote if nothing is guarding the promotion&nbsp;square." },

                { elo: 750, type: "—Promotional—", title: "Bad Boss", description: "You can't promote your pawns.<br><br>Or rather, you refuse to because you're a filthy&nbsp;capitalist." },


                // Clock Rules
                { elo: 250, type: "—Clock Rule—", title: "Underclocked", description: "You can never end your turn with more time than your&nbsp;opponent." },
                // { elo: 1000, type: "—Clock Rule—", title: "Speedrun, Any %", description: "Finish the game with 80% of your time left on the clock for games over 5&nbsp;minutes.<br><br>Otherwise, it's 50% of your&nbsp;time." },
                { elo: 250, type: "—Clock Rule—", title: "Even Steven", description: "If you stop your clock on an odd number, you must waste 10% of your time at the end of your&nbsp;next&nbsp;move." },
                { elo: 250, type: "—Clock Rule—", title: "Odd Todd", description: "If you stop your clock on an even number, you must waste 10% of your time at the end of your&nbsp;next&nbsp;move." },

                { elo: 250, type: "—Clock Rule—", title: "Time Odds", description: "Use 1/5 of your time on your third move.<br><br>Make increasingly loud pondering noises while you&nbsp;wait." },
                { elo: 500, type: "—Clock Rule—", title: "Berzerker", description: "Use 1/2 of your time on your third move.<br><br>Make increasingly loud pondering noises while you&nbsp;wait." },
                { elo: 750, type: "—Clock Rule—", title: "Breath Chess", description: "Hold your breath at the start of every turn. You must move before you run out&nbsp;of&nbsp;breath." },

                { elo: 750, type: "—Clock Rule—", title: "Lagging Queen", description: "<i>Read this rule aloud.</i><br><br>Every time you want to move your queen, you have to announce the move first, then wait before moving it. How long you wait depends on time&nbsp;control:<br><br><ul>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;60-90 minutes: Wait 2 minutes.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;20-60 minutes: Wait 1 minute.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;10-20 minutes: Wait 30 seconds.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;5-10 minutes: Wait 15 seconds.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;3-5 minutes: Wait 10 seconds.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;Under 3 minutes: Wait 5 seconds.</li></ul>" },
                { elo: 750, type: "—Clock Rule—", title: "Lagging Rooks", description: "<i>Read this rule aloud.</i><br><br>Every time you want to move a rook, you have to announce the move first, then wait before moving it. Castling counts as moving your rook. How long you wait depends on time&nbsp;control:<br><br><ul>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;60-90 minutes: Wait 2 minutes.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;20-60 minutes: Wait 1 minute.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;10-20 minutes: Wait 30 seconds.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;5-10 minutes: Wait 15 seconds.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;3-5 minutes: Wait 10 seconds.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;Under 3 minutes: Wait 5 seconds.</li></ul>" },
                { elo: 750, type: "—Clock Rule—", title: "Lagging Bishops", description: "<i>Read this rule aloud.</i><br><br>Every time you want to move a bishop, you have to announce the move first, then wait before moving it. How long you wait depends on time&nbsp;control:<br><br><ul>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;60-90 minutes: Wait 2 minutes.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;20-60 minutes: Wait 1 minute.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;10-20 minutes: Wait 30 seconds.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;5-10 minutes: Wait 15 seconds.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;3-5 minutes: Wait 10 seconds.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;Under 3 minutes: Wait 5 seconds.</li></ul>" },
                { elo: 750, type: "—Clock Rule—", title: "Lagging Knights", description: "<i>Read this rule aloud.</i><br><br>Every time you want to move a knight, you have to announce the move first, then wait before moving it. How long you wait depends on time&nbsp;control:<br><br><ul>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;60-90 minutes: Wait 2 minutes.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;20-60 minutes: Wait 1 minute.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;10-20 minutes: Wait 30 seconds.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;5-10 minutes: Wait 15 seconds.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;3-5 minutes: Wait 10 seconds.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;Under 3 minutes: Wait 5 seconds.</li></ul>" },


                // Opponent Power
                { elo: 500, type: "—Opponent Power—", title: "\"Nuh uh!\"", description: "<i>Read this rule aloud.</i><br><br>After your turn, your opponent can force you find a different move by saying  \"Nuh&nbsp;uh!\"<br><br>This phrase can only be used once." },
                { elo: 750, type: "—Opponent Power—", title: "\"No way, José!\"", description: "<i>Read this rule aloud.</i><br><br>After your turn, your opponent can force you find a different move by saying either  \"No way, José!\" or \"Nuh&nbsp;uh!\"<br><br>Each phrase can only be used once." },
                { elo: 1000, type: "—Opponent Power—", title: "\"I don't think so, Tim.\"", description: "<i>Read this rule aloud.</i><br><br>After your turn, your opponent can force you find a different move by saying either \"I don't think so, Tim\",  \"No way, José!\", or \"Nuh&nbsp;uh!\"<br><br>Each phrase can only be used once." },
                { elo: 750, type: "—Opponent Power—", title: "\"Why don't I just move that for ya?", description: "<i>Read this rule aloud.</i><br><br>Your opponent can take your turn by saying, \"Why don't I just move that for&nbsp;ya?\"<br><br>This phrase can only be used&nbsp;once." },
                { elo: 'Magnus', type: "—Opponent Power—", title: "\"Let me just scootch that over here", description: "<i>Read this rule aloud.</i><br><br>Your opponent can take your turn by saying, \"Let me just scootch that over here,\" or \"Why don't I just move that for&nbsp;ya?\"<br><br>Each phrase can only be used&nbsp;once." },

                { elo: 750, type: "—Opponent Power—", title: "Mouse Slip", description: "<i>Read this rule aloud.</i><br><br>After your turn, your opponent can say \"Mouse slip!\" and move your queen, rook, or bishop one square short or one square&nbsp;past.<br><br>They cannot force an illegal move. This can only be used&nbsp;once." },
                { elo: 500, type: "—Opponent Power—", title: "Not That One", description: "<i>Read this rule aloud.</i><br><br>At any point in the game, your opponent can tell you not to move a piece or pawn and you have to pick a&nbsp;new&nbsp;one.<br><br>This can only be used&nbsp;once." },
                { elo: 750, type: "—Opponent Power—", title: "Not That One, Either", description: "<i>Read this rule aloud.</i><br><br>At any point in the game, your opponent can tell you not to move a piece or pawn and you have to pick a&nbsp;new&nbsp;one.<br><br>This can only be used&nbsp;twice." },
                { elo: 750, type: "—Opponent Power—", title: "This One", description: "<i>Read this rule aloud.</i><br><br>At any point in the game, your opponent can pick what piece or pawn you move as long as it has a legal move&nbsp;to&nbsp;make.<br><br>This can only be used once." },
                { elo: 1000, type: "—Opponent Power—", title: "This One, Too", description: "<i>Read this rule aloud.</i><br><br>At any point in the game, your opponent can pick what piece or pawn you move as long as it has a legal move&nbsp;to&nbsp;make.<br><br>This can only be used twice." },

                { elo: 250, type: "—Opponent Power—", title: "\"Lights Out!\"", description: "<i>Read this rule aloud.</i><br><br>At any point in the game, your opponent can say \"Lights out!\" and you have to play your next turn with your eyes&nbsp;closed.<br><br>This can only be used once." },
                { elo: 500, type: "—Opponent Power—", title: "\"Power's Out!\"", description: "<i>Read this rule aloud.</i><br><br>At any point in the game, your opponent can say \"Power's out!\" and you have to play your next two turns with your eyes&nbsp;closed.<br><br>This can only be used once." },
                { elo: 750, type: "—Opponent Power—", title: "\"Blackout!\"", description: "<i>Read this rule aloud.</i><br><br>At any point in the game, your opponent can say \"Blackout!\" and you have to play your next three turns with your eyes&nbsp;closed.<br><br>This can only be used once." },
                { elo: 750, type: "—Opponent Power—", title: "\"Powerlines Are Down!\"", description: "<i>Read this rule aloud.</i><br><br>At any point in the game, your opponent can say \"Powerlines are down!\" and you have to play your next four turns with your eyes&nbsp;closed.<br><br>This can only be used once." },
                { elo: 'Magnus', type: "—Opponent Power—", title: "The Northeast Blackout of&nbsp;2003", description: "<i>Read this rule aloud.</i><br><br>At any point in the game, your opponent can say \"It's the Northeast Blackout of 2003!\" and you have to play your next five turns with your eyes&nbsp;closed.<br><br>This can only be used once." },

                { elo: 500, type: "—Opponent Power—", title: "Duck Chess", description: "<i>Read this rule aloud.</i><br><br>Your opponent can place an invisible rubber duck on the board after their turn on any unoccupied square. For your next turn, you cannot land a piece or pawn on, nor travel through, this square.<br><br>This can only be used once." },
                { elo: 750, type: "—Opponent Power—", title: "Ducks Chess", description: "<i>Read this rule aloud.</i><br><br>Your opponent can place an invisible rubber duck on the board after their turn on any unoccupied square. For your next turn, you cannot land a piece or pawn on, nor travel through, this square.<br><br>This can only be used twice." },
                { elo: 1000, type: "—Opponent Power—", title: "Waddling Chess", description: "<i>Read this rule aloud.</i><br><br>Your opponent can place an invisible rubber duck on the board after their turn on any unoccupied square. For your next turn, you cannot land a piece or pawn on, nor travel through, this square.<br><br>This can only be used three times." },
                { elo: 'Magnus', type: "—Opponent Power—", title: "Bag Of Bread", description: "<i>Read this rule aloud.</i><br><br>Your opponent can place an invisible rubber duck on the board after their turn on any unoccupied square. For your next turn, you cannot land a piece or pawn on, nor travel through, this square.<br><br>This can be used an unlimited number of times." },


                // Fail Condition
                { elo: 750, type: "—Fail Condition—", title: "V.I.N.s", description: "If you lose both knights, you must&nbsp;resign." },
                { elo: 750, type: "—Fail Condition—", title: "V.I.B.s", description: "If you lose both bishops, you must&nbsp;resign." },
                { elo: 500, type: "—Fail Condition—", title: "V.I.P.s", description: "If you lose all your pawns, you must&nbsp;resign." },
                { elo: 750, type: "—Fail Condition—", title: "V.I.Q.", description: "If you lose your queen, you must&nbsp;resign." },
                { elo: 'Magnus', type: "—Fail Condition—", title: "V.I.P.", description: "If you lose your |ƒ| pawn, you must&nbsp;resign." },
                { elo: 'Magnus', type: "—Fail Condition—", title: "V.I.E.", description: "You must resign if you lose a)&nbsp;both&nbsp;bishops, b)&nbsp;both&nbsp;knights, c)&nbsp;both&nbsp;rooks, or d)&nbsp;your&nbsp;queen." },

                { elo: 750, type: "—Fail Condition—", title: "Achill-e's Square", description: "If your opponent gets a piece or pawn on the |1st| or ~8th~ rank of the |ƒ| file, you&nbsp;must&nbsp;resign." },
                { elo: 'Magnus', type: "—Fail Condition—", title: "Capture The Flag", description: "If your opponent lands a piece or pawn in your back rank, you must&nbsp;resign." },
                { elo: 1000, type: "—Fail Condition—", title: "Check Is Mate", description: "If your opponent puts you in check, you&nbsp;must&nbsp;resign." },


                // Endgame Rule
                { elo: 500, type: "—Endgame Rule—", title: "My Little Ponies", description: "You can't mate unless you have three knights on the&nbsp;board." },
                { elo: 750, type: "—Endgame Rule—", title: "Animal Husbandry", description: "You can't mate unless you have four knights on the&nbsp;board." },
                { elo: 500, type: "—Endgame Rule—", title: "Seminary", description: "You can't mate unless you have three bishops on the&nbsp;board." },
                { elo: 750, type: "—Endgame Rule—", title: "The Crusades", description: "You can't mate unless you have four bishops on the&nbsp;board." },

                { elo: 750, type: "—Endgame Rule—", title: "Squeezed By The&nbsp;Juicer", description: "You must get checkmate with a bishop&nbsp;move." },
                { elo: 750, type: "—Endgame Rule—", title: "Drawn and Quartered", description: "You must get checkmate with a knight&nbsp;move." },
                { elo: 750, type: "—Endgame Rule—", title: "Subjects Only", description: "You can't use a queen to mate." },
                // { elo: 'Magnus', type: "—Endgame Rule—", title: "Checking Is Winning", description: "You can't mate. You can only win by perpetual&nbsp;check." },


                // Dungeons & Diagonals
                { elo: 250, type: "—Dungeons & Diagonals—", title: "Roll For Opening", description: "<i>Read this rule aloud.</i><br><br>You must announce when you want to move a pawn, then roll a d8 to determine which pawn it will be. If you can't move that pawn, roll again.<br><br>If you need a d8, click <a href=https://rolladie.net/roll-a-d8-die>here</a>.<br>Lasts until turn 6." },
                { elo: 500, type: "—Dungeons & Diagonals—", title: "Roll For Opening", description: "<i>Read this rule aloud.</i><br><br>You must announce when you want to move a pawn, then roll a d8 to determine which pawn it will be. If you can't move that pawn, roll again.<br><br>If you need a d8, click <a href=https://rolladie.net/roll-a-d8-die>here</a>.<br>Lasts until turn 10." },
                { elo: 750, type: "—Dungeons & Diagonals—", title: "Roll For Opening", description: "<i>Read this rule aloud.</i><br><br>You must announce when you want to move a pawn, then roll a d8 to determine which pawn it will be. If you can't move that pawn, roll again.<br><br>If you need a d8, click <a href=https://rolladie.net/roll-a-d8-die>here</a>.<br>Lasts until turn 13." },
                { elo: 1000, type: "—Dungeons & Diagonals—", title: "Roll For Opening", description: "<i>Read this rule aloud.</i><br><br>You must announce when you want to move a pawn, then roll a d8 to determine which pawn it will be. If you can't move that pawn, roll again.<br><br>If you need a d8, click <a href=https://rolladie.net/roll-a-d8-die>here</a>.<br>Lasts until turn 16." },
                { elo: 'Magnus', type: "—Dungeons & Diagonals—", title: "Roll For Opening", description: "<i>Read this rule aloud.</i><br><br>You must announce when you want to move a pawn, then roll a d8 to determine which pawn it will be. If you can't move that pawn, roll again.<br><br>If you need a d8, click <a href=https://rolladie.net/roll-a-d8-die>here</a>.<br>Lasts the whole game." },

                { elo: 250, type: "—Dungeons & Diagonals—", title: "Roll To Attack", description: "<i>Read this rule aloud.</i><br><br>You must announce when you want to capture a piece, then roll a d20 to determine if your attack is&nbsp;successful.<br><br><ul>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 10 through 19, you capture the&nbsp;piece.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 2 through 9, the attack misses and you must make a different move. If it's another capture, roll&nbsp;again.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 1, the attack misses and you blunder instead, either by moving the attacking piece to a square where it can be captured or, if that's not an option, by making the worst move you can&nbsp;find.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 20, the attack is successful and you must describe the gruesome details of how the piece is&nbsp;captured.</li></ul><br>If you need a d20, click <a href=https://rolladie.net/roll-a-d20-die>here</a>.<br>Expires after one capture." },
                { elo: 500, type: "—Dungeons & Diagonals—", title: "Roll To Attack", description: "<i>Read this rule aloud.</i><br><br>You must announce when you want to capture a piece, then roll a d20 to determine if your attack is&nbsp;successful.<br><br><ul>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 10 through 19, you capture the&nbsp;piece.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 2 through 9, the attack misses and you must make a different move. If it's another capture, roll&nbsp;again.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 1, the attack misses and you blunder instead, either by moving the attacking piece to a square where it can be captured or, if that's not an option, by making the worst move you can&nbsp;find.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 20, the attack is successful and you must describe the gruesome details of how the piece is&nbsp;captured.</li></ul><br>If you need a d20, click <a href=https://rolladie.net/roll-a-d20-die>here</a>.<br>Expires after two captures." },
                { elo: 750, type: "—Dungeons & Diagonals—", title: "Roll To Attack", description: "<i>Read this rule aloud.</i><br><br>You must announce when you want to capture a piece, then roll a d20 to determine if your attack is&nbsp;successful.<br><br><ul>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 10 through 19, you capture the&nbsp;piece.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 2 through 9, the attack misses and you must make a different move. If it's another capture, roll&nbsp;again.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 1, the attack misses and you blunder instead, either by moving the attacking piece to a square where it can be captured or, if that's not an option, by making the worst move you can&nbsp;find.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 20, the attack is successful and you must describe the gruesome details of how the piece is&nbsp;captured.</li></ul><br>If you need a d20, click <a href=https://rolladie.net/roll-a-d20-die>here</a>.<br>Expires after three captures." },
                { elo: 1000, type: "—Dungeons & Diagonals—", title: "Roll To Attack", description: "<i>Read this rule aloud.</i><br><br>You must announce when you want to capture a piece, then roll a d20 to determine if your attack is&nbsp;successful.<br><br><ul>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 10 through 19, you capture the&nbsp;piece.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 2 through 9, the attack misses and you must make a different move. If it's another capture, roll&nbsp;again.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 1, the attack misses and you blunder instead, either by moving the attacking piece to a square where it can be captured or, if that's not an option, by making the worst move you can&nbsp;find.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 20, the attack is successful and you must describe the gruesome details of how the piece is&nbsp;captured.</li></ul><br>If you need a d20, click <a href=https://rolladie.net/roll-a-d20-die>here</a>.<br>Expires after four captures." },
                { elo: 'Magnus', type: "—Dungeons & Diagonals—", title: "Roll To Attack", description: "<i>Read this rule aloud.</i><br><br>Each time you want to capture a piece, you must announce your intended move, then roll a d20 to determine if your attack is&nbsp;successful.<br><br><ul>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 10 through 19, you capture the&nbsp;piece.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 2 through 9, the attack misses and you must make a different move. If it's another capture, roll&nbsp;again.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 1, the attack misses and you blunder instead, either by moving the attacking piece to a square where it can be captured or, if that's not an option, by making the worst move you can&nbsp;find.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 20, the attack is successful and you must describe the gruesome details of how the piece is&nbsp;captured.</li></ul><br>If you need a d20, click <a href=https://rolladie.net/roll-a-d20-die>here</a>." },

                { elo: 250, type: "—Dungeons & Diagonals—", title: "Saving Throw", description: "<i>Read this rule aloud.</i><br><br>When you are put in check, you must announce your intended move and then roll a d20 to determine if it is&nbsp;successful.<br><br><ul>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 10 through 19, you defend&nbsp;successfully.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 2 through 9, choose a new move. You don't have to roll&nbsp;again.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 1, choose a new move and roll&nbsp;again.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 20, you defend successfully and must describe in detail how it is carried&nbsp;out.</li></ul><br>If you need a d20, click <a href=https://rolladie.net/roll-a-d20-die>here</a>.<br>Expires after one use." },
                { elo: 500, type: "—Dungeons & Diagonals—", title: "Saving Throw", description: "<i>Read this rule aloud.</i><br><br>When you are put in check, you must announce your intended move and then roll a d20 to determine if it is&nbsp;successful.<br><br><ul>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 10 through 19, you defend&nbsp;successfully.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 2 through 9, choose a new move. You don't have to roll&nbsp;again.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 1, choose a new move and roll&nbsp;again.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 20, you defend successfully and must describe in detail how it is carried&nbsp;out.</li></ul><br>If you need a d20, click <a href=https://rolladie.net/roll-a-d20-die>here</a>.<br>Expires after two uses." },
                { elo: 750, type: "—Dungeons & Diagonals—", title: "Saving Throw", description: "<i>Read this rule aloud.</i><br><br>When you are put in check, you must announce your intended move and then roll a d20 to determine if it is&nbsp;successful.<br><br><ul>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 10 through 19, you defend&nbsp;successfully.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 2 through 9, choose a new move. You don't have to roll&nbsp;again.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 1, choose a new move and roll&nbsp;again.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 20, you defend successfully and must describe in detail how it is carried&nbsp;out.</li></ul><br>If you need a d20, click <a href=https://rolladie.net/roll-a-d20-die>here</a>.<br>Expires after three uses." },
                { elo: 1000, type: "—Dungeons & Diagonals—", title: "Saving Throw", description: "<i>Read this rule aloud.</i><br><br>When you are put in check, you must announce your intended move and then roll a d20 to determine if it is&nbsp;successful.<br><br><ul>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 10 through 19, you defend&nbsp;successfully.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 2 through 9, choose a new move. You don't have to roll&nbsp;again.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 1, choose a new move and roll&nbsp;again.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 20, you defend successfully and must describe in detail how it is carried&nbsp;out.</li></ul><br>If you need a d20, click <a href=https://rolladie.net/roll-a-d20-die>here</a>.<br>Expires after four uses." },
                { elo: 'Magnus', type: "—Dungeons & Diagonals—", title: "Saving Throw", description: "<i>Read this rule aloud.</i><br><br>Each time you are put in check, you must announce your intended move and then roll a d20 to determine if it is&nbsp;successful.<br><br><ul>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 10 through 19, you defend&nbsp;successfully.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 2 through 9, choose a new move. You don't have to roll&nbsp;again.</li>" +
                "<li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 1, choose a new move and roll&nbsp;again.</li>" +
                "<li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;If you roll a 20, you defend successfully and must describe in detail how it is carried&nbsp;out.</li></ul><br>If you need a d20, click <a href=https://rolladie.net/roll-a-d20-die>here</a>." },


                // Unlockable
                { elo: 750, type: "—Unlockable—", title: "Endgame Hero", description: "You can't move your queen until you're down to 10% of your original starting&nbsp;time." },
                // { elo: 500, type: "—Unlockable—", title: "New Challenger Approaching!", description: "You can't move your queen until&nbsp;turn&nbsp;15." },
                { elo: 'Magnus', type: "—Unlockable—", title: "Crank", description: "<i>Read this rule aloud.</i><br><br>You only have 5 turns. For each capture you make, you get 3&nbsp;more&nbsp;turns.<br><br>If you run out of turns, your heart&nbsp;stops.<br><br>I mean, you lose." },

                // { elo: 250, type: "—Unlockable—", title: "I Slept In", description: "Your attacking piece on the |ƒ| file can't move until turn 10. The pawn ahead of it can still&nbsp;move." },
                // { elo: 500, type: "—Unlockable—", title: "I Missed The Bus", description: "Your attacking piece on the |ƒ| file can't move until turn 15. The pawn ahead of it can still&nbsp;move." },
                // { elo: 750, type: "—Unlockable—", title: "My Car Broke Down", description: "Your attacking piece on the |ƒ| file can't move until turn 20. The pawn ahead of it can still&nbsp;move." },

                // Sacrifices
                { elo: 500, type: "—Sacrifice—", title: "Oh No, My Knight!", description: "Sac your knight for a pawn before turn&nbsp;10." },
                { elo: 1000, type: "—Sacrifice—", title: "Oh No, My Knights!", description: "Sac both knights for a pawn before turn&nbsp;15." },
                { elo: 500, type: "—Sacrifice—", title: "Oh No, My Bishop!", description: "Sac your bishop for a pawn before turn&nbsp;10." },
                { elo: 1000, type: "—Sacrifice—", title: "Oh No, My Bishops!", description: "Sac both bishops for pawns before turn&nbsp;15." },
                { elo: 'Magnus', type: "—Sacrifice—", title: "Oh No, My Everything!", description: "Sac a knight and a bishop for pawns, a rook for a knight or bishop, and a queen for a knight, bishop, or&nbsp;rook." },
                { elo: 250, type: "—Sacrifice—", title: "The ROOOOOK!", description: "Sac your rook for a bishop, knight, or pawn before turn&nbsp;20." },
                { elo: 750, type: "—Sacrifice—", title: "The ROOOOOKS!!", description: "Sac both rooks for bishops, knights, or pawns before turn&nbsp;30." },
                { elo: 750, type: "—Sacrifice—", title: "Oh No, My Queen!", description: "Sac your queen for a knight, bishop, or rook before turn&nbsp;10." },
                { elo: 1000, type: "—Sacrifice—", title: "Oh F***, My Queen!", description: "Sac your queen for a pawn before turn&nbsp;10." },
                { elo: 1000, type: "—Sacrifice—", title: "Oh No, My Speedrun!", description: "Sac your queen on turn 3." },
                { elo: 1000, type: "—Sacrifice—", title: "Oh No, My Queens!", description: "Sac your queen for a rook, bishop, or knight before turn 10. Then promote to a queen and sac that,&nbsp;too." },

                { elo: 1000, type: "—Sacrifice—", title: "Botez Gambit", description: "Hang your queen until it's captured, then get really mad about&nbsp;it." },
                { elo: 'Magnus', type: "—Sacrifice—", title: "Double Botez Gambit", description: "Hang your queen until it's captured. Then promote to a queen and hang that one,&nbsp;too." },
                { elo: 1000, type: "—Sacrifice—", title: "Pawn-Seeking Missiles", description: "Take out 3 pawns with knight, bishop, and rook&nbsp;sacrifices." },
                { elo: 'Magnus', type: "—Sacrifice—", title: "Somebody Call An Ambulance (For&nbsp;Me)", description: "Take out 4 pawns with knight, bishop, and rook&nbsp;sacrifices." },


                // Arrested Development
                { elo: 250, type: "—Arrested Development—", title: "\"It's one pawn Michael,<br>what could it cost? $10?\"", description: "You can't develop any attacking pieces past the |3rd| / ~6th~ rank unless you have one less pawn than your&nbsp;opponent." },
                { elo: 500, type: "—Arrested Development—", title: "\"Say goodbye to <i>these!</i>\"", description: "You can't develop any attacking pieces past the |3rd| / ~6th~ rank unless you have two less pawns than your&nbsp;opponent." },
                { elo: 750, type: "—Arrested Development—", title: "\"I've made a huge mistake\"", description: "You can't develop any attacking pieces past the |3rd| / ~6th~ rank until you've lost four&nbsp;pawns." },
                { elo: 1000, type: "—Arrested Development—", title: "\"Oh my god, we're having a&nbsp;fire...&nbsp;sale!\"", description: "You can't develop any attacking pieces past the |3rd| / ~6th~ rank until you've lost six&nbsp;pawns." },
                { elo: 'Magnus', type: "—Arrested Development—", title: "\"I may have committed some light treason\"", description: "You can't develop any attacking pieces past the |3rd| / ~6th~ rank until you've lost all eight&nbsp;pawns." },

                { elo: 750, type: "—Arrested Development—", title: "Operation Hot Mother", description: "You can't develop any other pieces until you've sent a knight into your opponent's half and then back to its starting square. Or until it&nbsp;dies." },

                { elo: 250, type: "—Arrested Development—", title: "\"No touching!\"", description: "You can't move any chess pieces onto your opponent's side until they have a piece on your&nbsp;side." },
                { elo: 250, type: "—Arrested Development—", title: "\"Well excuuuuuuse me.\"", description: "You can't move any chess pieces onto your opponent's side until you've been put&nbsp;in&nbsp;check." },
                { elo: 500, type: "—Arrested Development—", title: "\"Her?\"", description: "You can't move any chess pieces onto your opponent's side until you've lost your queen." },

                { elo: 1000, type: "—Arrested Development—", title: "\"Take a look at banner, Michael!\"", description: "Start with |Na3| / ~Na6~, then rally the troops by parading your knight across the board. You can't develop any of your pieces until either your knight reaches the |h| file, or&nbsp;is&nbsp;captured." },
                { elo: 500, type: "—Arrested Development—", title: "\"The fact that you call it that means you're not ready.\"", description: "You can't develop any attacking pieces past the |2rd| / ~7th~ rank until after you've castled or lost castling&nbsp;rights." },

                // Baby, you got a stew going.
                // Steve Holt!
                // There are dozens of us. Dozens!
                // And that's why you always leave a note.
                // I'm afraid I just blew myself.
                // There's always money in the banana stand.
                // Oh Tobias, you blowhard.
                // You can always tell a Milford man.
                // Ooh look at all these parts!
                // It's an illusion, Michael.
                // Wow, we are just blowing through nap time.
                // Heeeey, brother.
                // Mr. Manager.
                // You are now punished. I punish thee.
                // Marry me.
                // There's no I in Teamocil, at least not where you'd think.
                // Your son is going to be all right.
                // You must teach me the ways of the secular flesh.
                // We're kids, we're supposed to work.
                // You can always tell a Milford man.
                // A darkish area, with points.
                // Would a coward have THIS?
                // Dr. Funke's 100% Natural Good Time Family Band Solution.
                // If this scene I recreate, perhaps I can resnare my mate.

                // Quest
                { elo: 500, type: "—Quest—", title: "Pawn Eater", description: "You must capture all your opponent's&nbsp;pawns." },
                { elo: 1000, type: "—Quest—", title: "The Preakness", description: "Get a knight to the |8th| / ~1st~ rank before the&nbsp;<div class='tooltip'>endgame<span class='tooltiptext'>Approx. when the middlegame is&nbsp;over.</span></div>." },
                { elo: 'Magnus', type: "—Quest—", title: "The Belmont Stakes", description: "Get a knight to the |8th| / ~1st~ rank and then back again before the&nbsp;<div class='tooltip'>endgame<span class='tooltiptext'>Loosely defined as when your king wants to come out and&nbsp;play.</span></div>" },
                { elo: 250, type: "—Quest—", title: "Sniper!", description: "Put a bishop in the corner of the board by turn&nbsp;12." },
                { elo: 500, type: "—Quest—", title: "Nerf a Knight", description: "Put a knight in your corner of the board by turn&nbsp;15." },

                { elo: 500, type: "—Quest—", title: "DIY", description: "Castle by hand, getting your king to the left or right of a rook on the |1st| / ~8th~ rank before the&nbsp;<div class='tooltip'>endgame<span class='tooltiptext'>About the time when your king gets hungry for&nbsp;pawns.</span></div>" },
                { elo: 'Magnus', type: "—Quest—", title: "I'm Sorry Mario, But Your King Is In Another&nbsp;Castle", description: "Castle to one side, then re-castle your king to the other side by hand. Must be done before the&nbsp;<div class='tooltip'>endgame<span class='tooltiptext'>Considered by Speelman to begin when each player has thirteen or fewer points of&nbsp;material.</span></div>" },

                { elo: 750, type: "—Quest—", title: "Queenside Stan", description: "You must always have an equal number or more of your chess pieces on the |a| through |d| files at the end of your&nbsp;turn." },
                { elo: 750, type: "—Quest—", title: "Kingside Stan", description: "You must always have an equal number or more of your chess pieces on the |e| through |h| files at the end of your&nbsp;turn." },

                { elo: 500, type: "—Quest—", title: "Contrarian", description: "Castle to the opposite side of your opponent. If your opponent doesn't castle, you&nbsp;can't&nbsp;either.<br><br>If you lose castling rights, you must castle&nbsp;by&nbsp;hand." },
                { elo: 750, type: "—Quest—", title: "Middleman", description: "Occupy 3 of the 4 centre squares before the&nbsp;<div class='tooltip'>endgame<span class='tooltiptext'>Per Minev, when there are four or fewer pieces other than kings and&nbsp;pawns.</span></div>." },
                { elo: 1000, type: "—Quest—", title: "King of the Middle", description: "Occupy 4 of the 4 centre squares before the&nbsp;<div class='tooltip'>endgame<span class='tooltiptext'>Defined as the exact moment when kings stop sleeping and wake up like that Squidward meme.</span></div>." },

                { elo: 750, type: "—Quest—", title: "Just Visiting", description: "Get your queen to |ƒ®(4-5)| by move 15. Once there, your queen can't move for 3&nbsp;turns." },
                { elo: 1000, type: "—Quest—", title: "Moving In", description: "Get your queen to |ƒ®(4-5)| by move 15. Once there, your queen can't move for 5&nbsp;turns." },
                { elo: 'Magnus', type: "—Quest—", title: "Squatter", description: "Get your queen to |ƒ®(4-5)| by move 15. Once there, your queen can't move for 7&nbsp;turns." },

                { elo: 500, type: "—Quest—", title: "Not So Fast!", description: "Prevent your opponent from castling." },
                { elo: 500, type: "—Quest—", title: "Invasion", description: "Get 5 attacking pieces on your opponent's side of the&nbsp;board." },
                { elo: 'Magnus', type: "—Quest—", title: "Chess 960-y", description: "Rearrange your pieces so that your |1st| / ~8th~ rank is full, but not the same as when you&nbsp;started." },

                { elo: 750, type: "—Quest—", title: "Shared Space", description: "Get at least 4 different chess pieces to land on&nbsp;|ƒ®(3-6)|." },
                { elo: 750, type: "—Quest—", title: "Town Square", description: "Get a knight, bishop, and rook to land on |ƒ®(3-6)|." },

                { elo: 500, type: "—Quest—", title: "Sub", description: "Create a vertical or horizontal chain of 2 pieces before turn 10. It must be worth at least 4 points of material. Once you've \"placed\" your ship, you can no longer move any of the pieces&nbsp;in&nbsp;it.<br><br>If your opponent captures every piece in your \"ship,\" you must say, \"You&nbsp;sunk&nbsp;my&nbsp;Sub!\"" },
                { elo: 750, type: "—Quest—", title: "Cruiser", description: "Create a vertical or horizontal chain of 3 pieces before turn 10. It must be worth at least 6 points of material. Once you've \"placed\" your ship, you can no longer move any of the pieces&nbsp;in&nbsp;it.<br><br>If your opponent captures every piece in your \"ship,\" you must say, \"You&nbsp;sunk&nbsp;my&nbsp;Cruiser!\"" },
                { elo: 1000, type: "—Quest—", title: "Battleship", description: "Create a vertical or horizontal chain of 4 pieces before turn 10. It must be worth at least 7 points of material. Once you've \"placed\" your ship, you can no longer move any of the pieces&nbsp;in&nbsp;it.<br><br>If your opponent captures every piece in your \"ship,\" you must say, \"You&nbsp;sunk&nbsp;my&nbsp;Battleship!\"" },
                { elo: 'Magnus', type: "—Quest—", title: "Carrier", description: "Create a vertical or horizontal chain of 5 pieces before turn 10. It must be worth at least 9 points of material. Once you've \"placed\" your ship, you can no longer move any of the pieces&nbsp;in&nbsp;it.<br><br>If your opponent captures every piece in your \"ship,\" you must say, \"You&nbsp;sunk&nbsp;my&nbsp;Carrier!\"" },

                { elo: 250, type: "—Quest—", title: "Pawn Lead", description: "Have two pawns more than your opponent at some point in the&nbsp;game." },
                { elo: 500, type: "—Quest—", title: "Pawn Advantage", description: "Have three pawns more than your opponent at some point in the&nbsp;game." },
                { elo: 750, type: "—Quest—", title: "Pawn Superiority", description: "Have four pawns more than your opponent at some point in the&nbsp;game." },
                { elo: 1000, type: "—Quest—", title: "Pawn Supremacy", description: "Have five pawns more than your opponent at some point in the&nbsp;game." },
                { elo: 'Magnus', type: "—Quest—", title: "Pawn Domination", description: "Have six pawns more than your opponent at some point in the&nbsp;game." },

                { elo: 750, type: "—Quest—", title: "Pawn Camper", description: "Get 3 attacking pieces on the |7th| / ~2nd~ rank.</i>" },

                { elo: 500, type: "—Quest—", title: "Martin For A Moment", description: "<i>Read this rule aoud.</i><br><br>Open Chess.com and start a game against the bot Martin. Make him your colour and then let Martin either |begin the game| or ~respond to your opponent's moves~ for&nbsp;5&nbsp;turns.<br><br>After his 5 turns are up, you take&nbsp;over." },
                { elo: 750, type: "—Quest—", title: "Martin For A Minute", description: "<i>Read this rule aloud.</i><br><br>Open Chess.com and start a game against the bot Martin. Make him your colour, then let Martin either |begin the game| or ~respond to your opponent's moves~ for&nbsp;8&nbsp;turns.<br><br>After his 8 turns are up, you take&nbsp;over." },
                { elo: 1000, type: "—Quest—", title: "I Am Become Martin, Destroyer&nbsp;Of&nbsp;Chances", description: "<i>Read this rule aloud.</i><br><br>Open Chess.com and start a game against the bot Martin. Make him your colour, then let Martin either |begin the game| or ~respond to your opponent's moves~ for&nbsp;12&nbsp;turns.<br><br>After his 12 turns are up, you take&nbsp;over." },

                // { elo: 500, type: "—Quest—", title: "King Bolt", description: "Move your king 2 times in a row by turn&nbsp;8." },
                // { elo: 750, type: "—Quest—", title: "King van Niekerk", description: "Move your king 3 times in a row by turn&nbsp;11." },
                // { elo: 1000, type: "—Quest—", title: "King Kiptum", description: "Move your king 4 times in a row by turn&nbsp;15." },
                // { elo: 'Magnus', type: "—Quest—", title: "King Sorokin", description: "Move your king 5 times in a row by turn&nbsp;15." },

                // { elo: 500, type: "—Quest—", title: "Queen Griffith-Joyner", description: "Move your queen 3 times in a row by turn&nbsp;7." },
                // { elo: 750, type: "—Quest—", title: "Queen Koch", description: "Move your queen 4 times in a row by turn&nbsp;9." },
                // { elo: 1000, type: "—Quest—", title: "Queen Assefa", description: "Move your queen 5 times in a row by turn&nbsp;12." },
                // { elo: 'Magnus', type: "—Quest—", title: "Queen Herron", description: "Move your queen 6 times in a row by turn&nbsp;15." },

                { elo: 500, type: "—Quest—", title: "Tower", description: "Stack four connected chess pieces on the |ƒ| file before the&nbsp;<div class='tooltip'>endgame<span class='tooltiptext'>Everyone has a different definition. Why don't you make one&nbsp;up?</span></div>." },
                { elo: 750, type: "—Quest—", title: "Church Spire", description: "Stack four connected chess pieces on the |ƒ| file before the <div class='tooltip'>endgame<span class='tooltiptext'>When most of the attacking pieces are off the&nbsp;board.</span></div>. The piece on top must be a&nbsp;bishop." },
                { elo: 750, type: "—Quest—", title: "Roach?", description: "Stack four connected chess pieces on the |ƒ| file before the <div class='tooltip'>endgame<span class='tooltiptext'>When players prioritize pushing past&nbsp;pawns.</span></div>. The piece on top must be a&nbsp;knight." },
                { elo: 750, type: "—Quest—", title: "Turret", description: "Stack four connected chess pieces on the |ƒ| file before the <div class='tooltip'>endgame<span class='tooltiptext'>When both players are eager to activate their&nbsp;kings.</span></div>. The piece on top must be a&nbsp;rook." },
                { elo: 1000, type: "—Quest—", title: "Rapunzel", description: "Stack five connected chess pieces on the |ƒ| file before the <div class='tooltip'>endgame<span class='tooltiptext'>When your king is drawn to the centre like a moth to the&nbsp;flame.</span></div>. The piece on top must be a&nbsp;queen." },
                { elo: 'Magnus', type: "—Quest—", title: "Crown Jewel", description: "Stack five connected chess pieces on the |ƒ| file before the <div class='tooltip'>endgame<span class='tooltiptext'>Roughly when both players have 1/4 as many attacking pieces as when they&nbsp;started.</span></div>. The piece on top must be your&nbsp;king." },

                { elo: 750, type: "—Quest—", title: "Police Lineup", description: "Get 5 different chess pieces side-by-side on the |4th| / ~5th~ rank before turn&nbsp;20." },
                { elo: 500, type: "—Quest—", title: "Trench Advance", description: "Occupy the entire |3rd| / ~6th~ rank." },
                { elo: 750, type: "—Quest—", title: "Neutral Zone Trench", description: "Occupy the entire |4th| / ~5th~ rank." },
                { elo: 1000, type: "—Quest—", title: "Forward Trench", description: "Occupy the entire |5th| / ~4th~ rank." },
                { elo: 'Magnus', type: "—Quest—", title: "Infiltration Trench", description: "Occupy the entire |6th| / ~3rd~ rank." },

                { elo: 500, type: "—Quest—", title: "Home Square", description: "Make a square of chess pieces somewhere on the |3rd and 4th| / ~5th and 6th~&nbsp;ranks." },
                { elo: 750, type: "—Quest—", title: "Central Square", description: "Make a square of chess pieces somewhere on the |4th and 5th|&nbsp;ranks." },
                { elo: 1000, type: "—Quest—", title: "Square Over There", description: "Make a square of chess pieces somewhere on the |5th and 6th| / ~3rd and 4th~&nbsp;ranks." },

                { elo: 750, type: "—Quest—", title: "Diagonal Dash", description: "Move a bishop from one corner to the other before turn&nbsp;30." },
                { elo: 500, type: "—Quest—", title: "Full Send", description: "Move a rook from one end of the board to the other before turn&nbsp;30." },


                // Pawn Quests
                { elo: 1000, type: "—Pawn Quest—", title: "Pawn Attack", description: "Get check with a pawn." },

                { elo: 250, type: "—Pawn Quest—", title: "Pawn Walk", description: "Get a pawn to the |6th| / ~3rd~ rank by move 30." },
                { elo: 500, type: "—Pawn Quest—", title: "Pawn Jog", description: "Get a pawn to the |6th| / ~3rd~ rank by move 25." },
                { elo: 750, type: "—Pawn Quest—", title: "Pawn Race", description: "Get a pawn to the |6th| / ~3rd~ rank by move 20." },
                { elo: 1000, type: "—Pawn Quest—", title: "Pawn Sprint", description: "Get a pawn to the |6th| / ~3rd~ rank by move 15." },

                // { elo: 500, type: "—Pawn Quest—", title: "Shaggy and Scooby", description: "Get two connected pawns to the |5th|&nbsp;/&nbsp;~4th~&nbsp;rank." },
                // { elo: 750, type: "—Pawn Quest—", title: "Thelma and Louise", description: "Get two connected pawns to the |6th|&nbsp;/&nbsp;~3rd~&nbsp;rank." },
                // { elo: 750, type: "—Pawn Quest—", title: "Sam and Frodo", description: "Get two connected pawns to the |7th|&nbsp;/&nbsp;~2nd~&nbsp;rank." },
                // { elo: 1000, type: "—Pawn Quest—", title: "The Three Amigos", description: "Get three connected pawns to the |7th|&nbsp;/&nbsp;~2nd~&nbsp;rank." },


                // Scoresheet Quest
                { elo: 750, type: "—Scoresheet Quest—", title: "Cess", description: "You can't move your |h| pawn or land any chess piece on the |h|&nbsp;file." },
                { elo: 750, type: "—Scoresheet Quest—", title: "Chss", description: "You can't move your |e| pawn or land any chess piece on the |e|&nbsp;file." },
                { elo: 750, type: "—Scoresheet Quest—", title: "hess", description: "You can't move your |c| pawn or land any chess piece on the |c|&nbsp;file." },
                { elo: 1000, type: "—Scoresheet Quest—", title: "css", description: "You can't move your |h| or |e| pawn, or land any chess piece on the |h| or |e|&nbsp;files." },
                { elo: 1000, type: "—Scoresheet Quest—", title: "hss", description: "You can't move your |c| or |e| pawn, or land any chess piece on the |c| or |e|&nbsp;files." },
                { elo: 1000, type: "—Scoresheet Quest—", title: "ess", description: "You can't move your |c| or |h| pawn, or land any chess piece on the |c| or |h|&nbsp;files." },
                { elo: 'Magnus', type: "—Scoresheet Quest—", title: "ss", description: "You can't move your |c|, |h|, or |e| pawn, or land any chess piece on the |c|, |h|, or |e|&nbsp;files." },

                { elo: 250, type: "—Scoresheet Quest—", title: "Target Practice", description: "Get |Qƒ®(2-7)| on your scoresheet within the first 30 moves. Captures count,&nbsp;too." },
                { elo: 500, type: "—Scoresheet Quest—", title: "Firing Range", description: "Get |Qƒ®(2-4)| and |Qƒ®(5-7)| on your scoresheet within the first 20 moves. Captures count,&nbsp;too." },
                { elo: 750, type: "—Scoresheet Quest—", title: "Skeet Shooting", description: "Get |Qƒ(1-3)®(2-7)|, |Qƒ(4-5)®(2-7)|, and |Qƒ(6-8)®(2-7)| on your scoresheet within the first 25 moves. Captures count,&nbsp;too." },
                { elo: 1000, type: "—Scoresheet Quest—", title: "Duck Hunting", description: "Get |Qƒ(1-4)®(2-4)|, |Qƒ(1-4)®(5-7)|, |Qƒ(5-8)®(2-4)|, and |Qƒ(5-8)®(5-7)| on your scoresheet within the first 30 moves. Captures count,&nbsp;too." },
                { elo: 'Magnus', type: "—Scoresheet Quest—", title: "Womprat Bullseying", description: "Get |Qƒ(1-3)®(2-4)|, |Qƒ(1-3)®(5-7)|, |Qƒ(4-5)®(2-7)|, |Qƒ(6-8)®(2-4)|, and |Qƒ(6-8)®(5-7)| on your scoresheet within the first 35 moves. Captures count,&nbsp;too." },

                { elo: 'Magnus', type: "—Scoresheet Quest—", title: "\"Thank you for coming to my&nbsp;Ned&nbsp;Talk\"", description: "Get \"Ned\" on your scoresheet.<br><br>Here, let me help:<br>|e3, Ne2, Na3, c3, Nc2, Ned4|<br>or ~e6, Ne7, Na6, c6, Nc7, Ned5~." },
                { elo: 500, type: "—Scoresheet Quest—", title: "The Rad One Radiates", description: "Get |Rad1| or ~Rad8~ on your scoresheet.<br><br><font size=-2>Yeah, that would be hella rad.</font>" },


                // Opening Quest
                { elo: 500, type: "—Opening Quest—", title: "Out Of Book", description: "Create a four-move opening that you think has never been played before. Then name&nbsp;that&nbsp;opening." },

                { elo: 250, type: "—Opening Quest—", title: "Double Diagonals", description: "Fianchetto both bishops to |b2 and g2| / ~b7 and g7~ by turn&nbsp;7." },

                { elo: 750, type: "—Opening Quest—", title: "Negative Nancy", description: "You must be down <i>at least</i> a pawn by move 5, and keep a minimum 1 point material deficit for the rest of&nbsp;the&nbsp;game." },
                { elo: 1000, type: "—Opening Quest—", title: "In The Red", description: "You must sacrifice <i>at least</i> a knight or bishop by move 5, and keep a minimum 2 point material deficit for the rest of&nbsp;the&nbsp;game." },
                { elo: 'Magnus', type: "—Opening Quest—", title: "Underwater", description: "Sacrifice <i>at least</i> two minor pieces by move 8, and keep a minimum 4 point material deficit for the rest of&nbsp;the&nbsp;game." },

                { elo: 500, type: "—Opening Quest—", title: "Mirror Mirror, On&nbsp;The&nbsp;Board", description: "Mimic your opponent's moves. If they ask if you're mimicking them, mimic what they say,&nbsp;too.<br><br>If you're white, start with |a3|.<br><br>Lasts until you can't legally mimic their move." },
                { elo: 500, type: "—Opening Quest—", title: "Same Same, But Different", description: "Whatever piece your opponent moves, you have to move the same kind of piece as&nbsp;well.<br><br>If you're white, start with |a3|.<br><br>Lasts until you can't legally move the piece they move." },

                { elo: 250, type: "—Opening Quest—", title: "Pawn Storm", description: "Open with four pawn moves in your first 5&nbsp;turns." },
                { elo: 500, type: "—Opening Quest—", title: "Pawn Monsoon", description: "Open with six pawn moves in your first 8&nbsp;turns." },
                { elo: 750, type: "—Opening Quest—", title: "Pawn Hurricane", description: "Open with eight pawn moves in your first 11&nbsp;turns." },
                { elo: 1000, type: "—Opening Quest—", title: "Pawn Tsunami", description: "Open with ten pawn moves in your first 13&nbsp;turns." },

                { elo: 1000, type: "—Opening Quest—", title: "Roll Call!", description: "Open the game with |a3| / ~a6~ while saying, \"Give me an a!\" From then on, you can only move your pawns in order from |b| through |h| while cheering, \"Give me a b!\", \"Give me an c!\" and&nbsp;so&nbsp;on.<br><br>If a pawn is lost before you get to |h|, skip it and continue in a sad&nbsp;voice.<br><br>When finished, cheer (or sadly cheer),<br>\"What does that spell? Ab-si-def-guh!\"" },
                { elo: 500, type: "—Opening Quest—", title: "Eroooooy Jenkinsss!", description: "Shout, \"Eroooooooooy Jeeeenkinssssss!\" at your opponent, and then push your |e| pawn as far as it'll&nbsp;go.<br><br>As the game progresses, you must immediately play any legal move that pushes Eroy&nbsp;forward." },

                { elo: 250, type: "—Opening Quest—", title: "Prancing With Myself", description: "Begin the game with 3 knight&nbsp;moves." },
                { elo: 500, type: "—Opening Quest—", title: "I Wanna Prance With&nbsp;Somebody", description: "Begin the game with 4 knight&nbsp;moves." },
                { elo: 750, type: "—Opening Quest—", title: "Save The Last Prance For Me", description: "Begin the game with 5 knight&nbsp;moves." },
                { elo: 1000, type: "—Opening Quest—", title: "Shut Up And Prance", description: "Begin the game with 6 knight&nbsp;moves." },
                { elo: 'Magnus', type: "—Opening Quest—", title: "Prance Prance Revolution", description: "Begin the game with 7 knight&nbsp;moves." },

                { elo: 250, type: "—Opening Quest—", title: "Early Bird Appetizer", description: "Capture 2 chess pieces by move 6." },
                { elo: 500, type: "—Opening Quest—", title: "Early Bird Dinner", description: "Capture 3 chess pieces by move 9." },
                { elo: 750, type: "—Opening Quest—", title: "Early Bird Buffet", description: "Capture 4 chess pieces by move 12." },
                { elo: 1000, type: "—Opening Quest—", title: "Early Bird AYCE", description: "Capture 5 chess pieces by move 15." },

                { elo: 250, type: "—Opening Quest—", title: "Nonconfrontational", description: "Go 5 turns without capturing a piece or pawn." },
                { elo: 500, type: "—Opening Quest—", title: "Conscientious Objector", description: "Go 7 turns without capturing a piece or pawn." },
                { elo: 1000, type: "—Opening Quest—", title: "Pacifist", description: "Go 9 turns without capturing a piece or pawn." },

                { elo: 500, type: "—Opening Quest—", title: "Hey Diddle Diddle", description: "Get your rooks to the middle on |d1 and e1| / ~d8 and e8~ by turn&nbsp;15." },
                { elo: 250, type: "—Opening Quest—", title: "Hey Kniddle Kniddle", description: "Get your knights to the middle on |d2 and e2| / ~d7 and e7~ by turn&nbsp;4." },

                { elo: 1000, type: "—Opening Quest—", title: "Royal Swap", description: "Swap the positions of your king and queen by turn&nbsp;10." },
                { elo: 1000, type: "—Opening Quest—", title: "Knight Swap", description: "Swap the positions of your knights on the |1st| / ~8th~ rank by turn&nbsp;20." },
                { elo: 1000, type: "—Opening Quest—", title: "Rook Swap", description: "Swap the positions of your rooks on the |1st| / ~8th~ rank by turn&nbsp;20." },

                { elo: 1000, type: "—Opening Quest—", title: "The Great Wall", description: "You must move all your pawns up one square before you can move any of them a second&nbsp;time.<br><br>If your opponent captures a pawn before you can complete your wall, say \"Just great, now the Mongols can invade!\" and then continue until your remaining pawns have made their first move." },
                { elo: 1000, type: "—Opening Quest—", title: "The Greater Wall", description: "You must move all your pawns up two squares before you can move any of them a second&nbsp;time.<br><br>If your opponent captures a pawn before you can complete your wall, say \"Just great, now the Mongols can invade!\" and then continue until your remaining pawns have made their first move." },
                { elo: 750, type: "—Opening Quest—", title: "One Of Everything", description: "You have to move a pawn, knight, bishop, rook, and queen once before you can move any attacking piece a second&nbsp;time.<br><br>Castling counts as moving both pieces. If your opponent captures a piece, consider&nbsp;it&nbsp;moved." },
                { elo: 'Magnus', type: "—Opening Quest—", title: "Gotta Push 'Em All!", description: "You have to move every attacking piece once before you can move any of them a second&nbsp;time.<br><br>Castling counts as moving both pieces. If your opponent captures a piece, consider&nbsp;it&nbsp;moved." },


                // Opening Moves
                { elo: 250, type: "—Opening Move—", title: "The Knights Grimm", description: "Open with |Na3, Nh3| / ~Na6, Nh6~." },
                { elo: 250, type: "—Opening Move—", title: "Good Game", description: "Open with |g3, g4| / ~g6, g5~." },
                { elo: 250, type: "—Opening Move—", title: "Ctrl-Z", description: "Open with |Nc3, Nb1| / ~Nc6, Nb8~." },
                { elo: 250, type: "—Opening Move—", title: "Gates Are Open, Come&nbsp;On&nbsp;In", description: "Open with |d3, f3| / ~d6, f6~." },
                { elo: 250, type: "—Opening Move—", title: "Outsiders", description: "Open with |a4, h4| / ~a5, h5~." },
                // { elo: 250, type: "—Opening Move—", title: "\"Say Cheese!\"", description: "Open with |c4, d3, e4| / ~c5, d6, e5~, then say, \"Say Cheese!\" and take a picture of the&nbsp;board." },
                { elo: 250, type: "—Opening Move—", title: "Rush A", description: "Open with |a4, a5| / ~a5, a4~." },
                { elo: 250, type: "—Opening Move—", title: "Rush B", description: "Open with |b4, b5| / ~b5, b4~." },

                // { elo: 500, type: "—Opening Move—", title: "You're Going To University And That's&nbsp;Final!", description: "You are forced to play the Scholar's Mate: |e4, Bc4, Qh5| / ~e5,&nbsp;Bc5,&nbsp;Qh4~." },
                { elo: 500, type: "—Opening Move—", title: "Anti-Feingold", description: "Open with |f3, f4| / ~f6, f5~." },
                { elo: 500, type: "—Opening Move—", title: "Guns Out", description: "Open with |a4, Ra3, h4, Rh3| / ~a5, Ra6, h5, Rh6~." },
                { elo: 500, type: "—Opening Move—", title: "Tempt Fate", description: "Open with |f3, g4| / ~f6, g5~ and hope for the&nbsp;best." },

                { elo: 750, type: "—Opening Move—", title: "Bongcloud", description: "Open with |e4, Ke2| / ~e5, Ke7~." },
                { elo: 1000, type: "—Opening Move—", title: "Bongcloud And Back", description: "Open with |e4, Ke2, Ke1| / ~e5, Ke7, Ke8~." },


                // Spelling Bee
                { elo: 250, type: "—Spelling Bee—", title: "The Other London Opening", description: "Your first three pawn moves must spell,&nbsp;\"BBC.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "It Flows", description: "Your first three pawn moves must spell,&nbsp;\"ebb.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "ulous", description: "Your first three pawn moves must spell,&nbsp;\"fab.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "Bird Opening", description: "Your first three pawn moves must spell,&nbsp;\"dee.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "Knock Knock", description: "Your first three pawn moves must spell,&nbsp;\"DEA.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "The Egg", description: "Your first three pawn moves must spell,&nbsp;\"egg.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "Sheep", description: "Your first three pawn moves must spell,&nbsp;\"baa.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                // { elo: 250, type: "—Spelling Bee—", title: "Open S_s_m_", description: "Your first three pawn moves must spell,&nbsp;\"eae.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "\"Bro, it's a 100% natty opening,&nbsp;bro!\"", description: "Your first three pawn moves must spell, \"hgh.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "Taxi!", description: "Your first three pawn moves must spell,&nbsp;\"cab.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "When Life Gives You&nbsp;Lemons", description: "Your first three pawn moves must spell,&nbsp;\"ade.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "She's A Witch!", description: "Your first three pawn moves must spell,&nbsp;\"hag!\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "Humbug!", description: "Your first three pawn moves must spell,&nbsp;\"bah!\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "Eureka!", description: "Your first three pawn moves must spell,&nbsp;\"aha!\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "Buzz Buzz", description: "Your first three pawn moves must spell,&nbsp;\"bee.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "Spilling The Tea", description: "Your first three pawn moves must spell,&nbsp;\"gab.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "Willickers!", description: "Your first three pawn moves must spell,&nbsp;\"gee.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "Pretty Please With A Cherry On&nbsp;Top", description: "Your first three pawn moves must spell,&nbsp;\"beg.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "It's Not A Good Opening", description: "Your first three pawn moves must spell, \"bad.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },

                { elo: 250, type: "—Spelling Bee—", title: "Pet Detective", description: "Your first three pawn moves must spell, \"ace.\"<br>When finished, say&nbsp;\"Alright then!\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "Take A Load Off", description: "Your first three pawn moves must spell, \"ahh.\"<br>When finished, sigh&nbsp;\"Ahhhh.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "Boo!", description: "Your first three pawn moves must spell, \"aah!\"<br>When finished, scream&nbsp;\"Aaaaaah!\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "Knee Slapper", description: "Your first three pawn moves must spell, \"hah.\"<br>When finished, slap your knee and laugh&nbsp;maniacally.<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 250, type: "—Spelling Bee—", title: "Schemin'", description: "Your first three pawn moves must spell,&nbsp;\"heh.\"<br>When finished, rub your hands together and say,&nbsp;\"heh heh heh.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter. " },

                { elo: 500, type: "—Spelling Bee—", title: "Pops", description: "Your first four pawn moves must spell,&nbsp;\"dada.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Born This Way", description: "Your first four pawn moves must spell,&nbsp;\"gaga.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Concerto For Two Violins", description: "Your first four pawn moves must spell,&nbsp;\"bach.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Don't Give A Care", description: "Your first four pawn moves must spell,&nbsp;\"dgac.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Don't Give A [Care]", description: "Your first four pawn moves must spell,&nbsp;\"dgaf.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Give A Space&nbsp;Advantage", description: "Your first four pawn moves must spell,&nbsp;\"cede.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Hopefully Not Prophecy", description: "Your first four pawn moves must spell,&nbsp;\"dead.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Nice Cut", description: "Your first four pawn moves must spell,&nbsp;\"fade.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Get Cooking", description: "Your first four pawn moves must spell,&nbsp;\"chef.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Hot Bean Water", description: "Your first four pawn moves must spell,&nbsp;\"cafe.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Oh No, Old Chap", description: "Your first four pawn moves must spell,&nbsp;\"egad.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Disco", description: "Your first four pawn moves must spell,&nbsp;\"abba.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "\"Does bebe enjoy the theatre?\"", description: "Your first four pawn moves must spell, \"bebe.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "The White Whaler", description: "Your first four pawn moves must spell, \"ahab.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Wagyu", description: "Your first four pawn moves must spell, \"beef.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "High T Opening", description: "Your first four pawn moves must spell,&nbsp;\"chad.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },

                { elo: 500, type: "—Spelling Bee—", title: "Lock 'Em Up", description: "Your first five pawn moves must spell,&nbsp;\"caged.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Not Looking Good", description: "Your first five pawn moves must spell,&nbsp;\"effed.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Keep A Stash", description: "Your first five pawn moves must spell,&nbsp;\"cache.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Real Detective", description: "Your first five pawn moves must spell,&nbsp;\"badge.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "Won't Keep You Up", description: "Your first five pawn moves must spell, \"decaf.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "You Know What They Say", description: "Your first five pawn moves must spell, \"adage.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },

                { elo: 500, type: "—Spelling Bee—", title: "Pig In The City", description: "Your first four pawn moves must spell,&nbsp;\"babe.\" If you do it by turn 4, say, \"That'll do, pig. That'll do.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 500, type: "—Spelling Bee—", title: "You Are Kenough", description: "Your first five pawn moves must spell,&nbsp;\"beach.\" If you do it by turn 5, you must shout,&nbsp;\"Sublime!!\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },

                { elo: 750, type: "—Spelling Bee—", title: "The Don Draper", description: "Your first six pawn moves must spell,&nbsp;\"adchad.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Cheating?", description: "Your first six pawn moves must spell,&nbsp;\"beaded.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Fannypacks", description: "Your first six pawn moves must spell,&nbsp;\"badfad.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Fashionable Father", description: "Your first six pawn moves must spell,&nbsp;\"fabdad.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Signed An NDA", description: "Your first six pawn moves must spell,&nbsp;\"gagged.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "A Hive?", description: "Your first six pawn moves must spell,&nbsp;\"beebag.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Rotten", description: "Your first six pawn moves must spell,&nbsp;\"badegg.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "It's A Front", description: "Your first six pawn moves must spell,&nbsp;\"facade.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Executioner", description: "Your first six pawn moves must spell,&nbsp;\"behead.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "The Longest Opening", description: "Your first six pawn moves must spell,&nbsp;\"decade.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Graffiti", description: "Your first six pawn moves must spell,&nbsp;\"deface.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Whoops!", description: "Your first six pawn moves must spell, \"gaffed.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Better Bettor", description: "Your first six pawn moves must spell, \"hedged.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },

                { elo: 750, type: "—Spelling Bee—", title: "Belly Laugher", description: "Your first six pawn moves must spell, \"hahaha.\"  When finished, put your hands on your hips and laugh&nbsp;maniacally.<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Villainous", description: "Your first six pawn moves must spell,&nbsp;\"hehehe.\" When finished, rub your hands together and say,&nbsp;\"heh heh heh.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter. " },
                { elo: 750, type: "—Spelling Bee—", title: "The Other Bongcloud", description: "Your first six pawn moves must spell, \"cheech.\" If you do it by turn 6, you must say, \"Far&nbsp;out,&nbsp;man.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },

                { elo: 750, type: "—Spelling Bee—", title: "The Knight's Favourite Opening", description: "Your first seven pawn moves must spell, \"feedbag.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Rough Cut", description: "Your first seven pawn moves must spell, \"badfade.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Non-Vegan", description: "Your first seven pawn moves must spell, \"addbeef.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Get It Checked", description: "Your first seven pawn moves must spell,&nbsp;\"baggage.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Reap What You Sow", description: "Your first seven pawn moves must spell,&nbsp;\"cabbage.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Sleepyhead", description: "Your first seven pawn moves must spell, \"bedhead.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Angling For A&nbsp;Promotion", description: "Your first seven pawn moves must spell, \"acceded.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Smartypants", description: "Your first seven pawn moves must spell, \"egghead.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Brunch", description: "Your first seven pawn moves must spell, \"eggchef.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 750, type: "—Spelling Bee—", title: "Iraq Opening", description: "Your first seven pawn moves must spell, \"baghdad.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },

                { elo: 1000, type: "—Spelling Bee—", title: "Silver Fox", description: "Your first eight pawn moves must spell,&nbsp;\"agedchad.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 1000, type: "—Spelling Bee—", title: "Not Tonight, Honey", description: "Your first eight pawn moves must spell,&nbsp;\"headache.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 1000, type: "—Spelling Bee—", title: "Bees?", description: "Your first eight pawn moves must spell,&nbsp;\"beadbead.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 1000, type: "—Spelling Bee—", title: "Executionee", description: "Your first eight pawn moves must spell,&nbsp;\"beheaded.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 1000, type: "—Spelling Bee—", title: "Friend Of The Devil", description: "Your first eight pawn moves must spell,&nbsp;\"deadhead.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },

                { elo: 1000, type: "—Spelling Bee—", title: "\"Strength does not come from winning. Your struggles develop your strengths.\" -&nbsp;Arnold&nbsp;Schwarzenegger", description: "Your first nine pawn moves must spell,&nbsp;\"chadadage.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 1000, type: "—Spelling Bee—", title: "Attack From The Seas", description: "Your first nine pawn moves must spell,&nbsp;\"beachhead.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 1000, type: "—Spelling Bee—", title: "One, two—", description: "Your first nine pawn moves must spell, \"chachacha.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 1000, type: "—Spelling Bee—", title: "Coffee By The Water", description: "Your first nine pawn moves must spell, \"beachcafe.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },

                { elo: 'Magnus', type: "—Spelling Bee—", title: "Highest T Opening", description: "Your first four pawn moves must spell, \"chad.\" You can't move any pawns&nbsp;afterwards.<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },

                { elo: 'Magnus', type: "—Spelling Bee—", title: "Too Much Protein", description: "Your first ten pawn moves must spell,&nbsp;\"chadbeefed.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 'Magnus', type: "—Spelling Bee—", title: "Secretly Low T", description: "Your first ten pawn moves must spell,&nbsp;\"chadfacade.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 'Magnus', type: "—Spelling Bee—", title: "Hairpiece", description: "Your first ten pawn moves must spell, \"badfacade.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 'Magnus', type: "—Spelling Bee—", title: "Spoiled", description: "Your first ten pawn moves must spell, \"badcabbage.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 'Magnus', type: "—Spelling Bee—", title: "Disco Is Dead, And You Killed&nbsp;It", description: "Your first ten pawn moves must spell, \"beheadabba.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 'Magnus', type: "—Spelling Bee—", title: "Rough Morning", description: "Your first ten pawn moves must spell, \"badbedhead.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },

                { elo: 'Magnus', type: "—Spelling Bee—", title: "Old Money", description: "Your first eleven pawn moves must spell, \"agedcheddah.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 'Magnus', type: "—Spelling Bee—", title: "Something Smells Off", description: "Your first eleven pawn moves must spell, \"badagedbeef.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },
                { elo: 'Magnus', type: "—Spelling Bee—", title: "\"Is it because I have a cabbage for a&nbsp;head?\"", description: "Your first eleven pawn moves must spell, \"cabbagehead.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },

                { elo: 'Magnus', type: "—Spelling Bee—", title: "Shopping List", description: "Your first thirteen pawn moves must spell, \"baggedcabbage.\"<br><br>You can move your other pieces in between. If you lose a necessary pawn, move on to the next&nbsp;letter." },


                // Multi-Rules
                { elo: 500, type: "—Multi-Rule—", title: "Habits Brah Lvl 3", description: "Obey the following habits rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;No gambits.</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;No sacrifices.</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;Castle early (but not ASAP).</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;Once finished development, create an escape square for the king.</li></ul>" },
                { elo: 750, type: "—Multi-Rule—", title: "Habits Brah Lvl 2", description: "Obey the following habits rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;No gambits.</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;No sacrifices.</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;Can only premove when under 10 seconds.</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;Pawns always capture towards the centre.</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;Castle early (but not ASAP).</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;Once finished development, create an escape square for the king.</li></ul>" },
                { elo: 1000, type: "—Multi-Rule—", title: "Habits Brah Lvl 1", description: "Obey the following habits rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;No pre-moves.</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;No tactics.</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;No gambits.</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;No sacrifices.</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;Pawns always capture towards the centre.</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;Always capture pieces of equal or greater value.</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;Castle as soon as possible.</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;Once finished development, create an escape square for the king.</li></ul>" },

                { elo: 250, type: "—Single-Rule—", title: "Mystery Box", description: "Obey the following one rule:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },
                { elo: 250, type: "—Single-Rule—", title: "What's Behind Door Number&nbsp;One?", description: "Obey the following one rule:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },
                { elo: 250, type: "—Single-Rule—", title: "Let's See Who's Under This Mask!", description: "Obey the following one rule:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },

                { elo: 500, type: "—Multi-Rule—", title: "Smorgasbord", description: "Obey the following two rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },
                { elo: 500, type: "—Multi-Rule—", title: "Mish-Mash", description: "Obey the following two rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },
                { elo: 500, type: "—Multi-Rule—", title: "Jumble", description: "Obey the following two rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },

                { elo: 750, type: "—Multi-Rule—", title: "That One Miscellaneous Drawer We&nbsp;All&nbsp;Have", description: "Obey the following three rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },
                { elo: 750, type: "—Multi-Rule—", title: "Pot Pourri", description: "Obey the following three rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },
                { elo: 750, type: "—Multi-Rule—", title: "Medley", description: "Obey the following three rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },

                { elo: 1000, type: "—Multi-Rule—", title: "Odds & Ends", description: "Obey the following four rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },
                { elo: 1000, type: "—Multi-Rule—", title: "Box Of Chocolates", description: "Obey the following four rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },
                { elo: 1000, type: "—Multi-Rule—", title: "Mix n' Match", description: "Obey the following four rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },

                { elo: 'Magnus', type: "—Multi-Rule—", title: "Hodge Podge", description: "Obey the following five rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },
                { elo: 'Magnus', type: "—Multi-Rule—", title: "Grab Bag", description: "Obey the following five rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },
                { elo: 'Magnus', type: "—Multi-Rule—", title: "Patchwork", description: "Obey the following five rules:<br><br><ul><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureLight'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li><li><span class='featureDark'>&#x25A0;</span>&nbsp;&nbsp;&nbsp;¡</li></ul>" },

                { elo: 1000, type: "—Multi-Rule—", title: "Crosshairs", description: "You can't land a piece or pawn on the |ƒ(3-6)| file or the |®(3-6)* rank|." },
                { elo: 'Magnus', type: "—Multi-Rule—", title: "Crosshairs", description: "You can't land a piece or pawn on the |ƒ(3-6)| file or the |®(3-6)* rank|." },


                // Bad Ones
                // { elo: 500, type: "—Quest—", title: "Snipers!!", description: "Put both bishops in the corner of the board." },
                // { elo: 1000, type: "—Quest—", title: "Dunces", description: "Put both knights into both your corners of the board at&nbsp;once." },
                // { elo: 1000, type: "—Quest—", title: "Queenside Purist", description: "Have all your attacking pieces on the |a| through |d|&nbsp;files." },
                // { elo: 1000, type: "—Quest—", title: "Kingside Purist", description: "Have all your attacking pieces on the |e| through |h|&nbsp;files." },
                // { elo: 1000, type: "—Quest—", title: "Queenside? What Queenside?", description: "Have all your attacking pieces plus your king on the |a| through |d| files, and no pawns on the |e| through |h|&nbsp;files." },
                // { elo: 1000, type: "—Quest—", title: "Kingside? What Kingside?", description: "Have all your attacking pieces plus your king on the |e| through |h| files, and no pawns on the |a| through |d|&nbsp;files." },
                // { elo: 750, type: "—Quest—", title: "Council of Elrond", description: "You can't capture pieces until you've had a bishop, knight, rook, and queen next to your king at&nbsp;one&nbsp;time." },
                // { elo: 750, type: "—Quest—", title: "Fire Alarm", description: "Completely vacate your backrank before the&nbsp;endgame.<br><br><i>Endgame = neither player has more than 10 points of&nbsp;material.</i>" },
                // { elo: 500, type: "—Quest—", title: "A Royal Affair", description: "Get your queen close enough to kiss the opponent's king." },
                // { elo: 1000, type: "—Piece Restriction—", title: "The Champion", description: "Pick one knight, bishop, or rook as your&nbsp;champion.<br>The rest can't move until your champion is dead.<br><br>Repeat." },

            ];

            const databaseSpecialChars = [
              { replacement: ["Your |ƒ| pawn cannot move."] },
              { replacement: ["You can't castle queenside." , "You can't castle kingside."] },
              { replacement: ["You can't en passant." , "En passant is forced."] },
              { replacement: ["You can't move your rook on the |a| file until turn&nbsp;20." , "You can't move your rook on the |h| file until turn&nbsp;20." , "You can't move your knight on the |b| file until turn&nbsp;20." , "You can't move your knight on the |g| file until turn&nbsp;20." , "You can't move your bishop on the |c| file until turn&nbsp;20." , "You can't move your bishop on the |f| file until turn&nbsp;20."] },
              // { replacement: ["You must have more pieces on light&nbsp;squares." , "You must have more pieces on dark&nbsp;squares."] },
              { replacement: ["Pawns can only capture to the left." , "Pawns can only capture to the right."] },
              { replacement: ["Isolated pawns can't move."] },
              { replacement: ["Doubled pawns can't move." , "You cannot make any move that puts two pawns on the same&nbsp;file."] },
              { replacement: ["Your king cannot pass the |4th| / ~5th~ rank." , "Your queen cannot pass the |4th| / ~5th~ rank."] },
              { replacement: ["Your king cannot capture pawns." , "Your queen cannot capture pawns."] },
              { replacement: ["You cannot land a piece on |ƒ®(3-6)|."] },
              { replacement: ["Pawns can only move one square at a time in the&nbsp;opening." , "Pawns must move two squares at a time in the&nbsp;opening."] },
              { replacement: ["You can only promote to a knight." , "You can only promote to a bishop." , "You can only promote to a rook."]  },
              { replacement: ["You must fianchetto a bishop in the&nbsp;opening."] },
              { replacement: ["Your knights can't capture the opponent's&nbsp;queen." , "Your bishops can't capture the opponent's&nbsp;queen." , "Your rooks can't capture the opponent's&nbsp;queen."] },
              { replacement: ["If your knight can capture a knight, it&nbsp;must." , "If your bishop can capture a bishop, it&nbsp;must." , "If your rook can capture a rook, it&nbsp;must."] },
              { replacement: ["Your pawns can only capture pawns." , "Your pawns cannot capture pawns."] },
              { replacement: ["You can only have two pieces in the centre four squares at&nbsp;once."] },

            ];
```

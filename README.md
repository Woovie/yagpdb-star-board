# YAGPDB Star Board

A star board function for YAGPDB, simple as that.

## Why?

I don't like having several Discord bots that serve only say one purpose. YAGPDB doesn't have a built in star board, so we used Dyno for a long time. This eliminates Dyno.

Less bots, more secure.

## How to use

It's pretty straightforward, you will see (variables at the top of the file)[https://github.com/Woovie/yagpdb-star-board/blob/main/starboard.go.tmpl#L3-L6] which are what you should edit.

- `reactionEmoji` sets what emoji will be used.
- `minReactions` sets the minimum number of reactions from all users that are needed in order for the post to get copied over. Using a greater than or equal to here.
- `reactorRoleIDs` is a space separated list of role IDs which bypasses the number limit.
- `repostChannelID` is what channel the starred posts get sent to.

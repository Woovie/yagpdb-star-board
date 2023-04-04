# YAGPDB Star Board

A star board function for YAGPDB, simple as that.

![image](https://user-images.githubusercontent.com/7304619/229657280-357f6544-33d4-4e31-b94a-9bf20252c659.png)

## How does it work?

After a certain defined of users or after a member with a particular role react to a post, YAGPDB will copy the contents of the post to a new embed in another channel. This works as a way to show what people like/laugh at/enjoy.

## Why?

I don't like having several Discord bots that serve only say one purpose. YAGPDB doesn't have a built in star board, so we used Dyno for a long time. This eliminates Dyno.

Less bots, more secure.

## How to use

It's pretty straightforward, you will see (variables at the top of the file)[https://github.com/Woovie/yagpdb-star-board/blob/main/starboard.go.tmpl#L3-L6] which are what you should edit.

- `reactionEmoji` sets what emoji will be used.
- `minReactions` sets the minimum number of reactions from all users that are needed in order for the post to get copied over. Using a greater than or equal to here.
- `reactorRoleIDs` is a space separated list of role IDs which bypasses the number limit.
- `repostChannelID` is what channel the starred posts get sent to.

<template>
    <div class="container mt-4">
        <h1>Rules</h1>
        <div class="row">
            <div class="shadow p-3 mb-3 bg-white rounded">
                <p>
                    The rules of Rummikub are fairly simple to understand. The biggest issue, in fact, with the game doesn't come from complicated game play or strategies; it lies simply in remembering what you can and can't do on a turn. Much like the card games gin, rummy and even solitaire, it's not a lack of expertise that will cause a loss. More likely, you'll find yourself in trouble if you're distracted and missing opportunities right in front of you.
                </p>
            </div>
            <div class="shadow p-3 mb-3 bg-white rounded">
                <p>
                    When you first sit down to play Rummikub (two to four players are recommended), you'll dump the numbered, multi-colored tiles on the table face-down. Each player will draw one tile; the highest number goes first, and the 1 tile is always low. (Return those tiles randomly to the table.) Each player will then draw 14 tiles from the table, placing them on their rack; whatever is left forms the pool. On the first turn, each player will attempt to make a set of one or more groups or runs that adds up to at least 30 points.
                </p>
            </div>
            <div class="shadow p-3 mb-3 bg-white rounded">
                <p>
                    A group is formed when three or four tiles of the same numbers are put together; like suits in a deck of cards, each number will have a different color. A run is formed when three or more numbers of the same color are played together. Playing a group or a run makes a set (sometimes called a meld). So on your first turn, you must lay either groups or runs that add up to at least 30 points. If your tiles aren't cooperating, no worries: You can take a tile from the pool in the hopes it'll help you snag a 30-point set to get you in the game. You can't play the drawn tile until the next turn, however -- this goes for any tile drawn during the game.
                </p>
            </div>
            <div class="shadow p-3 mb-3 bg-white rounded">
                <p>
                    From there, it's your job on every turn to scope out places where your tiles can add to a run or a group. This is called melding. A few ways to meld:
                </p>
                <ul>
                    <li>
                        Add a tile to an existing run or group.
                    </li>
                    <li>
                        Take the fourth tile from a run or group to complete your own set or add a fourth to another group and take another tile to create a new set.
                    </li>
                    <li>
                        Split a run. For instance, a run of 4, 5, 6, 7, 8 is on the table. You take a six from your rack and create a 4, 5, 6 run and make the remaining 6, 7, 8 its own run.
                    </li>
                </ul>
            </div>
            <div class="shadow p-3 mb-3 bg-white rounded">
                <p>
                    The object of the game is to place all your tiles on the table as part of a set. Once someone does that, that person can proclaim "Rummikub." The losers add up the value of the tiles they're still holding on their racks, and that score is written as a negative number. The winner gets a positive score that equals the total of all the losers' negative points.
                </p>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Rules',
        // props: {
        //     msg: String
        // }
    }
</script>
# HaliteIII

These are my Halite iterations, which start, and hopefully don't finish with Sentdex 6-part tutorial.
    
    Ideas for the Future:
    1/  create two different strategies (which will be mostly the same, just different constants) if a game is 2vs4 players.
        prior to game.ready("P1") you can go
            if #players ==2:
                follow this majorloop
            if #players==4:
                follow that majorloop
    
    2/ fix bug where when a ship is ~0.7 capacity, it goes from collecting to depositing and confuses the other ships so they   
        collide. at least that's what i think is happening.
        
        
    3/ Deal with manhattan distances more.
            right now the ship and shipyard make a + sign, and they use the vertical and horizontal column/row of the shipyard              as a highway instead of zig-zagging. see the documentation on manhattan distances to make fixy-fix.

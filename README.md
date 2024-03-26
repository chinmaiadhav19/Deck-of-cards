# Deck-of-cards
Project Name: DECK OF CARDS
Base URL: https://www.deckofcardsapi.com
Collection:[Deck of cards]
            Request 1:POST Shuffle the Cards  /api/deck/new/shuffle/?deck_count=1,
            Request 2:GET Draw a Card  /api/deck/{deck_id}/draw/?count=2,
            Request 3:GET Reshuffle the Cards  /api/deck/{deck_id}/shuffle/?remaining=true,
            Request 4:POST A Brand New Deck /api/deck/new/jokers_enabled=true,
            Request 5:GET A Partial Deck /api/deck/new/shuffle/?cards=AS,2S,KS,AD,2D,KD,AC,2C,KC,AH,2H,KH, 
            Request 6:GET Adding to Piles /api/deck/{deck_id}/pile/name/add/?cards=AS,2S,
            Request 7:GET Listing Cards in Piles /deck/{deck_id}/pile/name/list/,
            Request 8:GET Drawing from Piles /api/deck/{deck_id}/pile/name/draw/bottom,
            Request 9:GET Returning cards to the deck  /api/deck/{deck_id}/return/,
            Request 10:GET Back of Card Image /static/img/back.png,
            


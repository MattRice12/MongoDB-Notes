# Find item
  * Normal searches

    db.potions.find({"ingredients": "laughter"})


  * Dot notation (With hashes -- i.e., query embedded documents)

    db.potions.find({"ratings.flavor": 5})

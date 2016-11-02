# Add new data
  db.potions.insert(
    {
      "name": "Invisibility",
      "vendor": "James",
      "price": 10.99,
      "ingredients": ["newt toes", 42, "laughter"],
      "ratings": {"strength": 2, "flavor": 5}
    }
  )

  #=> WriteResult({ "nInserted": 1 })



  db.wands.insert(
    {
      "name": "Dream Bender",
      "creator": "Foxmond",
      "level_required": 10,
      "price": 34.9,
      "powers": ["Fire", "Love"],
      "damage": {"magic": 4, "melee": 2},
    }
  )

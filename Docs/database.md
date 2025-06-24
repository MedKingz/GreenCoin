| Table         | Fields                                                        |
| ------------- | ------------------------------------------------------------- |
| users       | id, name, email, hashed_pw, greencoin_balance                   |
| actions     | id, user_id, image_url, action_type, co2_saved, timestamp       |
| coins       | id, user_id, action_id, amount, minted_on                       |
| leaderboard | id, user_id, total_co2, total_coins                             |

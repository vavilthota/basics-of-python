age = int(input("Enter the age:\n"))
print(f"Age of Dhoni is {age}")






question = input("Banerjee's Question:\n")
reply = "I will if I get a chance."
print(f"Dhoni's Reply:\n{reply}")
print(f"For Banerjee's question \"{question}\" Dhoni's confident reply was \"{reply}\".")





print("Team 1:")
team1_name = input("Team Name:\n")
team1_score = input("Score:\n")
team1_overs = input("Overs played:\n")
print("Team 2:")
team2_name = input("Team name:\n")
team2_score = input("Score:\n")
team2_overs = input("Overs played:\n")
print("Match Details:")
print(f"Team 1:\nName: {team1_name}\nScore: {team1_score}\nOvers played: {team1_overs}")
print(f"Team 2:\nName: {team2_name}\nScore: {team2_score}\nOvers played: {team2_overs}")



dhoni_age = int(input())
devki_age = (4 * (dhoni_age + 3)) - 3
print(devki_age)





X = int(input())
Y = int(input())
Z = float(input())
days = 30
total_distance = 2 * X * days
litres_needed = total_distance / Y
total_cost = litres_needed * Z
print(f"{total_cost:.2f}")




salary = int(input())
bonuses_awards = int(input())
endorsements = int(input())
total_income = salary + bonuses_awards + endorsements
salary_percentage = (salary / total_income) * 100
bonuses_awards_percentage = (bonuses_awards / total_income) * 100
endorsements_percentage = (endorsements / total_income) * 100
print(f"{salary_percentage:.2f} {bonuses_awards_percentage:.2f} {endorsements_percentage:.2f}")





no_balls = int(input())
wides = int(input())
byes = int(input())
leg_byes = int(input())
penalty_runs = int(input())
total_extras = (no_balls + wides + byes + leg_byes + (penalty_runs * 5))
print(total_extras)




X = int(input())
Y = int(input())
senior_players_count = 6
junior_players_count = 5
senior_contribution_rate = 0.50  # 50%
junior_contribution_rate = 0.40    # 40%
senior_contribution = senior_players_count * (X * senior_contribution_rate)
junior_contribution = junior_players_count * (Y * junior_contribution_rate)
total_contribution = senior_contribution + junior_contribution
print(f"{total_contribution:.2f}")



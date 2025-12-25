# daily_update.p
import datetime
import random

print("Daily GitHub activity - Day 39")

today = datetime.date.today()

# Generate random steps for a week and analyze
steps = [random.randint(3000, 12000) for _ in range(7)]
total_steps = sum(steps)
average_steps = total_steps // len(steps)
best_day = max(steps)
worst_day = min(steps)

print(f"Today's date: {today}")
print("Daily steps:", steps)
print("Total steps:", total_steps)
print("Average steps:", average_steps)
print("Best day steps:", best_day)
print("Worst day steps:", worst_day)

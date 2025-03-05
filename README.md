import matplotlib.pyplot as plt

# Sample population distribution across age groups (in millions)
age_groups = ["0-14", "15-24", "25-54", "55-64", "65+"]
population_counts = [1500, 1000, 3000, 800, 600]  # Hypothetical values

# Create the bar chart
plt.figure(figsize=(8, 5))
plt.bar(age_groups, population_counts, color='skyblue', edgecolor='black')

# Labels and title
plt.xlabel("Age Groups")
plt.ylabel("Population (millions)")
plt.title("Population Distribution by Age Groups")
plt.grid(axis='y', linestyle='--', alpha=0.7)

# Show the plot
plt.show()

ratings = {
    'John': {'Hair Oil': 16, 'Shampoo': 20, 'Soap': 12, 'Face Cream': 18, 'Toothpaste': 15},
    'Mary': {'Hair Oil': 12, 'Shampoo': 16, 'Face Cream': 20, 'Toothpaste': 18},
    'Victor': {'Shampoo': 20, 'Soap': 16, 'Face Cream': 12, 'Toothpaste': 15},
    'Devi': {'Hair Oil': 20, 'Soap': 16, 'Face Cream': 8, 'Toothpaste': 10},
    'Prasath': {'Hair Oil': 16, 'Shampoo': 20, 'Soap': 12, 'Toothpaste': 15},
    'Alice': {'Shampoo': 19, 'Soap': 18, 'Face Cream': 16, 'Toothpaste': 20},
    'Bob': {'Hair Oil': 20, 'Shampoo': 18, 'Face Cream': 15, 'Toothpaste': 17},
    'Catherine': {'Hair Oil': 17, 'Shampoo': 19, 'Soap': 15, 'Face Cream': 18, 'Toothpaste': 20},
    'David': {'Hair Oil': 15, 'Soap': 20, 'Face Cream': 18, 'Toothpaste': 17},
    'Emily': {'Hair Oil': 18, 'Shampoo': 20, 'Face Cream': 17, 'Toothpaste': 19}
}

def recommend_items(ratings, user):
    user_ratings = ratings[user]
    sorted_ratings = sorted(user_ratings.items(), key=lambda x: x[1], reverse=True)
    recommended_items = [item for item, rating in sorted_ratings if rating >= 16]
    return recommended_items

user = 'John'
recommendations = recommend_items(ratings, user)
print("Recommended items for", user, ":", recommendations)

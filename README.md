
# Random Poems API

## Introduction
The Random Poems API is a versatile tool designed for developers and enthusiasts who want to integrate poetry into their applications. This API allows you to fetch random poems or search for specific poems based on title, author, or genre, making it ideal for literary projects, creative tools, or educational platforms.

---

## Key Features
- **Random Poem Generator**: Retrieve random poems with detailed information.
- **Author Search**: Find poems by specific authors.
- **Genre-Specific Poems**: Filter poems based on genres or themes.
- **Rich Metadata**: Access poem details, including title, author, and full content.

---

## Applications
- **Inspiration for Writers**: Provide random poetic content for creative inspiration.
- **Education**: Support literature teaching and poetry analysis in academic applications.
- **Literary Exploration**: Allow users to discover poems based on their preferences.

---

## Getting Started

### Requirements
- A RapidAPI account.
- Subscription to the Random Poems API.

### Steps to Access
1. **Sign Up on RapidAPI**
   - Visit [RapidAPI](https://rapidapi.com/robotfa-robotma/api/the-poems-unlimited-access) and create a free account.

2. **Subscribe to the Random Poems API**
   - Search for "Random Poems API" and subscribe to your preferred plan.

3. **Retrieve Your API Key**
   - Go to the "Endpoints" section of the API on RapidAPI.
   - Copy your unique API key (token) from the dashboard.

4. **Make API Requests**
   - Use your API key to authenticate requests. Below is an example:

     ```bash
     curl -X GET "https://the-poems-unlimited-access.p.rapidapi.com/random-poems" \
     -H "X-RapidAPI-Key: YOUR_API_KEY" \
     -H "X-RapidAPI-Host: the-poems-unlimited-access.p.rapidapi.com"
     ```

---

## API Endpoints

### 1. Fetch a Random Poem
Get a completely random poem:
```bash
GET /random
```
**Sample Response:**
```json
{
  "title": "If",
  "author": "Rudyard Kipling",
  "content": "If you can keep your head when all about you..."
}
```

### 2. Search Poems by Author
Retrieve poems written by a specific author:
```bash
GET /author/
```
**Sample Response:**
```json
[
  {
    "title": "Invictus",
    "author": "William Ernest Henley",
    "content": "Out of the night that covers me..."
  }
]
```


---

## Contribution
We welcome contributions! If you have ideas for new features or improvements, feel free to open an issue or submit a pull request.

---

## License
This API is licensed under the MIT License. Refer to the LICENSE file for detailed terms and conditions.


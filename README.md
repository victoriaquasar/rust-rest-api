## 🔹 Rust Users Rest API

> Project created to reinforce Rust knowledge based on REST principles, simulating an api
> created to manage (create, read, update and delete) users.

### Usage

**Endpoints:**

| Route | Method | Requirements | Description | Returns |
| ----- | ------ | ------------ | ----------- | ------- |
| /users | POST | body: ```{name: String, age: i32}``` | Create a new user | String (User uuid) |
| /users/user_id | POST | path: ```{user_id: String}``` | Gets an user by id | User |

### Roadmap

- [ ] ✨ Implement userId with auto-increment
- [ ] ⚒ Create an user
- [ ] ⚒ Create various users
- [ ] 📚 Read a single user
- [ ] 📚 Read all the users
- [ ] 📚 Read users with pagination
- [ ] 🗑 Delete an user
- [ ] 🗑 Delete various users
- [ ] 🗑 Delete all the users
## 🔹 Rust Users Rest API

> Project created to reinforce Rust knowledge based on REST principles, simulating an api
> created to manage (create, read, update and delete) users.

### Usage

**Endpoints:**

| Route | Method | Requirements | Description | Returns |
| ----- | ------ | ------------ | ----------- | ------- |
| /users/create | POST | body: ```{name: String, age: i32}``` | Create a new user | UserCreateResponse |
| /users/create-batch | POST | body: ```[{name: String, age: i32}...]``` | Creates new users | Vec\<UserCreateResponse> |
| /users/`user_id` | GET | path: ```{user_id: String}``` | Gets an user by id | User |
| /users | GET | - | Gets all the users | Vec\<User> |

### Roadmap

- [x] ✨ Implement `user_id` with uuid
- [x] ⚒ Create an user
- [x] ⚒ Create various users
- [x] 📚 Read a single user
- [x] 📚 Read all the users
- [ ] 📚 Read users with pagination
- [ ] 🗑 Delete an user
- [ ] 🗑 Delete various users
- [ ] 🗑 Delete all the users
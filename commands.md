## Phoenix Commands

### 1. Installation and Project Setup

🔧 **Install Phoenix**: Get Phoenix installed so you can start building your web app!
` "archive" refers to a package or bundle of files that contain predefined templates, libraries, and configurations for a particular task or purpose.`
```bash
mix archive.install hex phx_new_app_name
```
### 2. Starting the Server

🚀 **Start Server**: Fire up your Phoenix server to see your app in action!
```bash
mix phx.server
```
### 3. Dependency Management

📦 **Manage Dependencies**: Keep your project organized by installing and managing its dependencies.
```bash
mix deps.get
```
### 4. Database Management

🗃️ **Manage Database**: Adjust your database schema to match your code changes:
```bash
mix ecto.migrate
```
### 5. Data Manipulation

🔨 **Manipulate Data**: Add, update, or delete data in your database as needed.
```bash
mix ecto.insert
mix ecto.update
mix ecto.delete
```
### 6. Testing

✔️ **Run Tests**: Make sure your app works as expected by running tests.
```bash
mix test
```
### 7. Code Formatting

🎨 **Format Code**: Keep your code looking neat and tidy with automatic formatting.
```bash
mix format
```

### 8. Schema Creation

🎨 **Creating Schema**: 📋 Create a blueprint for your database structure:
```bash
mix phx.gen.json Modulename Schemaname dbtablename table_key:datatype
```
**Example :**
```bash
mix phx.gen.json Modulename Schemaname dbtablename table_key:datatype
```
**Relationship Example :**

```bash
mix phx.gen.json Users User user account_id:references:accounts full_name:string gender:string bio:text
```

These commands and concepts are the building blocks for creating and managing your Phoenix applications. Happy coding! 🌟

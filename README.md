<center><img src="https://i.postimg.cc/MKPVVR1s/dplogo-512.png" alt="logo"></center>
<center><img src="https://i.postimg.cc/RZ9dqPFx/introduce.png" alt="introduce"></center>

Example Video : *Coming soon!*

This plugin allows server owners to easily create and manage **custom crafting recipes** on their Minecraft server.  
Enable players to craft new and unique items beyond the standard Minecraft recipes, expanding your server’s gameplay with special crafts for custom items or previously uncraftable materials – all without complicated setup or configuration!

---

<center><img src="https://i.postimg.cc/RZ9dqP08/description.png" alt="description"></center>

- Create unlimited **custom crafting recipes** with your own defined ingredients and output items  
- Support for both **shaped** and **shapeless** recipes to fit any crafting pattern  
- Use **custom ingredients** (specific item types, names, or lore) as recipe components  
- Intuitive **in-game GUI** to design and edit recipes without manual file editing  
- Optional **PlaceholderAPI integration** for displaying crafting-related information  

---

<center><img src="https://i.postimg.cc/rwcjzhpH/depend-plugin.png" alt="depend-plugin"></center>

- All DP-Plugins require the **`DPP-Core`** plugin  
- The plugin will not work if **`DPP-Core`** is not installed  
- You can download **`DPP-Core`** here: <a href="https://github.com/DP-Plugins/DPP-Core/releases" target="_blank">Click me!</a>  

---

<center><img src="https://i.postimg.cc/dV01RxJB/installation.png" alt="installation"></center>

1️⃣ Place the **`DPP-Core`** plugin and this plugin file (**`DP-CustomCrafting-*.jar`**) into your server’s **`plugins`** folder  

2️⃣ Restart the server, and the plugin will be automatically enabled  

3️⃣ If needed, you can open and modify **`config.yml`** and **`plugin.yml`** to customize settings  

---

<center><img src="https://i.postimg.cc/jSKcC85K/settings.png" alt="settings"></center>

- **`config.yml`**: Manages basic plugin settings and message options  

---

<center><img src="https://i.postimg.cc/SxqdjZKw/command.png" alt="command"></center>

❗ Some commands require admin permission (`dpcc.admin`)

**Command List and Examples**

| Command | Permission | Description | Example |
|-------|------------|-------------|---------|
| `/dpcc createcategory <categoryName>` | dpcc.admin | Create a new category | `/dpcc createcategory MagicItems` |
| `/dpcc createrecipe <categoryName> <recipeName>` | dpcc.admin | Create a new recipe inside a category | `/dpcc createrecipe MagicItems FireWand` |
| `/dpcc recipeitem <categoryName> <recipeName>` | dpcc.admin | Set recipe ingredients (opens recipe item GUI) | `/dpcc recipeitem MagicItems FireWand` |
| `/dpcc setresultitem <categoryName> <recipeName>` | dpcc.admin | Set the recipe result item | `/dpcc setresultitem MagicItems FireWand` |
| `/dpcc setresultamount <categoryName> <recipeName> <amount>` | dpcc.admin | Set the recipe result amount | `/dpcc setresultamount MagicItems FireWand 3` |
| `/dpcc setresultweight <categoryName> <recipeName>` | dpcc.admin | Set the recipe result weight | `/dpcc setresultweight MagicItems FireWand` |
| `/dpcc opencategory <categoryName>` | None | Open the category inventory (recipe list GUI) | `/dpcc opencategory MagicItems` |
| `/dpcc reload` | dpcc.admin | Reload the config | `/dpcc reload` |

**❗Notes when using commands**

- Category names and recipe names support Korean and English, but **spaces are not allowed**  
- Most settings are handled through **in-game GUI** (ingredients / result setup)  
- `setresultitem` typically uses the **item you are holding** as the result item  
- Admin commands require **OP** status or the `dpcc.admin` permission  

---

<center><img src="https://i.postimg.cc/Z5ZH0fqL/api-integration.png" alt="api-integration"></center>

- No external API integrations are used

---

<center><a href="https://discord.gg/JnMCqkn2FX"><img src="https://i.postimg.cc/4xZPn8dC/discord.png" alt="discord"></a></center>

- https://discord.gg/JnMCqkn2FX  
- If you have any questions or issues, please contact your server administrator  
- Suggestions for new features or improvements are always welcome  

---

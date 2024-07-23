# Discord Community Enhancement Ideathon Submission

## Problem and Solution

### Enhance Security with Automated Link Detection

**Problem:**
Despite the server's security measures, such as requiring verified phone numbers for messaging, hacked accounts due to phishing can still send messages. Bots like Dyno and MEE6 block suspicious links, but they parse messages after they are published, causing confusion with unread messages.

**Solution:**
Implement regex-based automated moderation (automod) to filter messages containing suspicious links before they are published. The regex to be used: `(?:(?:https?://)?(?:www)?discord(?:app)?\.(?:(?:com|gg)/invite/[a-z0-9-_]+)|(?:https?://)?(?:www)?discord\.gg/[a-z0-9-_]+)`.
- **Prevents phishing attempts** by blocking malicious links before they appear in the chat.
- **Reduces confusion** caused by unread messages flagged by bots like Dyno and MEE6.
- **Enhances overall server security** and user trust.
- **Add Custom Blocked Words**, we can easily block cuss words using AutoMod

### Nitro Boost Incentives

**Problem:**
Despite having 65k+ members, the server only has 14 Nitro boosts :((

**Solution:**
Encourage Nitro boosts by offering incentives such as entry into a lucky draw with cash prizes or exclusive swag or maybe a role like PowerStackie(if they are also helping out others).
- **Increases the number of Nitro boosts.**
- **Builds community engagement** through exciting and rewarding activities.
- **Enhances server growth and development** with boosted capabilities.

### Regular Game Nights and Tournaments

**Problem:**
Quiz and game nights are infrequent, reducing engagement and interaction among server members.

**Solution:**
Host weekly game nights and monthly tournaments for popular games like chess and Gartic. Award points and prizes to winners.
- **Promotes community bonding** and interaction.
- **Increases server activity** and member retention.
- **Provides fun and engaging events** for all members.

### Quiz Night Enhancements with Digital Rewards

**Problem:**
Quiz nights attract limited participation, and there's a need for more incentives to encourage broader engagement.

**Solution:**
Offer NFTs or Credly badges as rewards for monthly quiz winners to attract more participants.
- **Encourages participation** by offering unique, collectible rewards.
- **Recognizes and celebrates top performers** publicly.
- **Adds a competitive edge** to quiz nights, making them more exciting.

### RAG based Discord Bot for Common Queries

**Problem:**
Users often have common queries that could be handled by a bot, reducing the load on moderators and improving response times.

**Solution:**
Develop a custom Discord bot to assist users with common queries, inspired by existing solutions like RAG: https://stackupchatbot.streamlit.app/.
- **Provides immediate assistance** to users when moderators are unavailable.
- **May Reduce the number of support tickets** on Zendesk.
- **Improves user experience** by offering quick and accurate responses.

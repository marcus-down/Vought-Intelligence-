# 🧠 Vought Intelligence

**Vought Intelligence** is an advanced artificial intelligence platform designed to manage, protect, and enhance Discord communities. Developed with high-performance infrastructure using Discord.js v14 and PostgreSQL, it delivers powerful moderation systems, automated community tools, and scalable engagement features.

Engineered with the precision expected from Vought International, this system provides a unified digital intelligence capable of maintaining order, improving interaction, and supporting large-scale Discord environments.

---

# 📚 Table of Contents

- Features Overview
- Quick Setup
- Manual Installation
- Database System
- Architecture
- Contributing

---

# 🌟 Core Systems

Vought Intelligence integrates multiple operational systems into a single intelligent framework designed for community stability and growth.

## 🛡 Governance & Moderation

Maintain order and enforce server policies through intelligent moderation tools.

- Mass ban and kick capabilities  
- Moderation case tracking  
- Persistent user notes  
- Administrative action history  

## 💰 Economy Infrastructure

Create engaging community economies with automated systems.

- Server shop and inventory system  
- Gambling mechanics  
- Peer-to-peer currency transfers  
- User balance tracking  

## 🎮 Engagement Systems

Increase user interaction with entertainment utilities.

- Random fact generator  
- Wanted poster image creator  
- Text transformation tools  

## 🎫 Support Ticket Network

Advanced ticket management designed for staff workflows.

- Ticket claiming system  
- Priority management  
- Transcript storage  
- Ticket spam prevention  

## 🔢 Server Intelligence Counters

Real-time server statistics displayed dynamically.

- Member counters  
- Bot counters  
- Voice activity tracking  
- Automatic updates  

## 🎭 Reaction Role System

Allow users to configure their own roles through interaction.

- Emoji-based role assignment  
- Multi-role support  
- Self-service role management  

---

# 📊 Experience & Leveling System

Encourage participation through an automated XP system.

- Message-based XP tracking  
- Automatic level progression  
- Level reward roles  
- Fully customizable settings  

---

# 🎉 Event Management

Host large-scale server events with automated systems.

- Multi-winner giveaways  
- Automatic winner selection  
- Giveaway reroll tools  

---

# 🎂 Birthday Recognition

Ensure community milestones are celebrated.

- Birthday tracking system  
- Automatic celebration announcements  
- Timezone-aware scheduling  

---

# 🔧 Utility Tools

Provide practical features for everyday community use.

- Reporting system for staff review  
- Personal task management tools  
- Channel message navigation tools  

---

# 👋 Community Welcome System

Create a structured onboarding experience for new members.

- Automated welcome messages  
- Auto role assignment  
- Custom embed messages  

---

# 🚀 Quick Setup

For a full step-by-step guide, follow the setup tutorial:

YouTube Channel: https://www.youtube.com/@TouchDisc

---

# ⚙️ Manual Installation

## Prerequisites

- Node.js 18 or higher
- PostgreSQL server (recommended)
- Discord bot application with required intents

---

## 1. Clone the Repository

```bash
git clone https://github.com/yourusername/TitanBot.git
cd TitanBot
```

---

## 2. Install Dependencies

```bash
npm install
```

---

## 3. Configure Environment Variables

Copy the example environment file:

```bash
cp .env.example .env
```

Edit `.env` with your bot credentials.

```env
DISCORD_TOKEN=your_discord_bot_token
CLIENT_ID=your_client_id
GUILD_ID=your_server_id

POSTGRES_URL=postgresql://postgres:password@localhost:5432/titanbot
POSTGRES_HOST=localhost
POSTGRES_PORT=5432
POSTGRES_DB=titanbot
POSTGRES_USER=postgres
POSTGRES_PASSWORD=password
```

---

## 4. Setup PostgreSQL Database (Optional but Recommended)

```bash
createdb titanbot
createuser titanbot
psql -c "ALTER USER titanbot PASSWORD 'password';"
psql -c "GRANT ALL PRIVILEGES ON DATABASE titanbot TO titanbot;"
```

---

## 5. Test Database Connection

```bash
npm run test-postgres
```

---

## 6. Start the Bot

```bash
npm start
```

---

# 🗄 Database System

Vought Intelligence uses PostgreSQL as its primary database with an intelligent fallback system.

## PostgreSQL Features

- Reliable transaction support  
- High performance query handling  
- Persistent data storage  
- Scalable infrastructure  
- Automatic schema generation  
- Connection pooling  

## Fallback System

If PostgreSQL becomes unavailable, the system automatically switches to memory storage.

- Temporary in-memory data storage  
- Automatic recovery when database reconnects  
- Zero downtime operation  

---

# 🏗 Architecture

## Technology Stack

- Discord.js v14  
- Node.js 18+  
- PostgreSQL  
- Express.js  
- Winston logging system  
- Node-cron scheduled tasks  

---

# 🔐 Required Bot Permissions

The bot requires the following permissions:

- View Channels  
- Send Messages  
- Embed Links  
- Attach Files  
- Read Message History  
- Manage Messages  
- Manage Channels  
- Manage Roles  
- Kick Members  
- Ban Members  
- Moderate Members  
- Connect  

---

# 🤝 Contributing

Contributions help expand the capabilities of Vought Intelligence.

1. Fork the repository  
2. Create a feature branch  
3. Implement your changes  
4. Test thoroughly  
5. Submit a pull request  

Development guidelines:

- Follow existing code style  
- Include error handling  
- Document new features  
- Test with PostgreSQL and memory storage  

---

# 📜 License

Released under the MIT License.

---

# 💌 Acknowledgment

Thank you for deploying **Vought Intelligence** to power your community infrastructure.

Efficient communities require intelligent systems.

# EngageNet 📱

**EngageNet** is a simplified social media engagement database system that simulates the interaction and experience of a typical content-sharing platform. It captures various user actions—like posting, liking ❤️, commenting 💬, saving 📌, sharing 🔁, and reporting 🚩—across the platform.

---

## 🔍 Overview

This platform helps explore how users engage with posts and how administrators can track activity. From users uploading photos and writing captions to viewers liking, sharing, saving, or reporting posts, **EngageNet** provides a holistic view of content engagement.

---

## ✨ Key Features

* 📝 **User Profiles**: Create a digital identity with a name, bio, contact, and signup details.
* 📸 **Post Creation**: Upload posts with captions, locations, and background music.
* ❤️ **Likes**: Appreciate content with heart ❤️ reactions.
* 💬 **Comments**: Express thoughts and interact under posts.
* 📌 **Saves**: Bookmark favorite posts for later.
* 🔁 **Shares**: Spread great content across the network.
* 🚩 **Reports**: Flag inappropriate content for admin review.
* 🛡️ **Admin Controls**: Designated admins monitor and handle reported posts.
* 👥 **Followers System**: Connect with others through following.

---

## 💡 Use Cases (Queries)

Here are some interesting questions you can answer using EngageNet:

1. **Top 3 Influential Users**

> *Who are the most popular users based on total engagement (likes ❤️ + shares 🔁 + saves 📌 + comments 💬)?*

2. **Silent Interactors**

> *Which users only comment 💬 but never like ❤️, save 📌, or share 🔁 posts?*

3. **Most Reported Users**

> *Who are the top 5 users whose posts got reported 🚩 the most?*

4. **Users with Most Saved Posts**

> *Which users consistently create content that others love to save 📌?*

5. **Commenters Who Spark Conversations**

> *Which comments receive the highest number of replies?*

6. **Admin-User Action Map**

> *Which admin handles moderation for which user and post?*

---

## 🗂️ Project Structure

```bash
EngageNet/
├── EngageNet_DDL_script.sql         # Table creation scripts
├── EngageNet_insert_data.txt        # Sample data for the tables
├── EngageNet_queries.sql            # Useful SQL queries and use cases
├── EngageNet_BCNF_proof.pdf         # BCNF normalization proof
├── EngageNet_ER_diagram.pdf         # Entity-Relationship diagram
├── EngageNet_relational_schema.pdf  # Visual representation of schema
```

---

## 🚀 Getting Started

To explore EngageNet, clone or download the repository and run the SQL scripts using any PostgreSQL-compatible database. You can view the schema in the PDFs and load sample data to test queries.

```bash
git clone https://github.com/thenakulpatel/EngageNet
cd EngageNet
```

You’re now ready to explore how social media platforms track engagement, user behavior, and content trends!

---

## 📬 Questions?

Feel free to raise issues on this repo or reach out if you want to expand EngageNet with more features!

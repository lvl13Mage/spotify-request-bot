---
sidebar_position: 1
---

# Chat Commands

spotify-request-bot provides a variety of chat commands to interact with Twitch and Spotify seamlessly. These commands allow streamers and their moderators to manage song requests, control the song queue, and interact with viewers in real time.

## Available Commands

### `!songqueue` (Aliases: `!sq`)
**Description**: Displays the current song queue.

- **Usage**: `!songqueue`
- **Response**: Lists the songs currently in the queue.
- **Example**:
  ```
  1️⃣ Artist 1 - Song 1 2️⃣ Artist 2 - Song 2
  ```

---

### `!lastsongs` (Aliases: `!ls`)
**Description**: Displays the last played songs.

- **Usage**: `!lastsongs`
- **Response**: Lists the most recently played songs.
- **Example**:
  ```
  1️⃣ Artist 1 - Song 1 2️⃣ Artist 2 - Song 2
  ```

---

### `!currentsong` (Aliases: `!cs`)
**Description**: Displays the currently playing song.

- **Usage**: `!currentsong`
- **Response**: Shows the artist and title of the song currently playing.
- **Example**:
  ```
  🎵 Now Playing: Artist - Song Title
  ```

---

### `!findsong` (Aliases: `!searchsong`, `!fs`)
**Description**: Searches for a song on Spotify.
:::warning
**(Not implemented yet)**
:::

- **Usage**: `!findsong <song name>`
- **Response**: Searches Spotify for the specified song and displays the result.
- **Example**:
  ```
  🔍 Found: Artist - Song Title
  ```

---

### `!skip`
**Description**: Skips the currently playing song.
**Permission**: Moderators only.

- **Usage**: `!skip`
- **Response**: Skips the current song and moves to the next one in the queue.
- **Example**:
  ```
  ⏭ Song skipped.
  ```
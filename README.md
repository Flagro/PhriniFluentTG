# 🌍 PhriniFluent: Enhanced Telegram Quiz Bot 🌍

![PhriniFluent Logo](logo.png)

Welcome to **PhriniFluentTG** repository of **PhriniFluent**! Originally forked from [QuizBot](https://github.com/SWel1a/QuizBot), PhriniFluent takes the engaging quiz experience a step further. With the addition of a User Database, Word Libraries Database, and an integration with OpenAI for word library management and interactions generation, our bot promises a richer interaction. Dive in and challenge your intellect!

🔗 [PhriniFluent Main Project](https://github.com/Flagro/PhriniFluent)

🔗 Interact with the bot directly on Telegram: [@PhriniFluentBot](https://t.me/PhriniFluentBot)

## 🚀 Features:

- 🌐 **Multi-language Support**: From English to Spanish, and beyond!
- 🕐 **Timed Quizzes**: Set your pace with customizable intervals between questions.
- ✏️ **Add & Remove Words**: With an authorized access, mold the quiz database as you see fit.
- 📚 **List Words**: Explore the vocabulary across different languages.
- 🌍 **Change Bot Language**: Desire a chat in French? C'est bon!
- 📊 **User Database**: Track and manage user interactions and performance.
- 📖 **Word Libraries Database**: A dedicated database to hold the vast array of words.
- 🤖 **OpenAI Integration**: Enhanced word library management and dynamic interactions generation.

## 🎖 Getting Started:

**1. Dive Right In**:
Begin with `/start English 60` for an English quiz that throws questions every 60 seconds. Tweak as you wish!

**2. Answering**: 
Respond straight to the bot's queries. Encountered a brainteaser? Reply with `/idk`.

**3. Control**:
End your quiz session with `/stop` or skip to the subsequent question using `/quiz`.

**4. Modify Database**:
Those with the authorization can expand the database using `/add_word` or trim it with `/remove_word`.

**5. Play in Your Language**:
Alter the bot's language with `/language` and retrieve words with `/list`.

## 🖥️ Running the Project Locally:

### Installation & Setup:

```bash
git clone https://github.com/Flagro/PhriniFluent
cd PhriniFluent
mv .env-example .env
echo "TELEGRAM_TOKEN=<your telegram token>" >> .env
docker-compose up
```

Or you could use our ghcr image:
```bash
docker run -e TELEGRAM_TOKEN=YOUR_TELEGRAM_TOKEN -e ALLOWED_HANDLES=@handle1,@handle2,@handle3 ghcr.io/flagro/phrinifluenttg:main
```

🎉 Dive into the captivating world of quizzes directly in your Telegram chat. If queries arise or you seek assistance, our developer community is ever ready. Enjoy and happy quizzing! 🎉

## Чат с YaGPT

### Краткая информация
Данный YaGPT-бот использует следующие компоненты:
- [Yandex GPT](https://cloud.yandex.ru/services/yandexgpt)
- [Yandex GPT for Langchain](https://pypi.org/project/yandex-chain/)
- [Streamlit](https://streamlit.io/)
- [LangChain](https://python.langchain.com/)

### Структура репозитория и порядок работы с ботом
- в файле ``.env`` находятся системные переменные (которые при запуске в облаке можно указать как secrets)
```
YAGPT_FOLDER_ID = 
YAGPT_API_ID = 
YAGPT_API_KEY = 
```
- файл `requirements.txt` традиционно содержит в себе список необходимых для работы программы модулей, которые устанавливаются командой 
```pip install -r requirements.txt ```
- в папке `images` хранится логотип компании, который можно использовать в графическом интерфейсе streamlit
- `YaGPT-Chat.py` запускаемый файл `streamlit run YaGPT-Chat.py`

### Запуск в Streamlit Community Cloud
Вы можете развернуть данное приложение через Streamlit Community Cloud, следуя [инструкциям](https://docs.streamlit.io/streamlit-community-cloud/get-started)


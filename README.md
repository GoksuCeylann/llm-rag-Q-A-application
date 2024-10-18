# LLM Q&A Application

## Setup

1. Aşağıdaki komutlar ile virtual environment oluşturun ve kütüphaneleri yükleyin:

requirements.txt'de son satırı yoruma aldım. Önce bu şekilde yükleyin ve daha sonra o yorum sembölünü silip tekrar yükleyin. Sıralı olması lazım yoksa kurulumda hata alınıyor.

```bash
$ python3 -m venv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```

2. Eğer API üzerinden kullanacaksanız: (GPT)

`.env` dosyasındaki değeri kendi API anahtarınızla doldurun:

```bash
OPENAI_API_KEY = [ENTER YOUR OPENAI API KEY HERE]
```

Local modeller içinse Ollama kullanabilirsiniz. Ben burada örnek olarak llama3:8b kullandım.

3. Kullanacağınız pdfleri proje klasörünün içine atın. Sonrasında local.ipynb'yi sırayla çalıştırabilirsiniz. (Path'leri eklemeyi unutmayın.)

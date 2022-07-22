https://cloud.google.com/pubsub/docs/publish-receive-messages-client-library

- Criar projeto, servico e chave

- Instalar modulos python
```
pip install --upgrade google-cloud-pubsub
```

- Terminal 1: publique uma mensagem, ex.:
```
export GOOGLE_APPLICATION_CREDENTIALS=/Users/iuri.malinoski/projects/gcp-pubsub-tests/key.json
python publisher.py
```

- Terminal 2: receba a mensagem (listening)

```
export GOOGLE_APPLICATION_CREDENTIALS=/Users/iuri.malinoski/projects/gcp-pubsub-tests/key.json
python subscriber.py
```

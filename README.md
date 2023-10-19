# model-ia-comments
This is a fake REST API to serve models IA and inputs

## Getting started

Install JSON Server 

```
npm install -g json-server
```

Start JSON Server

```bash
json-server --watch db.json
```

Now if you go to [http://localhost:3000/model-comments](http://localhost:3000/model-comments), you'll get

```json
{
  "text": "The item exceeded my expectations",
  "label": "positive review"
}
```

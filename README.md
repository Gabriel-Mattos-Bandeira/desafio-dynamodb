# desafio-dynamodb

```
{
    "Music": [
        {
            "PutRequest": {
                "Item": {
                  "Artist": {"S": "Roberto Carlos"},
                  "SongTitle": {"S": "Emoções"},
                  "AlbumTitle": {"S": "Roberto Carlos em Jerusalém"},
                  "SongYear": {"S": "2012"}
                }
            }
        },
        {
            "PutRequest": {
                "Item": {
                  "Artist": {"S": "Roberto Carlos"},
                  "SongTitle": {"S": "Eu sou Terrível"},
                  "AlbumTitle": {"S": "Roberto Carlos em Ritmo de Aventura"},
                  "SongYear": {"S": "1967"}
                }
            }
        },
        {
            "PutRequest": {
                "Item": {
                  "Artist": {"S": "Roberto Carlos"},
                  "SongTitle": {"S": "Jesus Cristo"},
                  "AlbumTitle": {"S": "Acústico MTV: Roberto Carlos"},
                  "SongYear": {"S": "2001"}
                }
            }
        }
      ]
}

```

```
{
  "Artist": {"S": "Roberto Carlos"},
  "SongTitle": {"S": "É Preciso Saber Viver"},
  "AlbumTitle": {"S": "Acústico MTV: Roberto Carlos"},
  "SongYear": {"S": "2001"}
}

```

```
{
    ":artist":{"S":"Roberto Carlos"},
    ":title":{"S":"Eu sou Terrível"}
}

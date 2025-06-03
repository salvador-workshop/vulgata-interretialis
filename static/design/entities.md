# entities

## VulgataInterretialis

| property | type | desc |
| --- | --- | --- |
| id | str | Alphanumeric ID |
| title | str | Title |
| subtitle | str | Subtitle |
| tags | list | List of tags (str) |
| books | list | List of VIBook |
| num_books | int | Number of VIBook |

## VIBook

| property | type | desc |
| --- | --- | --- |
| id | str | Alphanumeric ID |
| title | str | Title |
| subtitle | str | Subtitle |
| tags | list | List of tags (str) |
| chapters | list | List of VIChapter |
| num_chapters | int | Number of VIChapter |

## VIChapter

| property | type | desc |
| --- | --- | --- |
| id | str | Alphanumeric ID |
| title | str | Title |
| subtitle | str | Subtitle |
| tags | list | List of tags (str) |
| verses | list | List of VIVerse |
| num_verses | int | Number of VIVerse |

## VIVerse

| property | type | desc |
| --- | --- | --- |
| id | str | Alphanumeric ID |
| title | str | Title |
| subtitle | str | Subtitle |
| tags | list | List of tags (str) |
| text | str | Text for this verse |

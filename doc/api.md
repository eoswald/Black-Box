# API

## Submit
### /api/submit
### POST
```javascript
{
    "lang": "<Language>",
    "code": "<Code>"
}
```
### Response
```javascript
{
    "success" : "<Boolean Success/Failure>"
}
```

## Search
### /api/search
### POST
```javascript
{
    "lang" : "<Language>",
    "terms" : "<String terms>",
    "page" : <Integer Optional>
}
```
### RESPONSE
```javascript
{
    "lang" : "<Language>",
    "code" : "<Code>",
    "rating" : <Rating Float>,
    "id" : "<Snippet ID>"
}
```
## Snippet
### /api/snippet
### POST
```javascript
{
    "id" : "<Snippet ID>"
}
```
### RESPONSE
```javascript
{
    "lang" : "<Language>",
    "code" : "<Code>",
    "rating" : <Rating Float>,
    "id" : "<Snippet ID>"
}
```
## Rate
### /api/rate
### POST
```javascript
{
    "id": "<Snippet ID>",
    "rating" : <Rating Float>
}
```
### RESPONSE
```javascript
{
    "success": <Boolean Success/Failure>
}
```

# Songify REST API
This API works as a backend for the music streaming service Songify. The API allows anyone to get information and metadata about artists, albums, playlists and tracks.

The user must first obtain an API Key. An account is required for creating the API Key. You can get API Key for your account by visiting Developer Section of you account page.

The header must contain API Key. 
```
{
    X-API-KEY : xxYOUR_API_KEY_HERExx
}
```
This repo contains `JSON` and `YAML` files for the `Open API Specification 3.0.0`. 

You can view the API documentation here on [Swagger Hub](https://app.swaggerhub.com/apis/uragirii/Songify/1.0.2).

# API Structure
Any user can use the API. It's free to use. However a Rate-Limit has been imposed with max 5 requests per second or 250 requests per minute.

If you recieve `HTTP Code 429`. Please wait for sometime to send another request.

A user is considered an artist if he has uploaded atleast a sing track. Users and Artists share same routes.

Any one can upload a track, create a playlist, create an album.

For more details [visit here](https://app.swaggerhub.com/apis/uragirii/Songify/1.0.2)

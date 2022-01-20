# Urlshortener
I have developed this Url shortener using Spring MVC and Redis.
- Spring Boot 2.1.0 (Spring Web[MVC] + Spring Data Redis)
- Guava 18.0
- Common Validator 1.7

# URLs
- POST `/springboot/url` with body as `long_url_string` - For creating the short url from long url
- GET `/spring/url/{id}` - For retrieving the long URL from short `id`


JwtUtil class plays a crucial role in handling JWT operations like generating, validating, 
and extracting information from tokens.

The JwtRequestFilter class is a custom filter that intercepts incoming HTTP requests 
and processes the JWT token to authenticate the user. 
It extends the OncePerRequestFilter class to ensure that the filter is executed once per request.
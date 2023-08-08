# Claims-Based Authentication:
is an approach to managing user authentication and authorization in a more flexible and extensible manner.
In this authentication model, a user's identity and the associated permissions or attributes are represented as claims. 
-hese claims are usually presented in a security token like JSON Web Tokens (JWTs) or Security Assertion Markup Language (SAML) tokens.
These tokens are then used to verify the user's identity and permissions across different services and applications.

# JWT Authentication:

JWT stands for JSON Web Token. It's a compact and self-contained way to represent claims between two parties, commonly used for authentication and information exchange. A JWT consists of three parts: a header, a payload, and a signature. The header typically contains metadata about the token, such as the algorithm used for signing it.
The payload contains the claims, which are statements about an entity (typically the user) and additional data.

- JWT authentication works in the following way:

1. Authentication: When a user logs in or authenticates, the server generates a JWT containing relevant claims.
2. Token Issuance: The server signs the JWT using a secret key or private key, creating a signature that can be later used for verification.
3. Token Presentation: The JWT is then provided to the user, usually as a response to their login request.
4. Token Usage: The user includes the JWT in the headers of their subsequent requests to protected resources or services.
5. Validation: The server receiving the token can verify its integrity by checking the signature. It can also decode the claims within the payload to determine the user's identity and permissions.

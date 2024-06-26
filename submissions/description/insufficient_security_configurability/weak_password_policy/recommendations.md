# Recommendation(s)

The password policy should be sufficiently robust and contain the following guidelines for users:

- Have a minimum password length of eight characters and no maximum limit
- Require at least three different character types such as, upper and lower case letters, numbers, and special characters.
- Have a deny list of commonly used words and poor passwords such as, `password`, `password123`, the company’s name, or a user’s email address or username.
- When a user resets their password, they should not be able to use a previous password or increment a previous password in any way. For example, a user should not be able to change their password from `Correct-h0rse-1` to `Correct-h0rse-2`

Additionally, implementation of Multi-Factor Authentication (MFA) should be considered to provide an extra layer of security.

For more information refer to the following guide relating to this vulnerability:
<https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-63b.pdf>

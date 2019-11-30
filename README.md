# This repository contains tests of http://tutorialsninja.com/demo/ website.

All tests are written using PyTest framework, also tests includes custom info logging about every step.

Tests are run by PyTest automatically (to run just enter /tests folder and type in terminal: pytest)

# At current state following tests are available:

- Login - success
- Login - failed (no user/pwd not match)
- Login - forgotten password
- Password change
- Register
- Register - checkbox missing
- Search test (success + failed in one test)
- Checkout
- Return ordered product
- Add to wishlist - success
- Add to wishlist - failed, you have to be logged in
- Add to basket
- Add to basket - reorder previously ordered product
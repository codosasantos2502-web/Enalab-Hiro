# In this document, I will explain why we need to perform automated tests instead of manual ones.

### Apparently, manually performed tests are more likely to cause errors in systems, so the Testing Pyramid system is used, which divides the tests into three parts. The first part involves testing the code (most of it), which is fast and automated. The second part is the API test, which is not as fast but is faster than the E2E test, which is also automated. Finally, the E2E test, which is the slowest and is performed on the interface, or UI, and is done entirely manually. All of this is divided to prevent the system from having other errors (if it already has them) or creating one that complicates things for the developers.

#

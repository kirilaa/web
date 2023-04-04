# web
Personal web-site of 


Consumer Domain            Provider Domain 1            Provider Domain 2

     |                             |                             |
     | 1. Service announced       |                             |
     |---------------------------->|                             |
     |                             | 2. Announce received        |
     |                             |---------------------------->|
     |                             | 3. Bid offer sent to consumer
     |                             |<----------------------------|
     | 4. Winner choosen          |                             |
     |<----------------------------|                             |
     | 5. Winner announcement     |                             |
     |---------------------------->|                             |
     |                             | 6. Deployed federated service
     |                             |---------------------------->|
     | 7. Connection details sent |                             |
     |<----------------------------|                             |
     | 8. E2E Service running      |                             |
     |<---------------------------->|                             |
     |                             |                             |
     | ...                         | ...                         |
     |                             | ...                         |
     |                             |                             |
     | 9. Service stopped         |                             |
     |---------------------------->|                             |
     |                             |                             |
     | ...                         | ...                         |
     |                             | ...                         |
     |                             |                             |
     | 10. Federated service fails|                             |
     |<----------------------------|                             |
     | 11. New federation         |                             |
     |---------------------------->|                             |
     |                             | 12. Announce received       |
     |                             |---------------------------->|
     |                             | 13. Bid offer sent to consumer
     |                             |<----------------------------|
     | 14. Winner choosen         |                             |
     |<----------------------------|                             |
     | 15. Winner announcement    |                             |
     |---------------------------->|                             |
     |                             | 16. Deployed federated service
     |                             |---------------------------->|
     | 17. Connection details sent|                             |
     |<----------------------------|                             |
     | 18. E2E Service running     |                             |
     |<---------------------------->|                             |
     |                             |                             |
     | ...                         | ...                         |
     |                             | ...                         |
     |                             |                             |
     | 19. Service stopped        |                             |
     |---------------------------->|                             |

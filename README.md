# DeepFace Redis Technology Stack

## About this Project

Proof of concept of using DeepFace API with Redis key-pair storage for sub-millisecond facial recognition queries

## Built With

- Docker
- Redis
- DeepFace

## Getting Started

The demo has been containerized so run the following command to spin up the API + Redis:

```sh
sudo docker-compose up
```

Functions from the `test.ipynb` notebook can be ran regularly to interface with Redis server/

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

## References
- [DeepFace with Redis](https://sefiks.com/2021/03/02/deep-face-recognition-with-redis/)
- [DeepFace Tech Stack Recommendation](https://sefiks.com/2021/03/31/tech-stack-recommendations-for-face-recognition/)

# agent-anthropic
Build AI Agent using Anthropic


### Developer

#### Install Dependencies
- Run Python in virtual env
- Libraries required:
    `anthropic` for Anthropic API , 
    `python-dotenv` for reading environment variable, 

### Sample output from reading an image:
```json
Message(id='msg_017GoewXCwVPpqdCU6CDHj7c', content=[TextBlock(citations=None, text="This is an artistic representation of Krishna and Radha, two central figures in Hinduism. The image shows Krishna (depicted with blue skin) playing his iconic flute, wearing a peacock-feathered crown (mukut), and ornate jewelry. Beside him is Radha in a pink/magenta sari with gold embellishments.\n\nThe setting is typical of Krishna artwork, featuring:\n- Lotus flowers and lily pads in water\n- Vibrant colorful flowers\n- Lush green background\n- Decorative elements typical of Indian artistic style\n\nThis divine couple represents the eternal love between God and devotee in Hindu theology. Krishna is considered the eighth avatar (incarnation) of Lord Vishnu, while Radha represents the supreme feminine divine energy. Their relationship is often interpreted both literally and allegorically in Hindu philosophy and devotional traditions, particularly in the Bhakti movement.\n\nThe artistic style is contemporary devotional art (likely digital), though it draws from traditional Indian artistic conventions. Such images are commonly used in homes, temples, and during festivals like Janmashtami (Krishna's birthday celebration).\n\nThe flute-playing Krishna with Radha is one of the most popular themes in Hindu devotional art, representing divine love, harmony, and the spiritual connection between the divine and the devotee. This particular composition emphasizes the romantic and pastoral aspects of their relationship, which is characteristic of the Krishna-Radha iconography.", type='text')], model='claude-3-5-sonnet-20241022', role='assistant', stop_reason='end_turn', stop_sequence=None, type='message', usage=Usage(cache_creation_input_tokens=0, cache_read_input_tokens=0, input_tokens=935, output_tokens=314))
```
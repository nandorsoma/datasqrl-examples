# DataSQRL Use Cases and Examples

This is a repository for real world DataSQRL use cases and examples.

* **[Clickstream Recommendation](clickstream-recommendation/)**: Build a personalized recommendation engine based on clickstream data and vector content embeddings generated by an LLM.

You can find additional examples in the [DataSQRL repository](https://github.com/DataSQRL/sqrl).

## Using Python in examples

Some of our examples require python to generate their test data or to ingest them to Kafka.

It is recommended to use virtualenv to manage your python environment. Some IDEs require to place requirements.txt
and venv folder in the project root. That's why it is in the root, even though not all "modules" are utilizing it.

Here's how to use venv in this project:

- Create a virtual env in the project root folder: `python3 -m venv venv`
- Install dependencies: `pip install requirements.txt` 
- Activate env `source venv/bin/activate`
  - *you can deactivate it with this command:* `deactivate`

# langchain-zero-shot-JSON
Created by: brbernas\
Creation date: 10-15-23\
IDE: VSCode, Jupyter\
Chat/LLM: ChatOpenAI

Rationale:  Use 100% JSON inputs & outputs to create Etsy titles for niche t-shirt designs.

Performance summary: Zero-shot Langchain code that reads-in a JSON API token, a JSON zero-shot chat template & JSON inputs.\
This model accepts two inputs, calls the ChatOpenAI API, and sends back one output.\
After chat processing, output results are written to a JSON file.

To customize:
1. Copy files to a common directory.
2. In your JSON/IDE editor:
   - load 'OPENAI_API_KEY.JSON' > apply OpenAI API key > save & close
   - load 'langchain_chatAPI_zero_shot_JSON_method_gh' > set file_folder variable > save & close
   - load 'title_zero_shot_prompt.json' > customize "template" statement > save & close
   - load 'zero_shot_prompt_input.json' > customize JSON inputs > save and close
   - output file should be overwritten when notebook is run
3. Load notebook and run all cells in order.
4. View output to check chat completion.

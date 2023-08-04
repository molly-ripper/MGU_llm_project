All question (.jsonl) files, and the answer file directory (model_answer), go in the following path:
/FastChat/fastchat/llm_judge/data/mt_bench/

I included gen_model_answer.py (/FastChat/fastchat/llm_judge/) since I changed the file contents (I added a --question-file argument to make running it easier).

runfs.sh contains the code to run FastChat models.

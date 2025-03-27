ollama qwen2.5:14b-instruct-q4_K_M parallel=1, time = 25 минут
ollama qwen2.5:14b-instruct-q4_K_M parallel=4, time = 10 минут
ollama qwen2.5:14b-instruct-q4_K_M parallel=16, time = 25 минут


dl-002 tensor parallel 2 Qwen2.5-32B-Instruct-AWQ

parallel: 1 
(token/s): 25
10/933 [05:35<7:49:16, 30.51s/it

parallel: 4
(token/s): 88.25
10/933 [01:58<2:20:37,  9.14s/it

parallel: 8
(token/s): 175.68
14/933 [02:00<2:11:47,  8.60s/it


parallel: 16
(token/s): 330
18/918 [01:53<1:10:19,  4.69s/it

parallel: 32
(token/s): 330
65/933 [05:01<42:48,  2.96s/it


dl-002 tensor parallel 2 Qwen2.5-72B-Instruct-AWQ
parallel: 16
(token/s): 18
2/13995 [05:36<682:47:39, 175.66s/it (зависло)

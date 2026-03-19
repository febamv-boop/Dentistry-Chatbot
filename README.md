1. Data Dictionary (Schema):

         Column           Type     Description
         question         str      Contains possible queries
         answer           str      Contains descriptive answer to the question
         short_answer     str      Contains concise answer to the question
   
2. JSON sample
     {
    "question":     "zirconium dental implants. how common is it used now. is there any advantages or benefits over titanium implants. cons & pros please. thanks.",
    "short_answer": "\nDental implants\n",
    "answer": "a majority of the dental implants placed are titanium. they are highly successful with many years use ; many studies much lower in cost ;
               have many restorative options. zirconia implants are newer fewer studies on success lesser restorative options.
               however they can be more aesthetic in certain anterior(front) situations. let your dentist/oral surgeon chose what they feel will be best for you."}
   
4. Link to find JSON file:
          https://drive.google.com/drive/folders/1sO-XMqXPfdI6lIwN8WY7GIcXdTk9CQ2w

5. Library Requirements:
           pandas
           json
           os
           numpy
           faiss
           torch
           sentence_transformers
           sklearn
           google.generativeai

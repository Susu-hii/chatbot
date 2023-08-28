# chatbot
Generative Question Answering with loaded documents

# [packages]
streamlit = "*"
langchain = "*"
llama-cpp-python = "*"
chromadb = "*"


# LLaMa download

In order to download the model weights and tokenizers, please visit the Meta AI website and accept our License.

Once your request is approved, you will receive a signed URL over email. Then run the download.sh script, passing the URL provided when prompted to start the download. Make sure that you copy the URL text itself, do not use the 'Copy link address' option when you right click the URL. If the copied URL text starts with: https://download.llamameta.net, you copied it correctly. If the copied URL text starts with: https://l.facebook.com, you copied it the wrong way.

Pre-requisites: make sure you have wget and md5sum installed. Then to run the script: bash download.sh.

Keep in mind that the links expire after 24 hours and a certain amount of downloads. If you start seeing errors such as 403: Forbidden, you can always re-request a link.

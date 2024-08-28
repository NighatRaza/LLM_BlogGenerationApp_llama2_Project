****Blog Generation App****

This project is a Blog Generation App built using the **Llama 2 model**, designed to generate customized blog content. The app provides a user-friendly interface via **Streamlit**, enabling users to create blogs tailored to specific audiences.

**Features**

Topic Input: Specify the topic of your blog.

Word Count: Define the desired length of the blog in terms of word count.

Audience Perspective: Choose the perspective for the blog from a dropdown menu:
- Data Scientist
- Researcher
- Common People

**Technology Stack:**
- Model: Llama 2, deployed locally on CPU. Downloaded from open source hugging face community.
- Frontend: Streamlit for a responsive and interactive user interface.
- Backend: Powered by Python libraries and frameworks for seamless processing.

- Installation: To run this project locally, clone the repository and install the required dependencies.

- Usage: After installing the dependencies, you can start the app using Streamlit => streamlit run app.py

Enter your blog's topic, choose the word count, and select the target audience's perspective to generate a blog post.

**Requirements**
The following Python packages are required to run the app:

- sentence-transformers
- uvicorn
- ctransformers
- langchain
- python-box
- streamlit


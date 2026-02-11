# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

#### Name - Rakshitha P
#### Reg. No. - 212223220083

## AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:

You are part of an educational content team that delivers concise summaries of technical topics to undergraduate students.
The task is to summarize a technical article on Cloud Computing Fundamentals using multiple AI platforms and prompting strategies.


## Platforms Evaluated:
### ChatGPT 
### Gemini (Google) 
### Claude (Anthropic) 
### Copilot (Microsoft) 


## ChatGPT:
### 1. Zero-Shot Prompting 
#### Prompt: 
```
"Summarize the following article." 
```
#### Summary: 
Cloud computing allows users to access computing resources such as servers, storage, and applications through the internet instead of local hardware. It provides scalability, flexibility, and cost efficiency by enabling on-demand resource usage. Cloud computing is widely adopted across industries for data storage, application hosting, and collaboration.
### 2. Few-Shot Prompting 
#### Prompt: 
```
"Here are examples of summaries for technical articles.
[Provide 2–3 examples.]
Now, summarize the following article."

```
#### Summary: 
Cloud computing delivers computing services over the internet, eliminating the need for physical infrastructure. It supports flexible scaling and includes service models such as IaaS, PaaS, and SaaS. Organizations use cloud technology to improve efficiency, reduce costs, and enable remote access to data and applications. 

### 3. Chain-of-Thought Prompting 
#### Prompt: 
```
"Let's think step-by-step.
First, explain what cloud computing is,
then summarize its benefits and applications." 
```
#### Summary: 
Cloud computing works by hosting computing resources in remote data centers that users can access via the internet. Instead of maintaining physical servers, organizations rely on cloud providers for storage, processing power, and software services. Its key benefits include scalability, cost reduction, improved performance, and global accessibility. 

### 4. Role-Based Prompting 
#### Prompt: 
```
"You are a technology instructor explaining to first-year students.
Summarize the article in simple terms."
```
#### Summary: 
Cloud computing is like renting computer services online instead of buying and maintaining your own machines. Data and applications are stored on remote servers and can be accessed from anywhere. This helps businesses and individuals save money and work more efficiently.

## Gemini (Google) 
### 1. Zero-Shot Prompting 
#### Prompt: 
```
"Summarize the following article."
```
#### Summary: 
Cloud computing is a modern computing model that provides access to shared computing resources such as servers, storage, databases, networking, and software over the internet. Instead of purchasing and maintaining physical infrastructure, users can access these resources on demand from cloud service providers. This approach offers flexibility, scalability, and cost efficiency, allowing organizations to pay only for the resources they use. Cloud computing supports various deployment models, including public, private, and hybrid clouds, and is widely used in industries such as education, healthcare, finance, and e-commerce to improve productivity and operational efficiency.
### 2. Few-Shot Prompting 
#### Prompt: 
```
"Here are examples of summaries for technical articles. [Provide 2–3 examples.] Now, summarize the following article."
```
#### Summary: 
Cloud computing delivers computing services through the internet, removing the dependency on local hardware and infrastructure. It enables organizations to scale resources dynamically and manage workloads efficiently. The primary service models—Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS)—offer varying levels of control and responsibility. Cloud computing enhances collaboration, supports remote access, and accelerates innovation across multiple sectors.
### 3. Chain-of-Thought Prompting 
#### Prompt: 
```
"Let's think step-by-step. First, explain how cloud computing works, then summarize its key applications."
```
#### Summary: 
Cloud computing operates by hosting computing resources in large-scale data centers managed by cloud service providers. Users connect to these resources via the internet instead of relying on local machines. When a user requests a service, the cloud system allocates resources dynamically based on demand. This model ensures efficient resource utilization, scalability, and reliability. The benefits of cloud computing include reduced infrastructure costs, improved performance, automatic updates, and enhanced security. Real-world applications include cloud storage services, online collaboration tools, web hosting, big data analytics, and disaster recovery solutions.

### 4. Role-Based Prompting 
#### Prompt: 
```
"You are an expert educator explaining cloud computing to undergraduate students.
Summarize the article in clear and simple language."
```
#### Summary: 
Cloud computing means using computing services over the internet instead of running everything on your own computer or server. Companies store data and run applications on remote servers provided by cloud companies. This makes it easy to access information from anywhere, reduces hardware costs, and allows systems to grow as needed. Popular cloud platforms such as Google Cloud, AWS, and Microsoft Azure help organizations build, store, and manage applications efficiently.

##  Claude  
### 1. Zero-Shot Prompting 
#### Prompt:
```
"Summarize the following article."
```
#### Summary: 
Cloud computing is a technology that enables users to access computing services such as storage, servers, databases, networking, and software applications through the internet. Instead of maintaining physical infrastructure, organizations rely on remote data centers operated by cloud providers. This system ensures flexibility, scalability, and cost-effectiveness. Cloud computing supports multiple deployment models including public, private, and hybrid clouds. It has transformed industries by enabling remote collaboration, efficient data management, and improved system reliability.
### 2. Few-Shot Prompting 
#### Prompt: 
```
"Here are examples of summaries for technical articles. [Provide 2–3 examples.] Now, summarize the following article."
```
#### Summary: 
Cloud computing provides on-demand access to shared computing resources over the internet. It eliminates the need for organizations to invest heavily in hardware infrastructure. Through service models such as IaaS, PaaS, and SaaS, users can select services based on their needs. The technology enhances operational efficiency, supports global accessibility, and enables businesses to innovate rapidly. Its scalability and automated maintenance features make it a preferred solution across sectors.
### 3. Chain-of-Thought Prompting 
#### Prompt: 
```
"Let's think step-by-step. First, explain how cloud computing works, then summarize its key applications."
```
#### Summary: 
Cloud computing works by hosting computing resources in centralized data centers that are accessible through the internet. When a user requests a service, the cloud provider allocates virtual resources dynamically. This ensures optimal resource usage and performance. The main advantages include reduced infrastructure costs, scalability, automatic updates, enhanced security, and high availability. Applications of cloud computing include online storage systems, enterprise software delivery, web hosting, data analytics, machine learning platforms, and disaster recovery systems.
### 4. Role-Based Prompting 
#### Prompt: 
```
"You are a professional content curator for students. Summarize the article in simple terms."
```
#### Summary: 
Cloud computing means using computer services through the internet instead of owning physical machines. Companies store their data and run their applications on powerful remote servers managed by cloud providers. This allows them to access information anytime and from anywhere. It saves money, reduces maintenance effort, and helps systems grow easily when demand increases.
## Copilot  
### 1. Zero-Shot Prompting 
#### Prompt: 
```
"Summarize the following article."
```
#### Summary: 
Cloud computing is a model that provides computing resources over the internet. It allows users to access storage, servers, and applications without maintaining local infrastructure. This approach reduces costs and increases flexibility.
#### Prompt: 
```
"Here are examples of summaries for technical articles. [Provide 2–3 examples.] Now, summarize the following article."
``` 
#### Summary: 
Cloud computing delivers on-demand computing services using internet-based infrastructure. It provides scalable and flexible solutions through service models like IaaS, PaaS, and SaaS. Organizations benefit from reduced hardware costs, improved collaboration, and enhanced operational efficiency.
### 3. Chain-of-Thought Prompting 
#### Prompt: 
```
"Let's think step-by-step. First, explain how blockchain works, then summarize its key applications."
```
#### Summary: 
Cloud computing operates by storing data and applications in remote servers managed by service providers. Users connect through the internet to access these services. This system ensures scalability and efficient resource allocation. Its benefits include cost reduction, flexibility, global access, and improved reliability. It is widely used for data storage, application development, and enterprise management systems.
### 4. Role-Based Prompting 
#### Prompt: 
```
"You are a professional content curator for students. Summarize the article in simple terms"
```
#### Summary: 
Cloud computing is like using online services instead of storing everything on your own computer. Your files and applications are kept on powerful remote computers, and you can access them anytime through the internet. It helps businesses save money and work more efficiently.

## Observations:
### ChatGPT
#### Accuracy: High 
- Captures key concepts like decentralization, immutability, and applications beyond cryptocurrency. 
#### Coherence: Very High 
- Well-structured and logically flows from explanation to examples; suitable for student comprehension. 
#### Simplicity: Excellent 
- Uses relatable metaphors (e.g., digital notebook), making technical terms digestible for undergrads. 
#### Speed: Fast 
- Returns a high-quality summary within seconds. 
#### User Experience: Excellent 
- Interface is user-friendly, and output feels tailored and polished for the educational context. 

### Gemini (Google) 
#### Accuracy: High 
- Covers fundamental aspects like block linking and security features; slight underemphasis on real-world use cases. 
#### Coherence: High 
- Flows well but occasionally feels more generic than student-tailored. 
#### Simplicity: Good 
- Clear language, though explanations may lack the creativity or analogies found in ChatGPT. 
#### Speed: Very Fast 
- Delivers output nearly instantly. 
#### User Experience: Good 
- Efficient but lacks customization depth; output may feel “template-like” at times. 

### Claude (Anthropic) 
#### Accuracy: High 
- Includes all essential components: block structure, decentralization, real-world applications. 
#### Coherence: Very High 
- Summary reads smoothly and logically connects ideas for a student audience. 
#### Simplicity: Excellent 
- Uses analogies and clear language very effectively, second only to ChatGPT. 
#### Speed: Moderate to Fast 
- Slightly slower than Gemini or ChatGPT but still prompt. 
#### User Experience: Very Good 
- Friendly tone and human-like responses, though interface feels less refined than ChatGPT's. 

#### Copilot (Microsoft) 
#### Accuracy: Moderate to High 
- Hits basic points but can miss nuances or provide repetitive phrasing. 
#### Coherence: Moderate 
- The structure is serviceable, but transitions can feel mechanical. 
#### Simplicity: Good 
- Language is simple, but lacks depth or creative explanation. 
### Speed: Fast 
- Fast generation time, similar to ChatGPT. 
#### User Experience: Fair 
- Integrated into developer tools, not ideal for educational use cases; lacks interactivity. 

## Execution:

### Run all four prompting techniques on all four platforms 

### Result for the execution: 

<img width="1048" height="481" alt="rating 1" src="https://github.com/user-attachments/assets/c236f409-13ca-4a89-86a3-7a1e2fcf4bcb" />

<img width="1111" height="434" alt="rating 2" src="https://github.com/user-attachments/assets/5819fa70-a395-422e-9f0e-c02b1a9dc158" />



## RESULT: 

Thus Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization is executed successfully.

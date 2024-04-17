# Getting Started

## Google Drive Access Permission Analyzer

A tool designed for **Analyzing the Access Permission details of all the files and folders** for a given google drive account. This explains the entire flow of the script, including the sequence of authorizations leading to the execution of the results.  

## Requirements

-   A **platform** that support the execution of python scripts, here in this case **Visual Studio Code** application has been and to receive the result in the VS Code terminal itself, the **interpreter** selected here is **Python 3.12** (can be installed from **Microsoft Store** or directly from the official webpage of Python Organization [Download Python](https://www.python.org/downloads/))
    
-   **Enabled Google Drive API** for the account to be analyzed
    
-   **Script** to execute the flow of the tool **GDAPA**
    
-   A **credentials.json** file
    
-   A **token.json** file

## Workflow Execution

-   Create a **directory** at your desired path and **save the script** in that directory.

-   **Enable** the Google Drive API. To enable [click here](https://console.cloud.google.com/projectselector2/apis/enableflow?apiid=drive.googleapis.com&supportedpurview=project&authuser=1)
    
-   To create credentials, the **OAuth consent screen** has to be configured from **Google Cloud**
    
		Google Cloud > API & Services > OAuth consent screen

-   Once configured, **create credentials** required from
    
		Google Cloud > API & Services > Credentials

-   **Download** the credentials and **rename the file** as mentioned below, and save them in the **same directory** where the script exists

		credentials.json
    
    ## Reference
   
-  To view the **sample script** of the **credential.json** file, [click here](https://drive.google.com/file/d/1w0Plsw4o2lA3ugIZQLwCzBsmzHDGc5xI/view?usp=sharing)

    
- For **more information** regarding the creation of credentials, watch the video reference by  [clicking here](https://drive.google.com/file/d/1oUV-tBHhHJ9TEkvZdyL6v8_QtJeuWcr1/view?usp=sharing)

  ## Script Execution 

-   Now initiate the script in VS Code and launch the terminal to execute
    

![](https://lh7-us.googleusercontent.com/w2hrDZ79mVzNyEl_aanNpLYTi2cCds41kqMsbm3j5GsucD68NJ1NSz3TpAC8UgLL-UgrE8UgN_pYK2k_AX068JptJKMizOOETkTaKAjaJ1fg9_gqKNxz5QM4b6c5TcSg0Ji9q5lRmSvyF-KP-3OEB9g)

- To execute the script flawlessly, the below mentioned modules has to be installed,

		pip install google-auth google-auth-oauthlib google-api-python-client 
		pip install colorama
		pip install tabulate
		
-   In the terminal, **navigate to the folder** that contains the script and the credentials.

-   Check whether all the required files are present the directory created,

		ls
    
-   Run the script using this command, which is used to execute the output,

		 gdapa -o O
    

-   When the script is executed for the first time, the authentication flow occurs, and upon completion of the flow, the **token.json** file is **automatically generated** and saved in the same path where the script and the credentials exist.
    

## Reference Captures Output Execution along with Authentication Flow  






![](https://lh7-us.googleusercontent.com/Qdxk9hC6KEOXxKdaBFOlpZND-dlAGMNYxfmct8h6ZYKrgdNEMt1uP7zXzXskgwU2RoQYqLVYqLMB-77UPDgwaYuP8i6YqLJAIXiEwvq8nwdFgeH3Z8eQJxS99AbxjO2GvGircmrEw94n-MT0z5j-Xls)

![](https://lh7-us.googleusercontent.com/GTiDhR9jWmebR-l4YFL3eQrcDejH55Y3N_dL5V96e4JTPQFQK0o73jFWU_hLIO-gz9R17ZnIrNDN-jZrg_QHdjrrmmyBpcO8VoED5kFnN-XjSka742hTEO6gKHCCl-ReazZSYOXgdFSZFjwYtnspIUs)

![](https://lh7-us.googleusercontent.com/jZNTWCxDvYYLCj3GCuK_BCNtBymZyQvkuCg_VY_ifoM7AjiouwjQf84SvirDB4zyIgJjoxEXT9Nfa3XpRbSu5ah9Jo466pVyZiTk7JWV5Yuy5DgvPSSxcnVF66ZNyrW6Teo3hX-4Baaf93fPYhpAMxY)

![](https://lh7-us.googleusercontent.com/9nlAFJZbifMMH1oAeY_KhH0HNcYMHFCFPKZPwSUxID8_i9baVnuXa_IlmzkF4JWHOPAWojJVVOuMRd-U7O5XG7eaUZ8SkC-PxtpbnpVjdY99FG1zlQcFGcLINw1bXRUznaI6l1JhuHPOPi9ThWAh2NQ)
  ![](https://lh7-us.googleusercontent.com/AdI6uiLsJO2b47sM2fJGYLV8NGWhUAoVNzwMsOOT_h7mJW7V9VFsoCYpw5vypYkQQDKXj1Z39ITBQgAGY4q8zC0XM0y4Spzuqg2sqoW8k9MS9J8TKTZoVrpQqrdVPIAmXqWy4Gl-l8RrqwdM4NCRJjY)

- **Return** to Visual Studio Code and **catch a glimpse of the output** of the executed script
![](https://lh7-us.googleusercontent.com/bILmwhNX0NvXi_-KVg8FIhm_WkPlhgKhbecRbE9PTrAsXoDOg5IloywHuLmOSP2SOwtUfos-k0AQT1I7b12tdFQp0WRpgzy6w9Kw9YVS-xK0ZqxnOIPBwL9z3Bcam5PiMn25YQimdJzhIOPBFD6qSgQ)

-   Once the output gets executed again **list the files** inside the folder, here **token.json** will be there present

		 ls

![](https://lh7-us.googleusercontent.com/iVG0VIuzKgZNlu_V2KNBrKOpMgdlp_8OdN_UQhBZ3IHJuZZXfTRSy3rie_q0WqrWGdRyl-aUSnwI_g78vwRaGnk_chuo5HvHSZyqeHrk7upvc4T0exHFsEvLNN_H8Z91JENTftV3LH_DyvcX1QhNTj8)







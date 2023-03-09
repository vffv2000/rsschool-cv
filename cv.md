# Bychynski Valiantsin  

# Contact Information:  
Phone: +48571797197  
E-mail: Bychinskiy.Valentin@mail.ru  
LinkedIn - @vffv2000  
GitHub- @vffv2000  
Telegram: @vffv2000  

# About me
Hello there.  
I'm a person with strong interpersonal skills, an excellent team player, and a keen learner who's always looking to develop new skills. I'm dependable and responsible, and I often seek out new responsibilities across a broad range of employment areas.In my free time, I'm passionate about exploring the world of cryptocurrencies and staying up-to-date with the latest developments. I'm also an avid sports enthusiast and enjoy playing football and cycling. Additionally, I love learning about new technologies and finding ways to integrate them into my life.

# Skills
•	Understanding of OOP principles  
•	Knowledge of relational databases  
•	Proficient in Python  
•	Django web development  
•	Knowledge of the concept IaC CI/CD  
•	Web3 wrote multi-threaded scripts  
•	Tkinter interface development  
•	Basic HTML/CSS and C++ skills  
•	Unity game development for Android  
•	Basic VBA knowledge  
•	Knowledge of computer architecture, algorithms, graphics, graph theory, information technology, information security, probability and statistics, Linux  
•	High proficiency in Microsoft Office  

# Code example:

while True:  
    balance = client.get_account_balance(str(WALLET_ADDRESS))  
    print(balance)  
    if (balance>2):  
        try:  
            priv_key = PrivateKey(bytes.fromhex(PRIVATE_KEY))  
            txn = (  
                client.trx.transfer(str(WALLET_ADDRESS), str(WALLET_ADDRESS_MAIN),(balance-1)* 1000000)  
                .memo("Transaction Description")  
                .build()  
                .inspect()  
                .sign(priv_key)  
                .broadcast()  
            )  
            txn.wait()  
        except Exception as ex:  
            print(ex)  
    else:  
        print(str(balance)+" less that 2")  

# Work experience  
Participated in the hackathon from Hoster.by (January 2023) (4 place) - Asveta Project  
As a Python backend developer    
•	worked with admin panel   
•	Involved with admin panel and data models, as well as databases  
Technician at OJSC DST No. five (July 2021 - August 2021)  
•	Worked with data processing and reporting in 1C program  
•	Provided 1C user consulting  

# Education:  
2020 BSUIR (Belarusian State University of Informatics and Radioelectronics) - Third-year student  
Faculty: FITU (Faculty of Information Technology and Management)  
Specialization: ASOI (Automated systems for information processing)  

# Add. Education:  
•	“Python Generation” course for beginners (https://stepik.org/cert/1429917)  
•	“Python Generation” course for advanced (https://stepik.org/cert/1515263)  
•	Algorithms: theory and practice. Data Structures (https://stepik.org/cert/1558349)  
•	Python: Basics and Applications (https://stepik.org/cert/1568131)  
•	Web development for beginners: HTML and CSS (https://stepik.org/cert/1647742)  
•	Web technologies: entry level (https://stepik.org/cert/1697085)  

# Language Skills  
•	Russian (native speaker)  
•	Belorussian (native speaker)  
•	English (B1)  
•	Polish (A1)  

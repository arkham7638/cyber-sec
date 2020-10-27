# cyber-sec
Being an Big Data student I was always fascinated and wondered how cyber security will work with big data so my project revolves around the mixture of these both and I have created a Jupyter notebook which is called (EXPLORING CYBER ATTACK WITH EDA AND PYTHON)

The data set is taken from various api.

# Prediction 

In this project we are basically using the Python (3.6) to be exact the library including 
->Numpy
->Seaborn
->Matplotlib
->scipy
->sweetviz

STEP1: First step is the most impportant step as we are reading the data - set and checking if there is any null value.

Numpy = NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

Seaborn = Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

Mtaplotlib = Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits like Tkinter, wxPython, Qt, or GTK+.

SciPy is a free and open-source Python library used for scientific computing and technical computing. SciPy contains modules for optimization, linear algebra, integration, interpolation, special functions, FFT, signal and image processing, ODE solvers and other tasks common in science and engineering.

Sweetviz is an open source Python library that generates beautiful, high-density visualizations to kickstart EDA (Exploratory Data Analysis) with a single line of code. Output is a fully self-contained HTML application.

# Types of Cyber-Security Attacks

Reconnaissance: attacker gathers information about computer network to evade security controls.

Fuzzers: the attacker attempts to uncover security loopholes in a program, operating system, or network by feeding it with massive random data entry to block it.

Analysis: a type of intrusion that penetrates web applications through ports (for example, port scans), emails (for example, spam), and web scripts (for example, HTML files).

Backdoor: a stealthy technique to avoid normal authentication to ensure unauthorized remote access to a device.

Exploit: a sequence of instructions that exploits a flaw (vulnerability) caused by involuntary or unsuspected behavior on a host or network.

Generic: a technique that attempts against block encryption using a hash function for collision regardless of encryption settings.

Shellcode: attacker penetrates a small piece of code from shell to control the compromised machine.

Worm: the attack replicates malicious script to spread it to other computers. Often, it uses a computer network to spread, depending on security flaws in the destination computer.

DoS: an intrusion that disrupts computer resources, often through memory, to be extremely busy to prevent unauthorized requests from accessing a device.

# About the data set(Cyber-sec)

The columns contain - 
 
1. **Time:** start and end date of the attack in *timestamp* format.
2. **Attack category:** type of registered cybersecurity attack.
3. **Attack subcategory:** subcategory of the type of cybersecurity attack registered
4. **Protocol:** protocol used for the attack.
5. **Source IP:** IPv4 address where the attack came from.
6. **Source Port:** logical port where the attack came from.
7. **Destination IP:** destination IPv4 address.
8. **Destination Port:** logical destination port.
9. **Attack Name:** technical name for the cybersecurity attack.
10. **Attack Reference:** Common Vulnerabilities and Exposures (CVE) reference of the type of cybersecurity attack
 
 # About the data set(Tcp Port)
 
 The columns contain - 
 
 Port 
 Service -  It is the section which was malacious (like graphics and all )
 Desciption - The section which is vulunrable 
 
 ## Detailed analysis of logical ports
 
 There is a big difference in the mean of source ports (15391) and destination ports (1304) in cybersecurity attacks. In order to identify if this difference is **statistically significant**, that is, that it can be statistically verified with a level of **significance**, we will conduct a **Hypothesis Testing** on the difference in the averages of the source and destination ports.

In other words, we would like to statistically test whether the two group means are different from each other; that is, if the mean of the source ports of the cybersecurity attacks ($\mu_1$) are different from the mean of destination ports of the attacks ($\mu_2$). The testing procedure has two hypothesis statements $ H_0 $ and $ H_a $:

$$ H_0: \mu_1=\mu_2$$
$$ H_a: \mu_1\neq\mu_2$$

Being:
- $H_0$ the null hypothesis: the means of the source and destination ports are equal.
- $H_a$ the alternative hypothesis: the means of the source and destination ports are different.

This type of statistical tests report a **$p$-value**. This is a key value used to determine if the test results were or not statistically significant. We are going to introduce another variable $\alpha$ that corresponds to the significance level that will be set to $\alpha = 0.05$.

We can obtain one of two results from the test:

1. If the **$p$-value** is less than our significance level ($p<\alpha$) we reject the null hypothesis $H_0$ and affirm that the observed difference is **statistically significant**.
2. If the **$p$-value** is greater than our significance level ($p>\alpha$) we will have to retain $H_0$ and conclude that the observed difference **is not statistically significant**.

The hypothesis test is conducted using a statistical **$T-test$** which specifies the two Series `df_interest['Source Port']` and `df_interest['Destination Port']`. By specifying these two Series, we are automatically referring to a comparative test of the means of both Series:
 
# What to achieve -

So the EDA is done without any machine learning project and as u can see that machine learning and cyber security goes hand to hand so in the near future i wish to uprade the project using the machine learning model by using Naive Bayes 

In statistics, Naive Bayes classifiers are a family of simple "probabilistic classifiers" based on applying Bayes' theorem with strong independence assumptions between the features. They are among the simplest Bayesian network models

And using amazon (AWS) EC2 or the herekou for the deployment as which will help in updating the project for the usage .


**Thank You**
**-ReadigThis-**

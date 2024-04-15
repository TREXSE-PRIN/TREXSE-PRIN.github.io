---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Research Project
subtitle: Trustworthy Recommenders for Software Engineers
banner: "/assets/images/banners/home.jpeg"
---

Recommender Systems for Software Engineers (RSSEs) support software development, e.g., by suggesting APIs or source code snippets to use in a given context, or by helping in change management tasks, e.g., by assigning changes to suitable experts. The availability of data from forges such as GitHub or Question & Answer (Q&A) forums such as Stack Overflow, and the development of advanced machine learning techniques, have fostered significant advances in this field.
On the one hand, the large availability of training material increases the potential of RSSEs. On the other hand, such training material can suffer from several problems. First, it may contain potentially vulnerable code, which could be recommended to developers. Since recommenders often create training sets based on code popularity, attackers may produce malicious training data by creating fake projects or misleading discussions on forums and artificially inflating their popularity metrics. Second, upon receiving suggestions, developers may want to be aware of the provenance and trust of what they get.
For example, they may want to only leverage code snippets or suggestions originating from trusted groups, and possibly avoid whatever has a provenance from certain organizations or countries. Indeed, security and privacy issues occurring when leveraging automated approaches may also lead to legal issues. This is also testified by the efforts made by the European Commission to introduce a comprehensive legal framework for Artificial Intelligence (AI).
Moreover, developers would like to keep their previous decisions, and feedback provided to the RSSEs be taken into account. 
By setting up human-in-the-loop scenarios, developers would like to enhance the recommender systems' accuracy through the feedback given to the given recommendations while using the systems. Although studies tried to improve existing recommender systems by considering implicit and explicit feedback, their application to software engineering is still limited, and developers are supposed to go through recommended items without the possibility of marking them as accepted, rejected, or amended.
The project TRex-SE (Trustworthy Recommenders x Software Engineers) aims to develop methods to improve the trustworthiness of RSSEs.
More specifically, the TRex-SE contributions are related to:

2. The development of vulnerability and privacy-aware miners able to create training sets for RSSEs;
3. The conceptualization and instantiation of a trustworthiness model for RSSEs; and
4. The definition and development of trustworthy RSSEs that leverage the aforementioned trustworthiness model and are also able to capture (and leverage) developers’ feedback during development.

The TRex-SE output, beyond scientific publications, will consist of open-source toolsets. Such toolsets will foster the trustworthiness of RSSEs, and favor their adoption in industrial contexts.

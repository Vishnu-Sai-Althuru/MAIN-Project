# Main-Project

Project Title:-


                                A NEW ENCRYPTED DATA SWITCHING PROTOCOL: BRIDGING IBE AND ABE WITHOUT
                                LOSS OF DATA CONFIDENTIALITY


CONTEXT

    • ABSTRACT
    • EXISTING SYSTEM
    • DISADVANTAGES
    • PROPOSED SYSTEM
    • ADVANTAGES
    • SYSTEM REQUIREMENTS
    • REFERENCES


ABSTRACT

    • Encryption technologies have become one of the most prevalent solutions to safeguard data confidentiality in may real-world applications, e.g., cloud-based data storage systems. Encryption outputting a relatively “static" format of encrypted data, however, may hinder further data operations, for example, encrypted data may need to be “transformed" into other formats for either computation or other purposes.
    • In order to enable an encryption to be used in another device equipped with a different encryption mechanism ,the concept of encryption switching is first proposed in CRYPTO 2016 for conversion particularly between Paillier and ELGamal encryptions.
    • This paper considers the conversion between conventional identity-based and attribute-based encryptions and further proposes a concrete construction via the technique of proxy re-encryption.
    • The construction is proved to be CPA secure in the standard model under q-decisional parallel bilinear Diffie-Hellman exponent assumption. The performance comparisons highlight that our bridging mechanism reduces computation and communication cost on client side, especially when the data of client is encrypted and outsourced to remote cloud.
    • The computational costs w.r.t. re-encryption (on server side) and decryption (on client side) are acceptable in practice.

EXISISTING SYSTEM
    • Mizuno and Do i have proposed an ABE → IBE type PRE construction that is able to convert a cipher text in the format of ABE to an IBE encryption. The scheme, however, cannot achieve the conversion for the other way round, i.e. converting an IBE cipher text to an ABE encryption. Besides, only supports AND gates on positive and negative attributes w.r.t. ABE encryption, which is with low expressiveness.
    • The trusted third party is responsible for the generation and management of public/private keys. The trusted third party may be a single server or multiple servers. The symmetric keys are protected by combining the public key cryptography and the (k, n) threshold secret sharing schemes. Nevertheless, such schemes do not protect the data files against tempering and loss due to issues arising from virtualization and multi-tenancy.
    • Our proposed strategy does not depend on the traditional cryptographic techniques for data security. Moreover, the methodology does not store the whole file on a single node to avoid compromise of all of the data in case of successful attack on the node.



DISADVANTAGES

    • There is no Data Fragmentations to keep data in secure way.
    • The data outsourced to a public cloud is not secured due to lack of Cloud Security.


PROPOSED SYSTEM

    • In this paper we have introduced encryption switching between IBE and ABE which is the first of its type in the literature. The security notion has been defined in the    game based framework.
    • We have presented a concrete construction and meanwhile proved it to be CPA secure in the standard model under the decisional q-parallel BDHE assumption. The efficiency analysis has highlighted that our solution outperforms the download-and-re-encrypt conversion mode w.r.t. computation and communication cost
    • In order to construct a re-encryption key we usually need to input the secret/private key of a delegato and the public key information of a delegate.	

ADVANTAGES

    • A successful attack on a node might put the data confidentiality or integrity, or both at risk.
    • The system proposes not to store the entire file at a single node. The ABE methodology fragments the file and makes use of the cloud for replication. The fragments are           distributed such that no node in a cloud holds more than a single fragment, so that even a successful attack on the node leaks no significant information.

SYSTEM REQUIREMENTS:-

HARDWARE REQUIREMENTS:

    • System : Intel Core i5 and above.
    • Hard Disk : 500 GB.
    • Monitor : 15 INC LED
    • Input Devices : Keyboard, Mouse
    • Ram : 4 GB

SOFTWARE REQUIREMENTS:

    • Operating system : Windows 10.
    • Coding Language : Java
    • Database : MYSQL
    • Markup Languages : HTML , CSS ,Bootstrap.
    
IMPLEMENTATION:-

 • user module: User is the owner of data. Privacy, disaster recoverability,modification detection of user’s data is ultimate goal of this paper.
 
 • Owner module: Manage roles and permissions for a project and all resources within the project. Set up billing for a project, Granting the owner role at a resource level, such    as a Pub/sub topic, doesn‘t grant the owner role on the parent project, Granting the owner role at the organization level doesn‘t allow you to update the organizations          metadata. However, it also you to modify project and other resources under that organization.
 
 • Cloud server: Cloud server is considered as ℎ𝑜𝑛𝑒𝑠𝑡 𝑏𝑢𝑡 𝑐𝑢𝑟𝑖𝑜𝑢𝑠. This means that cloud server follows the Service Level Agreement (SLA) properly, but has an intention to          analyze user’s data. Conversely, cloud server may pretend to be good but acts as a potential adversary. In that case, cloud server may modify data in order to forge as          original data. Similarly, cloud server may hide/loss the data resulting in permanent data loss of the user. Furthermore, hardware/software failure may result in data            modification or permanent loss as well.
 
 • Trusted authority module: The trust store must contain any trusted client certificates used for authentication, or it must certificate of the certificate authority used to      sign the client‘s certificates. The login module is to authenticate the certificate presented by the client using the configured truststore

CONCLUSION:-


• It is a performance comparisons highlight that our bridging mechanism reduces computations and communication cost on the client side especially when the data of the client is encrypted and outsourced to a remote cloud. This includes the conversion between conventional identity-based and attribute-based encryptions and further proposes a concrete construction via the technique of proxy re-encryption. The construction is proved to be CPA secure in the standard model under q-decisional parallel bilinear Difﬁe–Hellman exponent assumption. The performance comparisons highlight that our bridging mechanism reduces computation and communication cost on the client side, especially when the data of the client is encrypted and outsourced to a remote cloud

REFERENCE:-

 • G. Couteau, T. Peters, and D. Pointcheval, “Encryption switching protocols,” in Advances in Cryptology - CRYPTO 2016 - 36th Annual International Cryptology Conference, 2016,    Proceedings, Part I, ser. Lecture Notes in Computer Science, M. Robshaw and J. Katz, Eds., vol. 9814. Springer, 2016, pp. 308–338. 
 
 • P. Paillier, “Paillier encryption and signature schemes,” in Encyclopedia of Cryptography and Security, 2nd Ed., H. C. A. van Tilborg and S. Jajodia, Eds. Springer, 2011, pp.    902–903. 
 
 • A. Shamir, “Identity-based cryptosystems and signature schemes,” in Advances in Cryptology, Proceedings of CRYPTO ’84, 1984, Proceedings, 1984, pp. 47–53. 
 
 • V. Goyal, O. Pandey, A. Sahai, and B. Waters, “Attribute-based encryption for fine-grained access control of encrypted data,” in ACM CCS’06, 2006, pp. 89–98. 
 
 • M. Portnoi and C. Shen, “Secure zones: An attributebased encryption advisory system for safe firearms,” in IEEE Conference on Communications and Network Security, CNS 2013,      2013. IEEE, 2013, pp. 397–398. [Online]. Available: https://doi.org/10.1109/CNS.2013.6682746

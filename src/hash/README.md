# Hash算法  

## 定义  

Hash（哈希或散列）算法是IT领域非常基础也非常重要的一类算法，可以将任意长度的二进制值（明文）映射为较短的固定长度的二进制值（Hash值），并且不同的明文很难映射为相同的Hash值。Hash值在应用中又被称为数字指纹（fingerprint）或数字摘要（digest）、消息摘要。  

## 流行的Hash算法  

目前常见的Hash算法包括Message Digest（MD）系列和Secure HashAlgorithm（SHA）系列算法。  

### Message Digest（MD）  

MD算法主要包括MD4和MD5两个算法。MD4（RFC 1320）是MIT的Ronald L.Rivest在1990年设计的，其输出为128位。MD4已被证明不够安全。MD5（RFC1321）是Rivest于1991年发布的MD4改进版本。它对输入仍以512位进行分组，其输出是128位。MD5比MD4更加安全，但过程更加复杂，计算速度要慢一点。MD5已于2004年被成功碰撞，其安全性已不足以应用于商业场景。  

### Secure HashAlgorithm（SHA）  

SHA算法由美国国家标准与技术研究院（National Institute of Standards andTechnology，NIST）征集制定。SHA-0算法于1993年问世，1998年即遭破解。随后的修订版本SHA-1算法在1995年面世，它的输出为长度160位的Hash值，安全性更好。SHA-1设计采用了MD4算法类似原理。SHA-1已于2005年被成功碰撞，意味着无法满足商用需求。为了提高安全性，NIST后来制定出更安全的SHA-224、SHA-256、SHA-384和SHA-512算法（统称为SHA-2算法）。新一代的SHA-3算法也正在研究中。  


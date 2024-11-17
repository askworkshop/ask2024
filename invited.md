---
layout: single
toc: false
classes: wide
sidebar:  
  - title: " "   
    image: /assets/images/kol2.jpeg
    image_alt: "image"
    nav: "docs"
---

# Invited Speakers

Here is the list of confirmed speakers. We will add more speakers and add the talk title and abstracts soon. <br>

<ul>
<li>Christina Boura, IRIF, Université Paris Cité, France
<ul>
  <li> Topic: Transistor: a TFHE-friendly Stream Cipher </li>
  <li> Abstract: In this talk we will introduce Transistor, a novel stream cipher specifically designed for efficient homomorphic evaluation within the TFHE scheme, a widely-used FHE framework known for its fast bootstrapping and ability to handle low-precision data. Transistor operates on F_17 which is chosen to optimize TFHE performance. Its components are carefully engineered to both control noise growth and provide strong security guarantees. First, a simple TFHE-friendly implementation technique for LFSRs allows us to use such components to cheaply increase the state size. At the same time, a small Finite State Machine is the only part of the state updated non-linearly, each non-linear operation corresponding in TFHE to a very expensive Programmable Bootstrapping. This update is done using an AES-round-like transformation. But, in contrast to other stream ciphers like SNOW or LEX, our construction comes with information-theoretic security arguments proving that an attacker cannot obtain any information about the secret key from three or fewer consecutive keystream outputs. These information-theoretic arguments also lead to a bound on the minimal keystream length required for recovering the secret key. Our implementation of Transistor significantly outperforms the state of the art, achieving a throughput of over 60 bits/s on a standard CPU, all while avoiding the need for an expensive initialization process.
</li>
</li>
<li>Jean Paul Degabriele, TII, Abu Dhabi</li>
<li>Patrick Derbez, INRIA, Rennes, France</li>
<li>Hossein Hadipour, Graz University of Technology, Austria</li>
<li>Ashwin Jha, Ruhr University, Bochum, Germany</li>
<li>Eik List, Independent Researcher</li>
<li>Bart Mennink, Radboud University, Netherlands</li>
<li>Palash Sarkar, Indian Statistical Institute, Kolkata, India</li>
<li>Yu Sasaki, NTT Social Informatics Laboratories and NIST Associate</li>
<li>André Schrottenloher, INRIA, Paris, France</li>
<li>Yaobin Shen, Xiamen University, China</li>
</ul>

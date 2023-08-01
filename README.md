# découpage réseau
# 172.16.1.0/24

**Découpage symétrique:**                                  
On a 50 équiepement pour les 4 pôles , Alors on a besoin de 6 bits (2^6=64)                                       
Pour 64 adresse, 32-6= 26 ---> /26     

**Le Pôle informatique:**                                  
- Adresse réseau: 172.16.1.0                              
- Adresse de diffusion: 172.16.1.63
  
**Le Pôle développement:**
- Adresse réseau: 172.16.1.64                                                                                
- Adresse de diffusion: 172.16.1.127

**Le Pôle Administratif:**                                 
- Adresse réseau: 172.16.1.128
- Adresse de diffusion: 172.16.1.191
                                        
**Le Pôle Technicien:**                                                                               
- Adresse réseau: 172.16.1.192
- Adresse de diffusion: 172.16.1.255                                                                                                                                        
                          
**Découpage asymétrique:**   

**- Le Pôle informatique**                                  
- On a 50 équipements, Alors on a besoin de 6 bits (2^6 = 64)                                        
pour 64 adresse , 32-6 = 26 ---> /26                                             
- Adresse réseau: 172.16.1.0                                        
- Adresse de diffusion: 172.16.1.63
                                           
**Le Pôle développement:**
- On a 12 équipements, Alors on a besoin de 4 bits (2^4 = 16)                                               
   pour 16 adresse, 32-4 = 28 ---> /28
- Adresse réseau: 172.16.1.64
- Adresse de diffusion: 172.16.1.79
                                   
**Le Pôle Administratif:**
- On a 20 équipements, Alors on a beseoin de 5 bits (2^5 = 32)                                               
Pour 32 Adresse , 32-5 = 27 ---> /27                                              
- Adresse réseau: 172.16.1.80                                                
- Adresse de diffusion: 172.16.1.111
                                         
**Le Pôle Technicien:**                               
-  On 15 équipements, Alors on a besoin de 4 bits  (2^4 = 16)                                                 
Pour 16 adress, 32-4 = 28 ---> /28                                                 
- Adresse réseau: 172.16.1.112                                             
- Adresse de diffusuin: 172.16.1.127                                                                                                                                     
  

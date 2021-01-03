# CuckooHashing

원리 : 
hash table 두 개를 만들고 먼저 첫번째 hash function에 넣어서 item이 들어갈 key값을 구하고 hash table에 넣는다.
만약 그 key에 다른 item이 들어가 있으면 두번째 hash function에 넣고 두 번째 hash table에 삽입한다.

## Cuckoo_Hashing.py 실행 결과
![image](https://user-images.githubusercontent.com/49015100/103477823-aaa9f480-4e05-11eb-9e84-23286c1a6541.png)
![image](https://user-images.githubusercontent.com/49015100/103477827-ae3d7b80-4e05-11eb-8cdf-4844f69898c7.png)
![image](https://user-images.githubusercontent.com/49015100/103477829-b1386c00-4e05-11eb-982f-934c2962a4d1.png)

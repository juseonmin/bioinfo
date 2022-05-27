생물정보학 및 실습 1 실습 프로젝트
목표 : Figure 2E 구현하기

LIN28A Is a Suppressor of ER-Associated Translation in Embryonic Stem Cells 의 figure 2E는 
Normalized relative frequency matrix of WC-pair co-occurrence around LIN28A-interacting sequences를 나타내고 있다.

mirlet7g 등과 상호작용하는 것으로 잘 알려져 있던 Lin28A가 miRNA 이외에도 mRNA와 상호작용 할 수 있다는 문맥의 figure 이다.
따라서 CLIP-seq data 인 CLIP-35L33G.bam 파일을 이용해 전체 Genome 단위로 search를 해보고자 한다.

week 1 - 전반적인 내용 파악 및 전체 genome 대상으로 shannon entropy 구하기
         FDR을 위해 read depth 50 이상, CRES(shannon entropy) 0.8로 cut-off 해줌 
       
       
week 2 - 위에서 구한 data를 기반으로 WebLogo 제작 및 찾은 binding site를 중심으로 하여금 주변 (-2~+3) seq 보기
         이를 통해 pattern 찾기
         또, 본격적인 2E를 위해 WC-pair co-occurrence frequency 계산하기 ~ randomly permuted sequences와 비교하기
         

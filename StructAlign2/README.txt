StructAlign2
======================================================================================
1) Place to desired folder
2) Unzip (tar -xf StructAlign.tar)
3) type 'make'
4) run as 'python StructAlign.py pdb1 pdb2'

Type 'python StructAlign.py -h' for more options


pdb1*_pdb2*.pdb
	pdb-���� � ����������� ��������, ��� * - ��� �������� ����

pdb1_pdb2.fasta
	������������ ���; ����������� ������ 2 � ��������� 2 ������������������
	
����� ������������ �� kodomo, ����� ������� ���� � 3DNA:
export PATH=${PATH}:/home/preps/golovin/progs/X3DNA/bin
export X3DNA=/home/preps/golovin/progs/X3DNA



MultiStructAlign
======================================================================================
������: python MultiStructAlign.py pdb1 pdb2 -d pdb_folder -c pdb2:chain1 pdb2:chain2

pdb1, pdb2 - �����, �� ID

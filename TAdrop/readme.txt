�@�~�T ������

�u�������v�]document classification or text categorization�^�O���̤��u���e�D���v���w�u���O�v�]class or category�^���N��C�Ҧp�A�s�D���i������ɪ����e�A�����u�F�v�v�B�u�~��v�B�u�T�֡v�B�u�B�ʡv��
���O�C�q�`�A�o�����O���O�ƥ��w�q�ο�w�A�H�ŦX�޲z�̪��ݨD�P����C�ӵ��w���O���u�@�A�ǲΤW���ѤH�u�\�����A�ھڨ�D�D�j�N�A�����A�����O�ХܡC�������O�Ϯ��]�Ǥ���T��´�P�D�D���R���̤@���D�`���n�����D�A�]�O�{�����Ѻ޲z�D�n�����Τu�㤧�@�C

²�z�@�~���e�p�U�G

1. �H20 Newsgroups����󬰰�¦�A�^���Ӹ�ƶ��������O�Gcomp.graphics�Pcomp.windows.x�A�U��500�g�峹�C
2. �H�����X400�g�Pcomp.graphics�������峹�H��400�g�Pcomp.windows.x�������峹�@��Training data (���ѩ���label data�Pword��Ӫ�)�A�Ѿl��200�g�峹�@��testing data(������label data)�C

3. �ЦP�ǥH2-4�H���@��(�����ۦ�M�w)�A���۰Q�סA��3/5�e�N�{���X�PTraining data���������G(output�榡���GConfusion matrix)�A�H��testing data���w�����G(�榡�аѦ�training data��label data)�C�W�Ǧ�E3���x�C�é�G

4. 3/6�W�ҫeú��ȥ��A���e�]�t�GTraining data�������G�Ptesting data���w�����G�C

�Ъ`�N�A���i�H�ϥ�matlab��python���t���u��c�κt��k�禡�A�ХΦۤv���޿�[�c�ӧ����{���X���g

��󤺮e�����G����training data(train.txt)�P������label(train_label.txt)�Btesting data(test.txt)�H�ε��J��Ӫ�(word.txt)

1) training set �]�t�G
	- train.txt       (dataMatrix, 800 x 228  - 800 vectors with dimensionality 228) 
	- train_label.txt (outcomeMatrix, 800 x 1 - 800 vectors with one dimension)
2) testing set �]�t�G
	- test.txt        (dataMatrix, 200 x 228  - 200 vectors with dimensionality 228)
	
3) word.txt (Vocabulary file)
	

�Ҧp�G
train.txt: �@�@       train_label.txt:
1 3 5 12	<====>    1
2 4 6 7	              2

word.txt:
lord
of
the
rings

�q�o�T���ɮץi��ܬ�
�Ĥ@�g�峹�Glord�X�{1���Aof�X�{3���Athe�X�{5���Arings�X�{12���A�ݩ�Ĥ@��
�ĤG�g�峹�Glord�X�{2���Aof�X�{4���Athe�X�{6���Arings�X�{7���A�ݩ�ĤG��

�ЧQ��training data�ι�����label�D�Xtraining data��Confusion matrix�Ptesting data���w��label����?

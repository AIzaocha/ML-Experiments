�ļ��ṹ��
�����ļ�����cnn-text-classification-tf��
���ļ�����data�ļ��а�������������
data_helpers.py��ϴ����
eval.py������������
text_cnn.py�ı�����
train.pyѵ������

��ʼ����ֻ��Ҫʹ��������������ɣ�
python train.py


�������壺
ALLOW_SOFT_PLACEMENT=TRUE:�Ƿ���Ҫ�Զ�����
BATCH_SIZE=64:�������С
CHECKPOINT_EVERY=100:����һ��ģ��
DEV_SAMPLE_PERCENTAGE=0.1:�������ݼ�����
DROPOUT_KEP_PROB=0.5������CNN����ȡ��Ԫ�������
EMBEDDING_DIM=128��ÿ�����ʵĴ������ĳ���
EVALUATE_EVERY=100��ÿѵ��һ�ٴΣ�����һ��
FILTER_SIZES=3,4,5������˸��ǵĵ���
L2_REG_LAMBDA=0.0�����򻯲���
LOG_DEVICE_PLACEMENT=False:�Ƿ��ӡ��־
NUM_EPOCHS=200����ѵ������
NUM_FILTERS=128������˵�����



ʵ�黷����
1.ubuntu16.04
2.python2.7��Ĭ�ϰ�װ�汾��
3.tensorflow1.0�汾����
��װ���sudo pip install  tensorflow
4.�����ļ���װpython��
sudo pip install  numpy
sudo pip install  collections





������
pip������apt-get�滻
pip��װ���ã�
cd ����Ŀ¼��
wget https://bootstrap.pypa.io/get-pip.py
sudo python  get-pip.py
mkdir ~/.pip
Ȼ���ڸ�Ŀ¼�´���pip.conf�ļ���д�������ݣ�
���vim ~/.pip/pip.conf

[global]
trusted-host =  pypi.douban.com
index-url = http://pypi.douban.com/simple
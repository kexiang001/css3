```
1����Ƶ
    ���ԣ�
        paused: ��Ƶ�Ĳ�����ͣ״̬
        duration:��Ƶ����ʱ��
        currentTime:��ǰ����ʱ��

    �ŷ���play() ����
          pause()��ͣ

    oncanplay�� ����Ƶ�������֮��
    ontimeupdate: ����Ƶ��ǰʱ�� �ı�֮�󴥷�

    ȫ����
        video.webkitRequsetFullScreen();

 2����ק��
    1����Ҫ������ק��draggable="true"
    2����קԪ�أ�
        ondragstart: ��ק��ʼ
        ondragend:��ק����
        ondragleave: �������ק�뿪 ����קԪ��ʱ
        ondrag:������קʱ����������
    3��Ŀ��Ԫ�أ�
        ondragenter:������קԪ�ؽ���Ŀ��Ԫ��ʱ
        ondragleave:��������Ŀ��Ԫ��ʱ
        ondragover: ������קԪ����Ŀ��Ԫ����ʱ����������
            --> e.preventDefault(); ��ֹ��ק��Ĭ����Ϊ��
        ondrop:����Ŀ��Ԫ�����ɿ����ʱ������


```



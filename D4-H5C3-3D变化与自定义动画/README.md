```


1�� 3d�任
    rotateX(30deg) ����x��ת30deg
    rotateY(30deg) ����y��ת30deg
    rotateZ(30deg) ����z��ת30deg
    translateX(30px) ����x���ƶ�30px
    translatey(30px) ����y���ƶ�30px
    translatez(30px) ����Z���ƶ�30px( ����������Ӽ�͸��)

 2��͸�ӣ�
        �Ӹ��任Ԫ�صĸ����ӣ� ���õ����û��۾�����Ļ�ľ��룻
        ֻ���Ӿ��ϵĳ��֣����������3d
        perspective:1000px;

  3��transform-style:preserve-3d;
        �Ӹ��任Ԫ�صĸ����ӣ����Ӻ��Ӵ�����ά�ռ��У�����3dЧ��
       flat:Ĭ��ֵ �����Ӻ��ӱ���ƽ����

   4�� backface-visibility:hidden; ���治�ɼ�


    skew(30deg,30deg);  2d�任 -��б

    css3�л�ȡ�Զ������Ե�ֵ��content:attr(data-text);

  5��������
      ���壺
        @keyframes ������{
            0%{

            }

            100%{

            }

            ����
            from{}
            to{}
        }

        �������ã�
            animation: �������� ����ʱ��  ִ�д���  �˶����� �ӳ�ִ�� ������״̬ �Ƿ���
                inifnite: ���޴�
                alternate: ����ִ��
                forwards: ���ֽ������״̬
                backwards: ���ֶ���ʼǰ��״̬
                steps(5): �ö����ֲ�ִ�У�

                ������ϸ���ԣ�
                    animation-name:��������
                    animation-duration:����ʱ��
                    animation-iteration-count:ִ�д���
                    animation-timing-function:�˶�����
                    animation-fill-mode:����״̬
                    animation-direction: ��������
                    animation-delay: �ӳ�ʱ��


                ���У����˽⣩
                    -webkit-column-count:����
                    -webkit-column-rule:�ָ�����ʽ
                    -webkit-column-width:�п�
                    -webkit-column-gap:�м��
                    -webkit-column-span:���� all ��������


```


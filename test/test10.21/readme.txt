1.�������ַ������ַ�������ķ������һ���ַ�,��ʾ��ҳ��idΪh1��Ԫ����
��:
    <div id="h1"></div>
    <script>
        var a = '���';
        var b = '����';
        var c  = a.concat(b); 
        document.getElementById('h1').innerHTML = c;
    </script>

2.һ���������87��,����ƹ���д��87w,���Զ����ɴ洢870000�ķ���,��ʾ��ҳ��idΪh2��Ԫ����
��:
    <div id="h2"></div>
    <script>
        var a = '87';
        var str = a.padEnd(6,'0');
        document.getElementById('h2').innerHTML = str;
    </script>

3.һ������79387.348�Ĺ��̿�,������λС������,��ʾ��ҳ��idΪh3��Ԫ����
��:
    <div id="h3"></div>
    <script>
        var num = new Number(79387.348);
        document.getElementById('h3').innerHTML = num.toFixed(2);
    </script>
4.һ��ͼƬ��һ�����·��img/head/,icon/1.jpg,��ֻ��Ҫ�õ������ļ���Ŀ¼����ʾ��ҳ��idΪh4��Ԫ����
��:
    <img src="img/head/icon/1.jpg" alt="" id="ig">
    <div id="h4"></div>
    <script>
        var ig = document.getElementById('ig');
        document.getElementById('h4').innerHTML = ig.getAttribute('src');
    </script>

5.�û�������֤��,���۴�Сд���붼����ȷ�ķ���,��ʾ��ҳ��idΪh1��Ԫ����
��:

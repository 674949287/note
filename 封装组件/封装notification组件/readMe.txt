�½�һ��notification.vue�����Ȼ�������������չ��������ͨ������ķ�ʽ���뵽index.js��ͨ��Vue.use��ȫ��ʹ��

func-notification��import notification.vue
Ȼ��extend���

function.js��import func-notification
����չ֮����������չ���ķ���
�׳�һ��notify
���ص�Vue��prototypeȥ����

��src�ļ��µ�index��
��Ҫͨ���������notification��index.js��ͨ��use��ȫ��ʹ��
	import Notification from './components/notification'
	// ����ȫ��֪ͨģ��
	Vue.use(Notification)

�����ͨ�������԰��ڰ�ť�ϻ�������
      this.$notify({
        content: 'test $notify',
        btn: 'close'
      })



��װһ��tabs���tabs�����л����ܣ�tab�����ڲ���li������ͨ�����ݸ�tabs����index����ѡ�еڼ�����tab����label��Ӧtab������
Ҳ������չ��tabs�м���span����tab��content����


      <tabs
        :value="filter"
        @change="handleChangeTab"
      >
        <tab
          v-for="tab in states"
          :key="tab"
          :label="tab"
          :index="tab"
        />
	<--�������չ-->
	<span>tab-content<span> // �������ֵ����Ƕ�̬�Ļ��������⣬�ҸĶ��ڶ��βŻ���ʾ��һ�εĸı䣬��vue����Ⱦԭ���йأ���Ҫȥ��һ��
      </tabs>
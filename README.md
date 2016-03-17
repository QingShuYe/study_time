# study_time
统计学习时长

为了促进学习，我需要一些来自现实的驱动力。用所学的知识解决一些现实中的问题是一个可行的做法。

学习时长，只是学习的其中一个指标，可以用来大概衡量对学习投入的多少。
统计出一周、一月的投入时间。

数据结构
mStudyTime:long

永久存储
SharedPreferences

界面布局
<ProgressBar>
<Button>30min
<Button>60min
*ProgressBar  max是目标，周目标，月目标，年目标。进度条满了表示达到了目标。
*我事先定义好id资源。

流程
1 启动App，打开Preference，读取“my_study_time”。如果是有，读取；否，读入0.
2 更新ProgressBar

输入记录
1 点击Button，有60min Button，30min Button。累加到mStudyTime。
2 更新ProgressBar


class StudyTimeActivity {

  /**
  *更新ProgressBar
  */
  private void upDateProgressBar(long)
  {

  }

}

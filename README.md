<div align="center">

# 新冠肺炎实时接口

<p>
    <!-- Place this tag where you want the button to render. -->
    <a class="github-button" href="https://github.com/leafcoder/django-covid19/subscription" data-color-scheme="no-preference: light; light: light; dark: dark;" data-show-count="true" aria-label="Watch leafcoder/django-covid19 on GitHub">
        <img alt="GitHub forks" src="https://img.shields.io/github/watchers/leafcoder/django-covid19?style=social">
    </a>
    <a class="github-button" href="https://github.com/leafcoder/django-covid19" data-color-scheme="no-preference: light; light: light; dark: dark;" data-show-count="true" aria-label="Star leafcoder/django-covid19 on GitHub">
        <img alt="GitHub forks" src="https://img.shields.io/github/stars/leafcoder/django-covid19?style=social">
    </a>
    <a class="github-button" href="https://github.com/leafcoder/django-covid19/fork" data-color-scheme="no-preference: light; light: light; dark: dark;" data-show-count="true" aria-label="Fork leafcoder/django-covid19 on GitHub">
        <img alt="GitHub forks" src="https://img.shields.io/github/forks/leafcoder/django-covid19?style=social">
    </a>
</p>

<p>
    <img src="https://img.shields.io/github/v/release/leafcoder/django-covid19" data-origin="https://img.shields.io/github/v/release/leafcoder/django-covid19" alt="GitHub release (latest by date)">
    <img src="https://img.shields.io/github/languages/top/leafcoder/django-covid19" data-origin="https://img.shields.io/github/languages/top/leafcoder/django-covid19" alt="GitHub top language">
    <img src="https://img.shields.io/github/languages/code-size/leafcoder/django-covid19" data-origin="https://img.shields.io/github/languages/code-size/leafcoder/django-covid19" alt="GitHub code size in bytes">
    <img src="https://img.shields.io/github/commit-activity/w/leafcoder/django-covid19" data-origin="https://img.shields.io/github/commit-activity/w/leafcoder/django-covid19" alt="GitHub commit activity">
    <img src="https://static.pepy.tech/badge/django-covid19" data-origin="https://pepy.tech/badge/django-covid19" alt="downloads">
</p>
</div>

由于现在疫情高发地已从国内转向国外，所以本项目也会逐渐增加*数据源*以便提供关于*国外某国某州（某省）*的疫情数据接口。

现已新增美国各州最新疫情以及各州每日疫情统计接口，可前往 [中国各省、美国各州接口](http://ncov.leafcoder.cn/docs/#/?id=province) 查看接口文档。

# 项目文档

本项目使用开源文档工具 [docsify](https://docsify.js.org) 编写了一份开发文档。

文档将如何安装部署本项目作了详细的描述，开发者可根据自身需求搭建一个属于个人
的 *新冠肺炎实时接口*，并通过项目提供的爬虫工具实时、定时的更新疫情数据，追踪
疫情的最新情况。

如果开发者本身没有个人的云服务器用来部署本项目，也可以直接调用本项目已部署好
的实时接口，可用于科研、娱乐、教学等各方面。

[![在线文档](https://raw.githubusercontent.com/leafcoder/django-covid19/master/docs/images/docs.png)](http://ncov.leafcoder.cn/docs/)

# 安装

可以通过 `pip` 命令安装：

    pip install django_covid19

# 初始化数据

初始化国家和地区编码数据；

    ./manage.py loaddata initial_data

# 在线大屏

根据已部署的疫情在线接口，并结合使用开源数据大屏项目中的示例代码，本项目提
供了一个使用本项目接口的数据大屏示例。

[![在线数据大屏](https://raw.githubusercontent.com/leafcoder/django-covid19/master/docs/images/dashboard.png)](http://ncov.leafcoder.cn/demo)

# 问题相关

有任何问题欢迎在 github 中提 issue，或者在文档页面的最后提交[评论](http://ncov.leafcoder.cn/docs/#/?id=detail-1)，我会尽快解答。

* 推荐使用评论方式提问；
* 推荐使用 isuss 提交 bug；

# 致谢

* [ccjhpu](https://github.com/ccjhpu)：在 [issues-8](https://github.com/leafcoder/django-covid19/issues/8) 中提出了加入各国各州的需求以及数据来源。

# 致各位

如果本项目对你有所帮助，请在[此处](http://ncov.leafcoder.cn/docs/#/?id=detail-1)留下你的项目地址。

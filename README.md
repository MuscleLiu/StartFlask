# StartFlask
On the way to study Flask!

做一些小例子来熟悉Flask!

hell.py:
1.首先，我们导入Flask类，这个类的实例将是我们的WSGI应用程序。
2.接下来我们创建该类的一个实例，第一个参数是应用模块或包的名称，如果你是用的
  是单一的模块（如本例），你应该使用__name__,因为模块的名称，将会因其作为单
  独应用启动还是作为模块导入而有不同（也即是‘__main__'或实际的导入名）。这是
  必须的，这样Flask才知道到哪里去找模块，静态文件等等。
3.然后我们使用route()装饰器告诉Flask什么样的URL能触发我们的函数。
4.这个函数的名字也在生成URL时被特定的函数采用，这个函数返回我们想要现实在用户
  浏览器中的内容。
5.最后我们用run()函数来让应用运行在本地服务器上，其中if __name == '__main__':
  确保服务器只会在该脚本被Python解释器直接执行的时候才运行，而不是作为模块导入的
  时候。
关闭服务器，按CTRL+C.


参考地址：http://docs.jinkan.org/docs/flask/index.html

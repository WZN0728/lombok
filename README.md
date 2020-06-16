lombok原理
 1.注解处理工具apt
  注解处理工具apt(Annotation Processing Tool)，这是Sun为了帮助注解的处理过程而提供的工具，apt被设计为操作Java源文件，而不是编译后的类。
 2.正常情况下使用APT工具只是能够生成一些文件(不仅仅是我们想象的class文件，还包括xml文件等等之类的)，并不能修改原有的文件信息
 3.其实Lombok是修改了Java中的**抽象语法树AST**才做到了修改其原有类的信息
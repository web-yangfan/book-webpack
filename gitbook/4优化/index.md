第4章 优化
======

经过前面的学习你已经能用 Webpack 解决常见的问题，但还有很多可以优化的点你可能还不知道。 优化可以分为优化开发体验和优化输出质量两部分， 本章进一步深入，教你如何优化 Webpack 构建。

优化开发体验
------

优化开发体验的目的是为了提升开发时的效率，其中又可以分为以下几点：

1.  **优化构建速度**。在项目庞大时构建耗时可能会变的很长，每次等待构建的耗时加起来也会是个大数目。
    
    *   [4-1 缩小文件搜索范围](4-1缩小文件搜索范围.html)
    *   [4-2 使用 DllPlugin](4-2使用DllPlugin.html)
    *   [4-3 使用 HappyPack](4-3使用HappyPack.html)
    *   [4-4 使用 ParallelUglifyPlugin](4-4使用ParallelUglifyPlugin.html)
2.  **优化使用体验**。通过自动化手段完成一些重复的工作，让我们专注于解决问题本身。
    
    *   [4-5 使用自动刷新](4-5使用自动刷新.html)
    *   [4-6 开启模块热替换](4-6开启模块热替换.html)

优化输出质量
------

优化输出质量的目的是为了给用户呈现体验更好的网页，例如减少首屏加载时间、提升性能流畅度等。 这至关重要，因为在互联网行业竞争日益激烈的今天，这可能关系到你的产品的生死。

优化输出质量本质是优化构建输出的要发布到线上的代码，分为以下几点：

1.  **减少用户能感知到的加载时间**，也就是首屏加载时间。
    
    *   [4-7 区分环境](4-7区分环境.html)
    *   [4-8 压缩代码](4-8压缩代码.html)
    *   [4-9 CDN 加速](4-9CDN加速.html)
    *   [4-10 使用 Tree Shaking](4-10使用TreeShaking.html)
    *   [4-11 提取公共代码](4-11提取公共代码.html)
    *   [4-12 按需加载](4-12按需加载.html)
2.  **提升流畅度**，也就是提升代码性能。
    
    *   [4-13 使用 Prepack](4-13使用Prepack.html)
    *   [4-14 开启 Scope Hoisting](4-14开启ScopeHoisting.html)

优化的关键是找出问题所在，这样才能一针见血，[4-15 输出分析](4-15输出分析.html) 教你如何利用工具快速找出问题所在。

[4-16 优化总结](4-16优化总结.html) 对以上的优化方法做一个总结。
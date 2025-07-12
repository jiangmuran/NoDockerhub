# NoDockerhub
### 在网络受限的情况下自动打包Docker镜像并发布为release

## 如何使用：
1. 点击Use this templates或拷贝github actions文件到你的项目
2. 在每次向main分支推送代码时会自动根据根目录下的DockerFile打包docker镜像到Action Artifact
3. 在每次创建新的标签时重新进行打包并上传至release
4. 无需任何额外配置，Enjoy it

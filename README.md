Hello there.

--Images to gif  (featuring imageio)--

TO-DO
- allow user to provide images to be converted into a gif
- allow for more user interaction
    - user could specify:
        - images files root folder
        - git files location
        - duration
- image file should be PNG or JPG
- images in the sub folder will be converted a gif
- Two gif files will be created for each groupf of images
- One gif file with 2 seconde duration, another gif file with duation assigned by the last argument 
REQUIREMENTS
    - Libraries needed:
        - imageio


Gif 文件生成工具
-- 1.第一个执行参数指定图片根目录，一级子目录下是图片文件, 每个子目录可以生成一个gif文件
-- 2.第二个参数指定间隔时间 单位秒
-- 3.图片是PNG或JPG扩展名
-- 4.一次生成两个gif文件，一个按指定间隔时间生成，一个按2秒生成由于慢速浏览。

使用示例：
# python gifyDir.py D:\DCIM\106APPLE\100APPLE D:\DCIM\gif 0.5
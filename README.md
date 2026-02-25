# Loren_Tool_Hub
存储常用的工具和库


'''
# 添加子模块（需要知道正确的仓库URL）
# 这里以假设的 URL 为例，你需要替换成实际的仓库地址
git submodule add https://github.com/原作者/clash-for-linux-install.git clash-for-linux-install

git add .gitmodules clash-for-linux-install
git commit -m "Add clash-for-linux-install as submodule"
git push
'''

'''
# 更新子模块
cd clash-for-linux-install
git pull
cd ..
git add clash-for-linux-install
git commit -m "Update clash-for-linux-install"
git push
'''
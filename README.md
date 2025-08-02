# hustoj-bs5
这是基于Bootstrap设计模板修改的HUSTOJ系统。

主要改进内容：

使用 Monaco编辑器（VS Code同款代码编辑器）

新增了原本缺失的 problem_import_xml.php（XML格式问题导入功能）

优化 problemset.php，改进了问题列表的UI设计

集成 Gemini API，支持AI自动生成题目功能

管理员页面可直接在线修改配置文件

新增 自动更新功能，可检测GitHub Release版本并执行更新

⚠️ 重要设置：
需调整web目录权限以确保正常运行：

bash
chown -R www-data:www-data /home/judge/src/web
（该版本在保持HUSTOJ核心功能的同时，增强了界面交互和管理便捷性）

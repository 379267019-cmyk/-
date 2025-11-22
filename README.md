# 山西大学餐厅评分计算系统

这是一个用于山西大学饮食文化中心的餐厅评分计算与数据分析系统。该系统可以帮助管理人员收集、分析和可视化餐厅的各项指标评分数据，从而更好地了解餐厅运营状况，提升服务质量。

## 📊 功能特性

- **餐厅评分录入**：支持录入多个餐厅的各项指标评分
- **实时数据分析**：自动计算综合评分和各类指标的平均分、最高分等统计信息
- **可视化图表展示**：使用雷达图展示各餐厅在不同维度的表现
- **时间筛选功能**：支持按日期范围筛选和查看数据
- **数据导出功能**：支持将数据导出为CSV格式
- **深色主题界面**：优化视觉体验，适合长时间使用

## 🚀 技术栈

- **前端技术**：HTML5, CSS3, JavaScript
- **UI框架**：Tailwind CSS v3
- **图标库**：Font Awesome
- **数据可视化**：Chart.js
- **响应式设计**：支持移动端和桌面端

## 📋 安装说明

### 本地开发

1. 克隆本仓库到本地
```bash
git clone https://github.com/your-username/restaurant-score-calculator.git
cd restaurant-score-calculator
```

2. 启动本地服务器（有多种方式）

   使用Python：
   ```bash
   python -m http.server 8080
   ```

   或使用Node.js：
   ```bash
   npx http-server -p 8080
   ```

3. 在浏览器中访问 `http://localhost:8080`

## 🌐 GitHub Pages 部署

### 手动部署步骤

1. **确保所有资源使用CDN引用**
   - 项目中的Tailwind CSS、Font Awesome和Chart.js等库已使用CDN链接
   - 确保没有本地依赖资源路径问题

2. **提交代码到GitHub仓库**
   ```bash
   git add .
   git commit -m "部署到GitHub Pages"
   git push origin main
   ```

3. **在GitHub仓库中配置Pages**
   - 打开仓库 → Settings → Pages
   - 在"Source"部分，选择：
     - Branch: `main`
     - Folder: `/ (root)`
   - 点击"Save"

4. **等待部署完成**
   - GitHub Pages通常会在几分钟内完成部署
   - 部署完成后，可以通过 `https://your-username.github.io/restaurant-score-calculator/` 访问

### 自定义域名配置（可选）

如果需要使用自定义域名：

1. 在GitHub Pages设置中添加自定义域名
2. 在域名DNS设置中添加CNAME记录指向 `your-username.github.io`

## 📱 浏览器支持

- Chrome 90+ (推荐)
- Firefox 88+
- Safari 14+
- Edge 90+

## 📝 使用说明

1. 在"餐厅评分录入"部分添加新的餐厅评分记录
2. 在"数据分析"部分查看各餐厅的评分统计信息
3. 在"图表展示"部分查看雷达图可视化数据
4. 使用"数据筛选"功能按日期范围查看数据
5. 使用"数据导出"功能导出CSV格式的数据

## 🛡️ 安全说明

- 本系统为前端应用，所有数据仅存储在浏览器的本地存储中
- 建议定期导出数据进行备份
- 如部署到公共网络，请注意数据隐私保护

## 📄 许可证

本项目仅供山西大学后勤管理处饮食文化中心使用。

## 📞 联系我们

山西大学后勤管理处饮食文化中心

---

*最后更新时间：2024年*
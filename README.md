### 个人信息
--------------------------
- **姓名**: 李文星
- **电话**: 13689526320 
- **邮箱**: tappanmorris@outlook.com 
- **地址**: 深圳宝安
- **GitHub**: [Nemausa](https://github.com/Nemausa)
- **LVGL项目展示**: [查看项目](https://github.com/Nemausa/resume/blob/master/lvgl_project_introduction.md)

### 求职意向
--------------------------
- **求职岗位**: C++程序员（嵌入式开发方向）
- **期望薪资**: 面议

### 教育背景
--------------------------
- **学历**: 本科
- **学校**: 江西师范大学
- **专业**: 软件工程
- **毕业时间**: 2016
- **相关课程**: 数据结构、操作系统、嵌入式系统设计

### 技能
--------------------------
- **深厚的C++基础**: 掌握C++的核心特性，包括面向对象编程、模板编程、RAII、STL和智能指针等。
- **LVGL、Qt 和 Flythings 开发**：熟悉LVGL界面设计与事件处理、Qt图形界面开发与信号槽机制、Flythings平台开发流程。
- **掌握CMake**: 能够编写复杂的`CMake`构建脚本，处理多平台、多模块项目，配置编译选项和管理依赖关系
- **Visual Studio Code配置**: 熟练使用Visual Studio Code进行C++开发，能够配置调试器、编辑器和扩展插件，以提高开发效率。
- **Vim/Neovim熟练**：精通使用Vim或Neovim进行C++开发，配置插件如YouCompleteMe或coc.nvim来提升代码补全和导航能力。
- **面向对象设计**：能够设计和实现复杂的面向对象系统，应用设计模式（如单例模式、工厂模式、观察者模式等）来解决实际问题。
- **内存管理**：精通C++中的内存管理技术，能够使用智能指针、手动内存管理和内存池来优化程序性能和防止内存泄漏。
- **调试技能**：熟练使用gdb、lldb等调试工具进行复杂的C++调试，能够排查和解决运行时错误和崩溃问题。
- **跨平台开发**：有在不同操作系统（如Windows、Linux、macOS、FreeRTOS）上开发和调试C++代码的经验，能够处理平台特定的差异和问题。
- **版本控制**：能够使用Git进行版本控制，熟悉分支管理、代码合并和解决冲突的技巧。

### 项目经验
--------------------------

#### 冰淇淋项目 (基于开阳630hv100芯片)
- **项目描述**: 该项目旨在设计、开发和集成一套汽车仪表系统，用于在驾驶过程中提供关键的车辆信息显示和与驾驶员的交互。系统的目标是通过优化显示模块、提升响应速度和安全性，增强驾驶体验。
- **负责模块**:
  - **显示模块**：负责汽车仪表盘的实时显示，包括车辆状态、速度、油量等关键数据。
  - **MCU（微控制器）**：处理与车辆传感器的数据通信和显示数据的传输。
  - **SOC升级**：进行系统升级，保证更好的性能和资源管理。
  - **蓝牙和串口通信**：实现蓝牙设备和仪表系统的连接，同时通过串口进行调试和通信。
  - **信号灯显示与报警**：管理汽车信号灯的显示，并在必要时触发报警。
  - **主题和语言切换**：为系统增加主题自定义和多语言支持功能，满足不同用户需求。
- **使用技术**:
  - **C**：核心功能和底层驱动开发。
  - **FreeRTOS**：实现实时任务调度和多任务管理。
  - **LVGL**：用于创建图形界面，实现高效的UI显示。
- **成果**: 
  - 提高了系统的响应速度，使仪表盘显示更加流畅。
  - 优化了内存管理，减少了内存消耗，提升了系统稳定性。


#### 大冶项目 (基于全志T113芯片)

- **项目描述**: 旨在提供先进的用户界面和功能，提升用户体验，并确保操作的安全性。

- **主要功能**:
  - 驾驶辅助系统
  - 信息娱乐系统
  - 通信系统

- **负责模块**:
  - **信号灯显示与报警**: 实现了复杂的信号灯报警功能，提高了系统的警示能力。
  - **主题切换**: 开发了主题切换功能，增强了用户界面的个性化和可定制性。
  - **串口通信**: 实现了稳定的串口通信，确保了设备间的可靠数据传输和互动.

- **使用技术**:
  - **C++**: 用于实现核心功能和模块的开发。
  - **框架**: 使用了特定框架来提升系统的稳定性和方便修改。

- **成果**:
  - 成功集成复杂的信号灯报警功能，显著提升了系统的稳定性和可靠性。
  - 通过框架的使用，提高了系统的稳定性和维护性，便于后续的功能修改和扩展。


#### 空调选型服务器
- **项目描述**: 独立开发的一套高度并发的空调选型系统，支持多用户在线实时选型。通过输入用户的关键需求参数，如房间面积、气候条件、预算等，系统智能推荐最优空调方案。系统采用先进的分布式架构，能够在海量用户同时访问时，保证高效的任务分发与处理，并通过集群化设计提供弹性扩展能力，确保系统在高并发环境下的稳定运行。
- **使用技术**:
  - **C++**: 核心业务逻辑和高性能并发处理。
  - **SQL Server**: 后端数据库，用于存储用户数据及选型规则。
  - **Python**: 用于自动化任务、数据分析以及部分业务流程脚本化。
  - **IOCP**: 基于I/O完成端口技术，实现高效网络通信，支持数万用户的并发请求处理。
  - **分布式架构**: 采用微服务架构，系统的各个模块通过RPC进行相互通信，确保了服务间的低耦合性和高可扩展性。
  - **集群技术**: 使用集群化部署，将计算和存储任务分散到多个节点，支持负载均衡、故障切换、动态扩展等高级功能，显著提升了系统的容错性和整体吞吐量。
  - **Token认证**: 采用基于Token的认证机制，确保多用户在线操作的安全性和数据完整性。
- **成果**:
  - **系统稳定性大幅提升**：通过分布式架构和集群化部署，系统具备极强的容错能力和弹性扩展性。
  - **优化系统升级速度**：采用热更新和滚动升级策略，在不中断服务的情况下完成系统的无缝升级。
  - **性能提升**：显著提高了并发处理能力，系统可支持数万用户同时在线选型，处理速度较传统单服务器架构提升了X倍。


### 工作经历
--------------------------

#### 均锐科技有限公司  
- **职位**: 软件工程师  
- **工作时间**: 2023年6月 - 2024年9月  
- **工作描述**:  
  在均锐科技负责T113 Linux平台上的仪表产品开发，涉及从UI设计到底层性能优化的全流程开发工作。深入参与产品的调试与测试，负责解决关键的性能瓶颈，确保系统在复杂应用场景下的稳定性与流畅性。通过对底层代码的优化和内存管理的改进，提升了系统整体性能，并且与硬件团队紧密协作，保证产品软硬件的完美集成。  
- **成果**:
  - **开机自检速度优化**: 成功解决了复杂开机自检过程中遇到的性能瓶颈，将自检时间优化至2.5秒内，显著提升了用户体验。
  - **内存占用问题解决**: 通过精细化管理图片加载和渲染流程，成功解决了图片占用内存过高的问题，使系统运行更加高效，减少了崩溃风险。
  - **系统稳定性和质量提升**: 在项目周期内持续调优系统，确保产品在各种苛刻的工作环境下保持高稳定性，进一步提高了产品的市场竞争力。


#### 车可讯科技有限公司  
- **职位**: 软件工程师  
- **工作时间**: 2020年7月 - 2023年5月  
- **工作描述**:  
  负责开发和维护汽车仪表系统，深入参与核心功能设计与实现，主要包括性能优化、系统稳定性提升和关键Bug修复工作。通过系统架构的优化和代码性能调优，确保了仪表系统的高效运行与可靠性。与产品团队和硬件团队紧密合作，确保软件与硬件的无缝衔接，持续推动用户体验的提升。
- **成果**:
  - **系统性能优化**: 通过代码优化，系统响应速度提升了20%，内存使用减少了15%，显著增强了系统整体表现。
  - **关键性Bug修复**: 成功修复了界面切换时崩溃的关键Bug，系统崩溃率显著降低，提升了系统的稳定性和用户满意度。
  - **按键电压滤波实现**: 成功实现了按钮的电压滤波功能，显著提高了按键响应的稳定性，优化了用户体验和交互流畅度。


#### 麦克维尔空调有限公司  
- **职位**: 软件工程师  
- **工作时间**: 2017年6月 - 2020年6月  
- **工作描述**:  
  在麦克维尔空调担任核心软件工程师，全面负责空调选型系统的设计与优化。主导系统架构改进与性能优化，确保系统在高并发环境下的稳定运行。深入参与解决复杂技术问题，从前端交互到后端数据库的全栈开发，并与跨部门团队密切合作，制定技术解决方案。编写详细的技术文档，为系统维护与升级提供坚实支持，确保代码的可维护性与扩展性。
- **成果**:
  - **系统错误率大幅降低**: 通过深入分析并修复系统中的瓶颈和潜在问题，成功将系统错误率降低了90%，显著提升了系统的稳定性。
  - **客户满意度显著提升**: 通过优化用户体验和系统响应速度，客户满意度大幅提高，为公司创造了更高的市场口碑和客户留存率。
  - **性能优化**: 引入分布式计算架构与智能缓存技术，使系统处理效率提升了5倍，满足了日益增长的用户需求。
  - **自动化升级流程**: 构建自动化升级和部署流程，减少了系统维护时间，实现了快速迭代和版本发布，提高了开发效率与系统可用性。



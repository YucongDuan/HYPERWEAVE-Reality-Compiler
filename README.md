# DIKWP‑Mesh 4.1 HYPERWEAVE Reality Compiler

**中文工程句柄：** 多意图因果世界线、形式反例与证明携带现实实验系统  
**版本：** 1.0.0  
**运行方式：** 离线优先、Python 标准库、SQLite、原生 JavaScript  
**默认端口：** `127.0.0.1:8822`

> “HYPERWEAVE”“Reality Compiler”“世界线”“现实实验”均为工程句柄。它们不构成对“现实”“世界”“未来”、智能、意识、安全、价值或任何外部概念的普遍定义。

## 1. 交付对象

HYPERWEAVE 将一组**来源化表达、多主体目的、权限边界、有限状态变量、声明式因果转移、形式义务、恢复关系和结算表达**编译为一个可检查的证明胶囊。它提供：

- 4 个可直接运行的有限合成场景、8 条任务候选；
- 13 个段玉聪公开项目与本地前置系统的来源化模块接口；
- 129 条策展项目关系记录，对应观察时点 GitHub 账户页显示的 220 个公开仓库；
- 显式状态空间展开与非确定性分支；
- 不变量、有限步长活性、权限与可逆性义务检查；
- 使义务失败的最短已发现反例轨迹；
- 多主体目的逐项结果，不在没有明确权重时合成总分；
- 节点删除式意图条件化问题核；
- 全部 25 个 DIKWP×DIKWP 有向关系地址及当前激活子网；
- 预注册观察结算；
- 脱敏联邦证据胶囊、完整性验证和外部权威不继承；
- SQLite 乐观修订控制、PBKDF2 本地账号和 SHA‑256 链式审计；
- OpenAPI 3.1、8 个 JSON Schema、浏览器工作台和命令行接口。

本系统不执行任何现实工具、医疗设备、公共权利决定、数据跨境传输、自动化裁员或其他高影响动作。

## 2. 直接运行

要求 Python 3.10 或更高版本。运行时不需要安装第三方 Python 包。

```bash
unzip DIKWP_Mesh_4_1_HYPERWEAVE_Reality_Compiler_v1.0.0.zip
cd DIKWP_Mesh_4_1_HYPERWEAVE_Reality_Compiler_v1.0.0
python run.py serve
```

浏览器打开：

```text
http://127.0.0.1:8822
```

默认演示登录：

```text
用户名：admin
密码：mesh41-demo
```

其他演示账号均使用密码 `mesh41-demo`：

| 用户名 | 工作流角色 |
|---|---|
| `admin` | 系统管理员 |
| `compiler` | 现实实验编译角色 |
| `auditor` | 形式验证与证据审计角色 |
| `settler` | 现实观察与结算角色 |
| `affected` | 受影响方代理角色，只读 |
| `federation` | 联邦节点交换角色 |

上述账号只是本地演示工作流标签，不代表真实身份、机构授权、执业资格或电子签名。

### Docker

```bash
docker compose up --build
```

## 3. 命令行

### 编译全部内置任务

```bash
python run.py demo --trials 500 --max-states 20000
```

### 编译单一任务

```bash
python run.py compile \
  --scenario scenario_civic_benefit_access \
  --mission mission_assistive_with_appeal \
  --trials 1000 \
  --seed 20260722 \
  --max-states 20000
```

### 查看系统状态与审计链

```bash
python run.py summary
python run.py verify-audit
```

### 执行完整 QA

```bash
python run.py qa
```

## 4. 核心运行链

```text
来源化表达
  → 多主体目的合同
  → 权限与禁止结果信封
  → 声明式因果动作
  → 显式状态空间与非确定性分支
  → 不变量 / 活性 / 权限 / 可逆性检查
  → 最小反例轨迹
  → 非标量目的结果表面
  → 反事实删除问题核
  → DIKWP×DIKWP 激活关系网
  → 证明携带胶囊
  → 来源化观察结算
  → 脱敏联邦证据交换
```

“编译”表示将声明式材料转化为有限可检查对象；它不表示现实世界已经被完整表示，也不表示系统发现了普遍因果真理。

## 5. 状态不是单一分数

每次编译分别给出：

```text
Closure State:
ADMISSIBLE / UNSETTLED / CONTESTED / BLOCKED / KILLED

Semantic Stability:
S4 / S3 / S2 / S1 / S0

Mesh Examination:
M4 / M3 / M2 / M1 / M0

Evidence Reliability:
Solid / Supported / Provisional / Borrowed /
Hollow / Contested / Blocked
```

`ADMISSIBLE` 只表示：在当前声明的有限状态模型、路径、义务、来源和状态上限内，没有发现足以触发更高门控的失败。它不是行动建议、现实授权、安全认证或有效性证明。

## 6. 内置有限场景

| 场景 | 可通过任务 | 对照任务 | 主要硬门 |
|---|---|---|---|
| 公共服务辅助分流 | 人工复核与申诉闭环 | 自治拒绝批处理 | 权利影响决定、服务底线、隐私 |
| 自动化转型与收入底线 | 红利、分阶段自动化、人工匹配、申诉 | 无收入底线的快速自动化 | 收入底线、申诉、不可逆影响 |
| 人机协同康复设备 | 前置检查、人工在环、遥测 | 设备自治强度更新 | 同意、急停、人工控制、伤害边界 |
| 主权研究证据交换 | 本地脱敏与独立复现 | 原始数据外传 | 数据驻留、去标识、外部权威不继承 |

所有场景均为合成运行对象，不对应真实个人、机构、患者、劳动者、行政个案或数据集。

## 7. 证明胶囊内容

每个胶囊包含：

- 场景和修订哈希；
- 原始目的表达、来源状态、主体和验收/否决表达；
- 任务序列、授权授予、禁止结果、停止条件和恢复动作；
- 选用模块及其公开来源、观察时间、局限和清单哈希；
- 状态空间展开摘要、结果范围、证明义务和反例；
- 抽样分布，明确标记为描述性合成抽样；
- 意图条件化问题核；
- DIKWP×DIKWP 关系网；
- 运行环境、随机种子、状态上限；
- 证书范围、哈希和开放残差；
- 明确的非主张列表。

## 8. 数据与目录

```text
hyperweave/             Python 运行时
web/                    原生浏览器工作台
data/scenarios/         有限合成场景
data/module_manifests/  来源化模块接口
schemas/                JSON Schema Draft 2020-12
examples/               运行后生成的示例
outputs/                QA 与演示输出
runtime/                本地 SQLite，发行包默认为空
openapi.yaml             OpenAPI 3.1
```

## 9. 关键文档

- `docs/00_public_portfolio_research.md`：公开项目组合研究方法与证据边界；
- `docs/01_intent_conditioned_gap_kernel.md`：为何关键缺口是跨模块形式反例编译层；
- `docs/02_system_architecture.md`：系统架构；
- `docs/03_bounded_formal_model.md`：有限状态、证明义务和反例语义；
- `docs/04_scenario_catalog.md`：四个场景与八条任务；
- `docs/05_portfolio_module_integration.md`：13 个模块接口；
- `docs/06_data_api_and_operations.md`：数据库、API、CLI 和部署；
- `docs/07_governance_and_nonclaims.md`：治理、非主张和失效边界；
- `docs/08_threat_model.md`：威胁模型；
- `docs/09_validation_plan.md`：验证范围。

## 10. 许可与来源边界

本交付中的原创代码采用 Apache License 2.0。段玉聪公开仓库的名称、README 能力表达和 URL 仅作为来源化接口资料保留；本交付未复制这些仓库的源码，也不声称得到作者认可、共同开发或官方纳入其项目组合。

联邦交换的固定边界字段为 `authority_inherited=false`。

## 11. 自动化验证

最终发行前的本地 QA 共执行 `1222` 项检查，结果为 `1222/1222` 通过，覆盖：

- Python 与 JavaScript 语法、浏览器控件绑定和安全头；
- 4 个场景、8 条任务、13 个模块清单、129 条项目关系记录及 25 个关系通道；
- JSON、Draft 2020-12 Schema 和 OpenAPI 结构；
- 全部任务的有界编译、反例、权限、活性、可逆性、问题核和非标量目的表面；
- 联邦包脱敏、哈希/HMAC 演示、篡改检测和 `authority_inherited=false`；
- 观察结算、乐观修订冲突、审计链、HTTP 登录、编译、导出、导入和静态工作台。

报告位于 `outputs/qa_summary.json`。该结果只验证本地实现和声明的合成不变量，不证明公开仓库外部能力、现实因果完整性、现实授权、作者认可或现场有效性。

# OCR_Server

基于 [MinerU v2.0.5](https://github.com/opendatalab/MinerU/releases/tag/v2.0.5) 的二次开发，提供基于MinerU 1.0的文件解析 FastAPI 服务。

## 功能介绍
To do list:
本项目在原始 MinerU 2.0 版本基础上，补充并升级了以下特性：  
1. 原 MinerU 2.0 版本仅提供命令行启动（类似 sglang 方式），不支持 HTTP 接口；  
2. 本项目新增基于 FastAPI 的文件解析服务，使解析流程可通过 RESTful API 调用；  
3. 兼容多种文件格式，包括 CSV、XLSX、TXT；  
4. 进一步升级 2.0 版服务，使其同时支持 DOC、DOCX、PPTX 等 Office 文档解析。


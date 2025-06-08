<div id="header" align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=00ffc7&height=300&section=header&text=IRO's%20Universe&fontSize=70&animation=twinkling&fontColor=ffffff&fontAlignY=38" alt="Header"/>
</div>

<div style="text-align: center; margin-top: 20px; margin-bottom: 20px;">
  <h2 style="font-weight: 900; font-size: 2.2em; color: #00ffc7;">
    End-to-End AI System Architect & MLOps Engineer
  </h2>
  <p style="font-size: 1.1em; color: #4a5568;">
    초거대 AI 모델의 연구 개발부터 안정적인 프로덕션 운영까지, 전체 생명주기를 포괄하는<br/>지능적이고 자동화된, 그리고 스스로 발전하는 머신러닝 시스템을 설계하고 구축합니다.
  </p>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=00ffc7&height=70&section=title&width=100%" alt="Divider"/>

### **🚀 Core Technical Competencies**

<table width="100%" cellspacing="15" cellpadding="0" style="border: none;">
  <tr valign="top">
    <td width="33.3%">
      <div style="background-color: #161b22; border: 3px solid #00ffc7; border-radius: 15px; padding: 25px; height: 100%;">
        <h3 align="center" style="font-weight: bold; color: #00ffc7;">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" alt="PyTorch" width="28" height="28"/>
          Large-Scale AI & Deep Learning
        </h3>
        <ul style="list-style-type: '🤖 '; padding-left: 20px; font-size: 15px; line-height: 1.9; color: #c9d1d9;">
          <li><b>분산 학습/파인튜닝</b>: <strong>DeepSpeed (ZeRO 1-3, Offload)</strong>, <strong>PyTorch DDP</strong>, <strong>TF MirroredStrategy</strong> 등 분산 전략을 `config.yaml` 기반으로 완벽히 추상화하여 수십억 파라미터 모델을 안정적으로 학습시킵니다.</li>
          <li><b>고급 모델 최적화</b>: <strong>Quantization (QAT, AWQ/GPTQ/HQQ, 4/8-bit)</strong>, <strong>Pruning</strong>, <strong>Knowledge Distillation</strong>, <strong>Low-Rank Factorization</strong> 등 최신 경량화 기법을 `auto_compress` 파이프라인으로 통합하여 추론 효율을 극대화합니다.</li>
          <li><b>지능형 AutoML 시스템</b>: <strong>Optuna</strong>와 <strong>메타 러닝</strong>을 결합, 데이터 특성 기반으로 탐색 공간과 Sampler/Pruner를 동적으로 추천합니다. OOM 등 자원 부족 발생 시 자동 복구(Self-healing) 로직을 포함한 지능형 HPO 파이프라인을 구축합니다.</li>
        </ul>
      </div>
    </td>
    <td width="33.3%">
      <div style="background-color: #161b22; border: 3px solid #00ffc7; border-radius: 15px; padding: 25px; height: 100%;">
        <h3 align="center" style="font-weight: bold; color: #00ffc7;">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-plain.svg" alt="Kubernetes" width="28" height="28"/>
          MLOps & System Architecture
        </h3>
        <ul style="list-style-type: '🛠️ '; padding-left: 20px; font-size: 15px; line-height: 1.9; color: #c9d1d9;">
          <li><b>워크플로우 오케스트레이션</b>: <strong>Airflow</strong>, <strong>Kubeflow</strong>와 완벽히 연동되도록 `--pipeline` 인자를 통해 파이프라인 단계를 개별적으로 실행할 수 있습니다.</li>
          <li><b>플러그인 기반 아키텍처</b>: 모델, 데이터 로더, 콜백, 파이프라인 단계까지 모든 구성 요소를 동적으로 탐색 및 등록합니다. `new_plugin.py` 유틸리티로 개발자 경험을 극대화한, 프레임워크 비종속적 시스템을 설계합니다.</li>
          <li><b>데이터 엔지니어링 및 관리</b>: <strong>Dask/Petastorm</strong>을 활용한 대용량 분산 데이터 처리를 지원하며, <strong>DVC</strong>와 연동하여 데이터 버전 관리 및 계보 추적(Lineage) 시스템을 구축합니다.</li>
          <li><b>품질 및 안정성</b>: <strong>pytest</strong> 기반의 단위, 통합, E2E 테스트 자동화는 물론, 예기치 못한 실패 상황을 시뮬레이션하는 <strong>카오스 엔지니어링(Chaos Engineering)</strong> 실험을 통해 시스템의 회복탄력성을 검증합니다.</li>
        </ul>
      </div>
    </td>
    <td width="33.3%">
      <div style="background-color: #161b22; border: 3px solid #00ffc7; border-radius: 15px; padding: 25px; height: 100%;">
        <h3 align="center" style="font-weight: bold; color: #00ffc7;">
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/graphql/graphql-plain.svg" alt="GraphQL" width="28" height="28"/>
          Next-Gen MLOps & System Intelligence
        </h3>
        <ul style="list-style-type: '💡 '; padding-left: 20px; font-size: 15px; line-height: 1.9; color: #c9d1d9;">
          <li><b>AI 기반 시스템 자동화 (GenesisEngine)</b>: <strong>GNN</strong>으로 과거 모든 실험의 관계를 학습하여 최적의 파이프라인을 '추천'하고, <strong>LLM API</strong>로 필요한 플러그인과 테스트 코드를 '자동 생성' 및 '자동 검증'하는 <strong>자가 개선/확장(Self-Improving/Extending) 시스템</strong>을 설계합니다.</li>
          <li><b>불변 감사 추적 (Immutable Audit)</b>: 코드, 데이터, 환경의 해시 값과 실험 결과를 <strong>해시 체인(Hash Chain)</strong>으로 연결하여 `experiment_blockchain_ledger.jsonl` 파일에 기록합니다. 이를 통해 모든 산출물의 무결성을 보장하고 금융/의료 수준의 <strong>절대적 재현성</strong>을 확보합니다.</li>
          <li><b>하드웨어 인식 최적화 (Co-Design)</b>: 타겟 하드웨어의 실제 추론 속도(Latency)와 비용까지 고려하는 <strong>Hardware-Aware NAS</strong> 및 모델 컴파일(<strong>ONNX/TensorRT/OpenVINO</strong>)을 통해 소프트웨어를 하드웨어 수준까지 최적화합니다.</li>
          <li><b>양방향 AI 개발 환경</b>: <strong>What-if 시뮬레이션</strong>으로 실험 전 결과를 예측하고, Drag & Drop 방식의 <strong>Visual Pipeline Composer</strong> 및 모델의 내부 동작을 3D로 시각화하는 <strong>Model Autopsy</strong>를 제공하여 개발 생산성을 극대화합니다.</li>
        </ul>
      </div>
    </td>
  </tr>
</table>
<br>

### ✨ **Representative Project Experience**
<details open>
<summary>
  <strong style="font-size: 1.2em; color: #1f2328;">
    대표 프로젝트: <자가 개선형 End-to-End AI 개발 자동화 및 MLOps 플랫폼>
  </strong>
</summary>
<div style="background-color: #f6f8fa; border: 4px solid #00ffc7; border-radius: 15px; padding: 25px; margin-top: 10px;">
  <p style="font-size: 1.1em;">
    초거대 AI 모델의 연구 개발부터 배포, 운영까지 전 과정을 자동화하는 MLOps 플랫폼을 A-Z까지 직접 설계하고 리드 개발했습니다. 이 플랫폼은 개발자의 개입을 최소화하고, 과거의 모든 실험으로부터 학습하여 스스로 더 나은 결정을 내리는 '자가 개선(Self-Improving)' 시스템을 목표로 합니다.
  </p>
  <h4 style="font-weight: bold; color: #333;">주요 성과 및 구현 기능</h4>
  <ul style="list-style-type: '🏆 '; padding-left: 20px; font-size: 15px; line-height: 1.8;">
    <li><strong>GenesisEngine 개발 (AI 기반 자동화)</strong>: GNN 메타러닝으로 데이터셋에 최적화된 파이프라인을 '추천'하고, LLM을 통해 필요한 플러그인과 테스트 코드를 '자동 생성' 및 `pytest`로 '자동 검증' 후 통합하는 Auto-Pilot 시스템의 핵심 엔진을 구현했습니다.</li>
    <li><strong>지능형 최적화 파이프라인 구축</strong>: 최신 양자화(AWQ/GPTQ/HQQ), Pruning, Distillation 등 모델 압축 기법을 `auto_compress` 파이프라인으로 통합하여, 모델 성능 저하를 최소화하면서 추론 비용을 <strong>최대 75%</strong>까지 절감하는 자동화 파이프라인을 완성했습니다.</li>
    <li><strong>절대적 신뢰성 및 재현성 확보</strong>: 코드/데이터/환경의 해시 스냅샷(`pipeline_snapshot.json`)은 물론, 모든 실험의 최종 결과를 <strong>해시 체인 기반 원장</strong>에 기록하여 위변조를 원천 방지하고, 언제든 <strong>100% 동일한 결과</strong>를 재현하는 시스템을 구축했습니다.</li>
    <li><strong>통합 대시보드 및 What-if 시뮬레이션</strong>: Streamlit을 활용하여 실시간 모니터링, 데이터/모델 심층 분석(XAI/Autopsy), 그리고 파라미터 변경 시 예상되는 성능/비용을 미리 시뮬레이션 해주는 양방향 웹 대시보드를 개발했습니다.</li>
  </ul>
  <h4 style="font-weight: bold; color: #333;">적용 기술 스택</h4>
  <p>
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/> <img src="https://img.shields.io/badge/DeepSpeed-007ACC?style=for-the-badge" alt="DeepSpeed"/> <img src="https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Airflow"/> <img src="https://img.shields.io/badge/DVC-13ADC7?style=for-the-badge&logo=dvc&logoColor=white" alt="DVC"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"/>
  </p>
</div>
</details>
<br>

### 💬 **Development Philosophy**
<div style="background-color: #161b22; border-left: 6px solid #00ffc7; border-radius: 10px; padding: 25px; color: #c9d1d9;">
  <p style="font-style: italic; font-size: 1.1em;">견고한 소프트웨어 공학 원칙 위에서 AI 기술이 가장 빛을 발한다고 믿습니다. 저의 개발 철학은 <strong>재현 가능성(Reproducibility)</strong>, <strong>확장성(Scalability)</strong>, <strong>자동화(Automation)</strong>라는 세 가지 키워드로 요약할 수 있습니다. 저는 여기서 한 걸음 더 나아가, 과거의 경험으로부터 스스로 학습하여 미래의 결정을 최적화하는 <strong>자가 개선 시스템(Self-Improving System)</strong>을 설계하여 AI 모델이 지속적으로 발전할 수 있는 기반을 마련합니다.</p>
</div>

### 📫 **Contact Information**
<p align="center">
  <a href="mailto:ATMOSPHERE.SHIRO@gmail.com"><img src="https://img.shields.io/badge/Gmail-ATMOSPHERE.SHIRO-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  &nbsp;
  <a href="https://linkedin.com/in/your-linkedin-id"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

<div id="footer" align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=00ffc7&height=200&section=footer" alt="Footer"/>
</div>

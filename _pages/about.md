---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 🔋 About Me

Currently, I am completing my last year of Ph.D degree at the Center for Advanced Electrical Machines & Drives (CAEMD), Huazhong University of Sci. & Tech. (HUST), advised by Professor [Ronghai Qu](https://ieeexplore.ieee.org/author/37278880800).

I am currently looking for any opportunities for a postdoc and research assistant position in the field of power electronics or electrical machine.

My research includes high power density synchronous machine nonlinear system identification, sensorless control, real-time thermal modelling and temperature estimation. I have published 10+ papers on IEEE Transactions and top EE conferences <a href='https://scholar.google.com/citations?user=s6tTk9wAAAAJ'><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FZirui24%2FZirui24.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. 

<html>
    <table style="margin-left: auto; margin-right: auto;">
        <tr>
            <td>
                <b>Educations</b> <br>
            </td>
            <td>
                <b>Research Interset</b> <br>
            </td>
        </tr>
        <tr>
            <td>
                🎓 2019.09 - 2025.06, PhD, Huazhong University of Sci. & Tech. (HUST), Hubei <br>
                <br>
                🎓 2015.09 - 2019.06, Undergraduate, Hunan University, Hunan. <b>GPA: 3.89/4 RANK: 2/263</b> <br>
            </td>
            <td>
                <b>system identification & control</b> <br>
                <b>thermal analysis</b> <br>
                <b>electrical machine design</b> <br>
            </td>
        </tr>
    </table>
</html>

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

#### Nonlinear Parameter Identification & Control

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

- ``IEEE TPE`` [Improved small-signal injection-based online multiparameter identification method for IPM machines considering cross-coupling magnetic saturation](https://ieeexplore.ieee.org/abstract/document/9835132) 
**Zirui Liu**, Xinggang Fan, Wubin Kong, Longfei Cao, Ronghai Qu
[![](https://img.shields.io/github/stars/Zirui24/PMSM_Elec.ANDMech.ParamEst?style=social&label=Code+Stars)](https://github.com/Zirui24/PMSM_Elec.ANDMech.ParamEst)
[![](https://img.shields.io/badge/PDF-8A2BE2)](https://www.researchgate.net/profile/Zirui-Liu-15/publication/362186000_Improved_Small-Signal_Injection-Based_Online_Multi-Parameter_Identification_Method_for_IPM_Machines_Considering_Cross-Coupling_Magnetic_Saturation/links/64c8e7f9b7d5e40f331955a1/Improved-Small-Signal-Injection-Based-Online-Multi-Parameter-Identification-Method-for-IPM-Machines-Considering-Cross-Coupling-Magnetic-Saturation.pdf)

- ``IEEE TIE`` [Online Multi-Parameter Observation of IPM Machine with Reconstructed Nonlinear Small-Signal Model Based on Dual EKF](https://ieeexplore.ieee.org/abstract/document/10083049) 
**Zirui Liu**, Wubin Kong, Xinggang Fan, Ronghai Qu
[![](https://img.shields.io/github/stars/Zirui24/PMSM_Elec.ANDMech.ParamEst?style=social&label=Code+Stars)](https://github.com/Zirui24/PMSM_Elec.ANDMech.ParamEst)
[![](https://img.shields.io/badge/PDF-8A2BE2)](https://www.researchgate.net/profile/Zirui-Liu-15/publication/369569211_Online_Multi-Parameter_Observation_of_IPM_Machine_with_Reconstructed_Nonlinear_Small-Signal_Model_Based_on_Dual_EKF/links/6426c6b3315dfb4ccec1091e/Online-Multi-Parameter-Observation-of-IPM-Machine-with-Reconstructed-Nonlinear-Small-Signal-Model-Based-on-Dual-EKF.pdf)

- ``IEEE TTE`` [A Novel Adaptive Nonlinear Reaching Law for DC-link Voltage Control of DC-biased Vernier Reluctance Generator](https://ieeexplore.ieee.org/abstract/document/10505008) 
Zimin Li, Wubin Kong, **Zirui Liu**, Bohan Shen, Ronghai Qu

#### AC Machine Position Sensorless Control

- ``IEEE TPE`` [Analytical Approach for Position Observation Error Correction in IPMSM Sensorless Drives Using Online Multi-Parameter Estimation](https://ieeexplore.ieee.org/abstract/document/9835132) 
**Zirui Liu**, Bohan Shen, Wubin Kong, Xinggang Fan, Kai Peng, Ronghai Qu
[![](https://img.shields.io/github/stars/Zirui24/SynMotor_FSO_ParamEst?style=social&label=Code+Stars)](https://github.com/Zirui24/SynMotor_FSO_ParamEst)
[![](https://img.shields.io/badge/PDF-8A2BE2)](https://www.researchgate.net/profile/Zirui-Liu-15/publication/379939779_Analytical_Approach_for_Position_Observation_Error_Correction_in_IPMSM_Sensorless_Drives_Using_Online_Multi-Parameter_Estimation/links/662902af06367b604d489c46/Analytical-Approach-for-Position-Observation-Error-Correction-in-IPMSM-Sensorless-Drives-Using-Online-Multi-Parameter-Estimation.pdf)

- ``ECCE 2023`` [Online Multiparameter Estimation with Position Error Correction for Unified Synchronous Machine Sensorless Drives](https://ieeexplore.ieee.org/abstract/document/10362894) 
**Zirui Liu**, Wubin Kong, Xinggang Fan, Fei Wang, Ronghai Qu
[![](https://img.shields.io/github/stars/Zirui24/AdaptParamOb_ACMotorSensorlessControl?style=social&label=Code+Stars)](https://github.com/Zirui24/AdaptParamOb_ACMotorSensorlessControl)
[![](https://img.shields.io/badge/PDF-8A2BE2)](https://www.researchgate.net/publication/376963793_Online_Multiparameter_Estimation_with_Position_Error_Correction_for_Unified_Synchronous_Machine_Sensorless_Drives)

- ``CIEEC 2023`` [Sensorless Control and Inductance Parameter Identification of PMSM Based on Two-Orientation High-Fequency Square Wave Injection](https://ieeexplore.ieee.org/abstract/document/10166793) 
Haowen Zheng, Jiarui Hao, Ming Zha, **Zirui Liu**, Wubin Kong

#### Real-time Thermal Modelling and Temperature Estimation

- ``IEEE TIA`` [Comparison of heat transfer characteristics of the hollow-shaft oil cooling system for high-speed permanent magnet synchronous machines](https://ieeexplore.ieee.org/abstract/document/9835132) 
Runyu Wang, Xinggang Fan, Dawei Li, Ronghai Qu, **Zirui Liu**, Lei Li

- ``IEEE TIE`` [Improved LPTN-Based Online Temperature Prediction of Permanent Magnet Machines By Global Parameter Identification](https://ieeexplore.ieee.org/abstract/document/9905476/) 
Longfei Cao, Xinggang Fan, Dawei Li, Wubin Kong, Ronghai Qu, **Zirui Liu**

- ``IEEE TEC`` [A Computationally Efficient Semi-Analytical Method for Circulating Current Loss of High Speed Permanent Magnet Machines](https://ieeexplore.ieee.org/abstract/document/10243050/) 
Lei Li, Xinggang Fan, **Zirui Liu**, Dawei Li, Tianjie Zou, Xiaoxue Chen, Ronghai Qu
[![](https://img.shields.io/badge/PDF-8A2BE2)](https://nottingham-repository.worktribe.com/preview/27596113/TEC3312648%20A%20Computationally%20Efficient%20Semi-Analytical%20Method%20for%20Circulating%20Current%20Loss%20of%20High%20Speed%20Permanent%20Magnet%20Machines_Author%20Version.pdf)


# 🔨 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">High Temperature, High Power Density Intergated PMSM </div><img src='images/proj1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
## 100kW High Temperature Intergated PMSM System

- Operating Ambient Temperature up to 150 $$^\circ$$ C

- Total Power Density 4.5 kW/kg (Larger than the latest aerospace SP200D series from Siemens, which power density is 3.8 kW/kg)

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
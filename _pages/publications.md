---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
table, th, td {
  border: none;
  border-collapse: collapse;
}
</style>

{% include base_path %}

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my papers on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

<br>

📝 Select Publications
======
<font face="helvetica, ariel, &#39;sans serif&#39;">
        <table cellspacing="0" cellpadding="0" class="noBorder" style="text-align:center">
            <tbody>
              <tr>
                <td class="noBorder" width="40%">
                    <img width="400" src="{{ base_path }}/images/CLIP2FL.png" alt="CLIP2FL" style="border:0px">
                </td>
                <td>
                  <b>CLIP-Guided Federated Learning on Heterogeneous and Long-Tailed Data</b>
                  <br>
                  Jiangming Shi, ShanShan Zheng, Xiangbo Yin, Yang Lu, Yuan Xie†, Yanyun Qu†
                  <br>
                  <em> Proceedings of the AAAI Conference on Artificial Intelligence (AAAI 2024)</em>
                  <br>
                  [<a href="https://ojs.aaai.org/index.php/AAAI/article/view/29416">Paper</a>][<a href="https://github.com/shijiangming1/CLIP2FL">Code</a>]
                </td>
              </tr>
              <tr>
                <td class="noBorder" width="40%">
                    <img width="400" src="{{ base_path }}/images/DPIS.png" alt="CLIP2FL" style="border:0px">
                </td>
                <td>
                  <b>Dual Pseudo-Labels Interactive Self-Training for Semi-Supervised Visible-Infrared Person Re-Identification</b>
                  <br>
                  Jiangming Shi*, Yachao Zhang*, Xiangbo Yin, Yuan Xie†, Zhizhong Zhang, Jianping Fang, Zhongchao Shi, Yanyun Qu†
                  <br>
                  <em> IEEE Conference on International Conference on Computer Vision (ICCV 2023) </em>
                  <br>
                  [<a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Shi_Dual_Pseudo-Labels_Interactive_Self-Training_for_Semi-Supervised_Visible-Infrared_Person_Re-Identification_ICCV_2023_paper.pdf">Paper</a>][<a href="https://github.com/shijiangming1/DPIS">Code</a>]
                </td>
              </tr>            
            </tbody>
          </table>
</font>


<!-- {% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} --> 

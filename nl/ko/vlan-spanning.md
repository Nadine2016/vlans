---
copyright:
  years: 1994, 2017
lastupdated: "2017-12-27"
---
{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# VLAN 스패닝 사용 또는 사용 안함

때로는 여러 개의 사설 네트워크 VLAN이 단일 고객 계정에 존재할 수 있습니다. 그러나, 네트워크 디바이스는 동일한 VLAN에 존재하지 않으면 사설 네트워크에서 서로 통신할 수 없습니다. VLAN 스패닝은 계정의 모든 디바이스가 그의 지정된 VLAN과 상관없이 사설 네트워크를 통해 서로 통신할 수 있도록 합니다. 

VLAN 스패닝 서비스는 계정의 모든 디바이스에 적용됩니다. 특정 VLAN이나 특정 디바이스에 스패닝을 적용할 수는 없습니다. VLAN 스패닝은 필요에 따라 사용 또는 사용 안함으로 설정할 수 있으며, 설정에 대한 변경이 작성된 후에는 처리하는 데 약 15분이 걸립니다. 계정에 대해 VLAN 스패닝을 사용 또는 사용 안함으로 설정하려면 이 기사에서 주어지는 단계를 따르십시오.


1. 브라우저에서 [Customer Portal ![외부 링크 아이콘](../../icons/launch-glyph.svg "외부 링크 아이콘")](https://control.softlayer.com/){: new_window}을 열고 사용자 계정에 로그인하십시오.
2. Customer Portal 탐색에서 **네트워크 > IP 관리> VLAN**을 선택하십시오.
3. **스팬** 탭을 선택하여 VLAN 스패닝 섹션에 액세스하십시오.
4. VLAN 스패닝을 사용으로 설정하려면 **On** 단일 선택 단추를 선택하십시오. VLAN 스패닝을 사용 안함으로 설정하려면 **Off** 단일 선택 단추를 선택하십시오.

## 다음 발생 결과

VLAN 스패닝 선택을 업데이트한 후, 요청은 처리하는 데 최대 15분이 소요될 수 있습니다. 변경 확인이 스팬 탭 아래에 나타납니다. VLAN 스패닝을 사용으로 설정하는 경우 디바이스는 사설 네트워크를 사용하여 VLAN을 통해 서로 통신할 수 있습니다. 스패닝을 사용 안함으로 설정하는 경우, 디바이스는 동일한 VLAN에 상주하는 경우에만 서로 연결할 수 있습니다. VLAN을 통한 통신은 더 이상 사용 불가능합니다. VLAN 스패닝 설정은 이 기사에서 제공되는 단계를 반복하여 언제든지 업데이트할 수 있습니다. **참고:** 짧은 시간에 VLAN 스패닝 설정 사이에서 전환하면 설정 적용 지연이 발생할 수 있습니다.

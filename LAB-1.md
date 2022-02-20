#  你會如何介紹虛擬化技術?
發展歷史線
早在計算機還是龐然大物的上世紀60年代，虛擬化技術已經開始悄悄發展了。
1964年 IBM M44/44X被認為是世界上第一個支援虛擬化的系統，其技術方式是:像分時系統一樣，在每個時間片，一個IBM 7044大型機獨佔所有硬體資源來運行，並且提出了分頁的概念，由於其依賴硬體來實現虛擬化，史稱硬體虛擬化。
1974年，論文Formal requirements for virtualizable third generation architectures提出了虛擬化系統結構的三個基本條件[1]。
1972年著名的天才法國程式設計師Fabrice Bellard出生。
1979年的 Unix 第7版引入了 chroot 機制,chroot 就是讓一個程序把指定的目錄作為根目錄，它的所有檔案系統操作都只能在這個指定目錄里進行
1990年 Xen hypervisor 的Xenoserver初始程式碼工程由 Keir Fraser 和 Ian Pratt 建立。
1998年，很著名的X86 模擬器Bochs出現了，其正式版本的退出時間為1998年11月。
1999年，Vmware 公司率先推出針對X86平臺的商用虛擬機器Vmaware workstation。
2001年，目前最流行的採用動態二進位制翻譯技術的虛擬化軟體Qemu（Quick EMUlator）釋出第一個版本，其作者是Fabrice Bellard。
2003年，劍橋大學釋出了首個Public 的Xen 版本，通過半虛擬化技術實現了對包括x86-64 平臺多個平臺的虛擬化支援。
同年，Intel 公佈了將在x86平臺的cpu上支援虛擬化技術VT。
2007年1月，Sun 公司釋出了開源虛擬化VirtualBox。
2007年2月，Linux Kernel 主線版本2.6.20合入了由以色列公司Qumranet開發的KVM（Kernel-based Virtual Machine，支援KVM的前提是CPU必須要支援硬體虛擬化。
2008年第一季度，微軟連同Windows Server 2008同時釋出了虛擬化產品Hyper-V。
2008年6月，Linux Container 釋出了0.1.0版本，其可以提供輕量級的虛擬化，用來隔離程序和資源。
2008年9月4，Red Hat 收購了色列公司Qumranet，並著手開始用KVM替換在Red Hat中的使用的Xen**[Xen開始在主流Linux 發行廠商中衰落]**。
2010年10月21，NASA釋出了可以提供基礎設施即服(IaaS)服務的雲平臺OpenStack>，並提供了第一個版本。
2011年1月11，Ubuntu的創始人Mark shuttleworth宣佈，Ubuntu 將採用Openstack 作為基礎的雲平臺，在之前的版本Ubuntu 採用的是Eucalyptus。
2013年3月15，在加利福尼亞州聖克拉拉召開的 Python 開發者大會上，DotCloud 的創始人兼執行長 Solomon Hvkes 在一場僅五分鐘的微型演講中，首次提出了Docker這一概念，並於會後將原始碼進行了開源，託管在了github上。
2014年6月，Docker釋出了第一個正式版本1.0，彼時，Docker的下載量已經超過275萬次，1年之內Redhat 和 AWS就宣佈為Docker提供官方支援。
2015年國外國內湧現各種從事雲的公司，並提供了各種雲服務，諸如Laas,Paas,Saas等。
從上述時間線，我們的發現，各種如春筍般的新技術的出現，必將有舊技術的沒落，技術界的革新比我們想象的要快太多。
#你會如何介紹VMWare Player?
VMware Player （现已更名为VMware Workstation Player）是一款桌面虚拟化应用，无需重新启动即可在同一计算机上运行一个或多个操作系统。凭借其简单的用户界面、无可比拟的操作系统支持和移动性，用户可以比以往更轻松地使用公司桌面投入工作。

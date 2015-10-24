##Tại sao Red Hat thu mua Ansible.

Hôm nay, chúng tôi đã công bố một thỏa thuận cuối cùng để có được Ansible, một công cụ tự động hóa IT phổ biến được ra mắt vào đầu năm 2013. Giống như trong việc mua lại, khách hàng và đối tác sẽ có rất nhiều câu hỏi, vì vậy hãy để tôi đi thẳng vào vấn đề và tập trung vào ba câu hỏi tôi dự đoán:

-	Tại sao là một giải pháp tự động hóa IT?
-	Tại sao là Ansible?
-	Làm thế nào để Ansible phù hợp trong chiến lược quản lý của Red Hat?

**Tại sao là một giải pháp tự động hóa IT?**

Tự động hóa giúp các tổ chức IT giải quyết nhu cầu ngày càng tăng về tốc độ và sự  đơn giản xuất phát từ các ngành nghề kinh doanh (LOB) thông qua các bước khởi đầu quan trong, bao gồm:

-	**Hỗ trợ các ứng dụng điện toán đám mây riêng thông qua việc triển khai Iinfractructure-as-a-Service(IaaS) và Platform-as-a-Service(PaaS).**

  Thế hệ ứng dụng tiếp theo yêu cầu môi trường điện toán thế hệ mới, giống như quy mô IaaS và PaaS. Việc triển khai các môi    trường điện toán đám mây (ví dụ OpenStack) có thể là một thách thức do sự phức tạp vốn có của nó và sự trưởng thành tương    đối của công nghệ lớp dưới.

  Các công cụ tự động hóa IT có thể giúp tăng tốc độ đáng kể các triển khai điện toán đám mây trong khi làm giảm mạnh mẽ lỗi   của con người kết hợp với can thiệp thủ công.

-	**Phát triển ứng dụng Agile thông qua áp dụng DevOps**

  Các ứng dụng thế hệ tiếp theo được phát triển sau các phương pháp luận mới, và các mô hình mới, như kiến trúc dịch vụ vi     mô. Hỗ trợ chuyển phát liện tục được dự bảo bởi phương pháp DevOps yêu cầu một chuỗi các công cụ, trao quyền cho các nhà     phát triển để phát hành sớm và thường xuyên. Lần lượt các ứng dụng cập nhật thường xuyên phụ thuộc vào sự hiệu quả, đơn      giản và nhanh chóng các công cụ DevOps trong chuỗi công cụ.

  Các công cụ tự động hóa IT là một bổ sung quan trong cho bất kì chuỗi công cụ DevOps nào, như chúng có thể hoạt đông một số   lượng lớn các thay đổi các cấu trúc ứng dụng phức tạp, và một lượng lớn các phiên bản ứng dụng trong một lượng thời gian     ngắn.
  
-	**Sự điều phối dịch vụ trong qua quá trình tự động hóa IT.**

  Tham vọng cuối cùng của các tổ chức IT trên toàn thế giới là cung cấp cho một LOB dự phòng hoàn toàn tự động của toàn bộ     ngăn xếp ưng dụng của họ, thông qua máy ảo(VMs) hoặc bình chứa, hoặc “điều phối dịch vụ”. Đây là một tham vọng xưa cũ như    các đám mây cá nhân, và chưa có một ngành công nghiệp nào đấu tranh để làm nó trở thành hiện thực. Vấn đề là điều phối và    tự động hóa là hai quá trình rất nhiều thách thức, và thiếu các giao diện chuẩn để kết hợp chúng theo quy trình.

  Red Hat CloudForms, nền tảng quản lý điện toán của chúng tôi đứng đầu trong hạng điều phối toàn bộ vòng đời của một ứng      dụng doanh nghiệp ( từ tính dự phòng cho đến kết thúc), theo như các chính sách cấu hình và tuân thủ.

  Khách hàng của chúng tôi đã sử dụng các giải pháp Red Hat kết hợp với rất nhiều các công cụ tự động hóa IT. Với sự thu nhận   này, chúng tôi muốn đưa ra một loại hình hội nhập thông qua các loại hỗ trợ Red Hat trên toàn thế giới và giấy chứng nhận    làm cho mã nguồn mở có thể tiêu thụ được cho doanh nghiệp ( chính xác theo cùng một cách chúng ta làm cho OpenStack và các   sản phẩm khác trong hạng mục đầu tư khác của chúng tôi).

**Tại sao là Ansible?**

Chúng tôi nhìn thấy trong Ansible một liên kết hoàn hảo với các nguyên tác cốt lõi để định hình quản lý của Red Hat, cả ở cấp độ sản phẩm và cấp độ danh mục đầu tư.

Ở cấp độ sản phẩm, Ansible phù hợp với mong muốn của Red Hat là cung cấp một thiết kế không ma sát và một kiến trúc mô đun thông qua sự phát triển mở.

-	**Ansible dễ sử dụng.**

  Tìm kiếm Google nhanh sẽ tiết lộ một quan điểm nhất quán áp đảo về đường cong học tập thấp của Ansible và quản lý khá đơn    giản của nó. Như khi chúng tôi cung cấp một IT không má sát, khách hàng của chúng tôi cần để giải quyết các thế hệ hiện tại   và tương lai, tập trung vào “sự đơn giản” là rất quan trọng. Sự đơn giản như thế nào? Hãy để tôi đưa ra hai ví dụ.

  Ví dụ thứ nhất: “playbooks” của Ansible được viết bẳng chữ số YAML con người có thể đọc được, nó dễ dàng hơn để viết và duy   trì quy trình tự động hóa.
  
  Ví dụ thứ hai: Ansible là một đại lý, sử dụng tiêu chuẩn kết nối SSH để thực hiện quy trình tự động hóa, làm nó dễ dàng hơn   để hoàn nhập vào môi trường doanh nghiệp IT hiện có và cơ chế hoạt động phức tạp của nó.

- **Ansible là mô đun.**

  Tại thời điểm viết bài, Ansible gồm trên 400 mô đun, có thể được gọi theo ý muốn để mở rộng tính năng của sản phẩm vượt ra   những tính năng cốt lõi và ý định của nó. Đây là một tính năng quan trọng của sản phầm mà chúng tôi muốn đưa ra trong tất    cả các sản phẩm quản lý Red Hat để hỗ trợ khác hàng của chúng tôi nhu cầu phát triển của họ về sự trưởng thàng, phức tạp và   quy mô IT của họ.

  Mô đun như thế nào? Hãy để tôi đưa ra một ví dụ.
  
  Tính năng mô đun của Ansible trải rộng từ quản lý lưu trữ hình ảnh in dịch vụ hình ảnh OpenStack(Glance) để quản lý bình     chứa Linux để thu thập dữ liệu từ kiểm soát phân phối ứng dụng F5 Big-IP.

- **Ansible là một dự án mã nguồn mở rất phổ biến.**
 
  Ansible là một dự án mã nguồn mở vô cùng phổ biến và cộng đồng các thành viên góp phần vào cả công nghệ cốt lõi và các mô    đun   đi kèm với nhân. Chúng tôi tin tưởng rằng hỗ trợ và nuôi dưỡng cộng đồng mã nguồn mở tuyệt vời là một cách duy nhất    để đảm bảo một luồng cải tiến, và đó là cái làm cho Red Hat đặc biệt.

  Phổ biến như thế nào?  Hãy để tôi chia sẽ một số ví dụ.
  
  Thứ nhất, Ansible có hơn 13.000 sao và gần 4000 nhánh trên GitHub.
  
  Thứ hai, theo như RedMonk, lượng đề cập đến Ansible trong cộng đồng Hacker News đang tăng vọt.

Ở cấp độ danh mục đầu tư, Ansible phù hợp với mong muốn của Red Hat để hỗ trợ kiến trúc đa tầng, cung cấp sự nhất quán nhiều tần, và cung cấp hỗ trợ nhiều nhà cung cấp:

-	**Ansible cung cấp triển khai nhiều tầng.**

  Ansible được thiết kế để hỗ trợ việc triển khai và cấu hình của một ứng dụng đa tầng, thông qua VMs và bình chứa. Điều này   có nghĩa là các tổ chức có thể tự động cung cấp các thành phần khác nhau của cùng một ứng dụng trên lớp hiệu quả nhất để     chạy chúng: quy mô khối lượng công việc trên kim loại trần và công cụ máy chủ ảo, khối lương công việc trên điện toán đám    mây IaaS và PaaS. Chúng tôi không tin tưởng phương pháp tiếp cận một kích thước phù hợp với tất cả” và chúng tôi ccan kết    hỗ trợ phạm vi rộng nhất của cơ sở hạ tầng và nền tảng có thể.

  Sự hỗ trợ nhiều bậc của Ansible đi đến đâu? Dưới đây là một ví dụ.
  
  Ansible có thể quản lý Vms và nhiều hệ điều hành khách trong môi trường máy chủ ảo VMware vSphere, triển khai và quản lý     máy ảo trong đám mây OpenStack IaaS, và triển khai ứng dụng bên trong đám mây OpenShift PaaS, tất cả điều này trong cùng     một lúc.

- **Ansible mang lại sự nhất quán ở nhiều lớp kiến trúc.**

  Ansible có thể được sử dụng để thao tác lập trình mọi lớp của kiến trúc điện toán, từ cơ sở hạ tầng đến ứng, và cho mọi      trường hợp, từ điều phối đến triển khai đến đến cấu hình. Như tôi đã nói ở phần đầu bài viết này, Red Hat tạo điều kiện cho   việc cung cấp toàn bộ ngăn xếp ứng dụng theo cách đơn giản nhất có thể, và tính quản lý nhất quán là một cách tuyệt với để   giữ cho mọi thứ dễ dàng.

  Sự hỗ trợ nhiều lớp của Ansible đi đến đâu? Dưới đây là một ví dụ.
  
  Ansible có thể tự động hóa mọi thứ bao gồm cả cấu hình mạng, lưu trữ, tính toán (ví dụ máy ảo OpenStack), OS, hệ trung gian   (ví dụ miền trung gian Red Hat JBoss) và cuối cùng là tầng ứng dụng.
  
- **Ansible hỗ trợ trường IT không đồng nhất.**

  Ansible có thể tự động cấu hình một loạt các công nghệ từ nhiều nhà cung cấp, không chỉ là Red Hat. Các khách hàng doanh     nghiệp của chúng tôi có những môi trường IT phức tạp không đồng nhất và điều cuối cùng tôi muốn dành cho khách hàng là tạo   ra các hầm chứa quản lý dự phòng, hoặc nắm lấy các nhà cung cấp đơn nếu nó không phải là điều tốt nhấy cho doanh nghiệp. 
  Sự hỗ trợ nhiều nhà cung cấp của Ansible đi đến đâu? Tôi có hai ví dụ cuối cùng cho các bạn.
  
  Thứ nhất: Ansible hỗ trợ cả hai môi trường Linux và Windows, thức hiện tốt như nhau cấu hình một máy chủ web Apache2 hoặc    một kho ứng dụng web Microsoft IIS.
  
  Thứ hai: thông qua các mô đun của nó, Ansible trao quyền cho các tổ chức IT để quản lý một loạt các công nghệ ISV và IHV,    từ bộ điều khiển mạng F5 Big-IP và Citrix etScaler đến Dịch vụ Web Amazon và đám mây Google.
  
**Ansible phù hợp với chiến lược quản lý của Red Hat như thế nào?**

Nếu bạn đã đọc đến đây, bạn đã có một ý tưởng khá tốt về các Ansible sẽ tăng cường và bổ sung cho doanh mục quản lý đầu tư   hiện tại của Red Hat.

- **Red Hat CloudForms** sẽ tiếp tục cung cấp sự điều phối chung và thực thi chính sách ở tất cả các tầng kiến trúc chúng tôi hỗ trợ, trong danh giới của công ty và trên đám mây công cộng.

- **Ansible** sẽ tự động trích lập và cấu hình các nguồn cở sở hạ tầng và các ứng dụng trong mỗi tầng kiến trúc, như yêu cầu thông qua các cổng thông tin dự liệu tự phục vụ CloudForms. Điều này sẽ bao gồm việc triển khai các đại lý truyền hình vệ tinh Red Hat trên máy kim loại trần khi các trường hợp yêu cầu nó.

- **Truyền hình vệ tinh Red Hat** sẽ tiếp tục cho phép trích lập và cấu hình hệ thống Red Hat (và các bản vá lỗi bảo mật và cập nhật phần mềm) trong mỗi tầng kiến trúc, như được định nghĩa bởi các quy trình tự động hóa Ansible. 

Khách hàng Red Hat sẽ có thể áp dụng làm theo bất kỳ trong ba như một sản phẩm độc lập, nhưng chúng tôi sẽ khó làm việc để thắt chặt sự tích hợp giữa ba để giúp họ làm việc tuyệt vời với nhau.

Chúng tôi tất vui mừng có một đội ngủ Ansible gia nhập vào gia đình Red Hat và chúng tôi không thể chờ đợi để đưa sản phẩm tới tay khách hàng của chúng tôi.


Nguồn: http://www.redhat.com/en/about/blog/why-red-hat-acquired-ansible

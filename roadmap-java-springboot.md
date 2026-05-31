# 📘 Roadmap Java + Spring Boot 2026

> **Lộ trình toàn diện** từ Fresher → Senior dành cho Java Developer & Spring Boot Engineer.
> Bao gồm: Định nghĩa, Ví dụ code chạy được, Link tài liệu chính thức, Câu hỏi phỏng vấn theo cấp độ.

---

## 📑 Mục lục

- [Phần 1 — Tổng quan Roadmap](#phần-1--tổng-quan-roadmap)
  - [1.1 Java Core Roadmap](#11-java-core-roadmap)
  - [1.2 Spring Boot Roadmap](#12-spring-boot-roadmap)
- [Phần 2 — Thẻ Khái niệm Java Core](#phần-2--thẻ-khái-niệm-java-core)
  - [Nhóm 1: Cú pháp & Kiểu dữ liệu cơ bản](#nhóm-1-cú-pháp--kiểu-dữ-liệu-cơ-bản)
  - [Nhóm 2: Lập trình hướng đối tượng (OOP)](#nhóm-2-lập-trình-hướng-đối-tượng-oop)
  - [Nhóm 3: Collections Framework](#nhóm-3-collections-framework)
  - [Nhóm 4: Exception Handling](#nhóm-4-exception-handling)
  - [Nhóm 5: Generics](#nhóm-5-generics)
  - [Nhóm 6: Functional Programming & Stream API](#nhóm-6-functional-programming--stream-api)
  - [Nhóm 7: Concurrency & Multithreading](#nhóm-7-concurrency--multithreading)
  - [Nhóm 8: I/O & NIO](#nhóm-8-io--nio)
  - [Nhóm 9: JVM Internals & Memory Management](#nhóm-9-jvm-internals--memory-management)
  - [Nhóm 10: Modern Java Features (Java 17–21+)](#nhóm-10-modern-java-features-java-1721)
  - [Nhóm 11: Design Patterns](#nhóm-11-design-patterns)
  - [Nhóm 12: Testing](#nhóm-12-testing)
- [Phần 3 — Thẻ Khái niệm Spring Boot](#phần-3--thẻ-khái-niệm-spring-boot)
  - [Nhóm A: Spring Core & IoC](#nhóm-a-spring-core--ioc)
  - [Nhóm B: Spring Boot Basics](#nhóm-b-spring-boot-basics)
  - [Nhóm C: REST API Development](#nhóm-c-rest-api-development)
  - [Nhóm D: Data Access (JPA/Hibernate)](#nhóm-d-data-access-jpahibernate)
  - [Nhóm E: Spring Security](#nhóm-e-spring-security)
  - [Nhóm F: Microservices Architecture](#nhóm-f-microservices-architecture)
  - [Nhóm G: Messaging & Event-Driven](#nhóm-g-messaging--event-driven)
  - [Nhóm H: Testing trong Spring Boot](#nhóm-h-testing-trong-spring-boot)
  - [Nhóm I: DevOps & Deployment](#nhóm-i-devops--deployment)
- [Phần 4 — Bảng tổng hợp Phỏng vấn](#phần-4--bảng-tổng-hợp-phỏng-vấn)
- [Tài nguyên tham khảo](#tài-nguyên-tham-khảo)

---

## Phần 1 — Tổng quan Roadmap

### 1.1 Java Core Roadmap

```
📘 Java Core Roadmap
├── 🟢 Cơ bản (Fresher)
│   ├── Variables & Data Types (Primitive, Reference)
│   ├── Operators & Expressions
│   ├── Control Flow (if/else, switch, loops)
│   ├── Arrays & Strings
│   ├── Methods (khai báo, overloading)
│   ├── OOP cơ bản: Class, Object, Encapsulation
│   ├── Inheritance & Polymorphism
│   ├── Abstract Class & Interface
│   ├── Exception Handling (try-catch-finally)
│   ├── Collections cơ bản (List, Set, Map)
│   └── Basic I/O (Scanner, File)
│
├── 🔵 Trung cấp (Junior)
│   ├── Generics
│   ├── Enum & Annotations
│   ├── Lambda Expressions
│   ├── Stream API
│   ├── Optional
│   ├── Collections nâng cao (Queue, Deque, TreeMap)
│   ├── Comparable & Comparator
│   ├── Exception Handling nâng cao (Custom Exceptions)
│   ├── File I/O & NIO
│   ├── Date/Time API (java.time)
│   └── Unit Testing với JUnit 5
│
├── 🟡 Nâng cao (Mid-level)
│   ├── Multithreading & Concurrency
│   ├── ExecutorService & Thread Pool
│   ├── Synchronized, Locks, Atomic
│   ├── CompletableFuture
│   ├── Design Patterns (Singleton, Factory, Builder, Observer, Strategy)
│   ├── Reflection API
│   ├── JVM Architecture (ClassLoader, JIT, GC)
│   ├── Memory Management (Heap, Stack, Metaspace)
│   ├── JDBC & Database Connectivity
│   └── Build Tools (Maven/Gradle)
│
└── 🔴 Chuyên sâu (Senior)
    ├── JVM Tuning & GC Algorithms (G1, ZGC, Shenandoah)
    ├── Class Loading Mechanism
    ├── Bytecode Analysis & Instrumentation
    ├── Virtual Threads (Project Loom)
    ├── Pattern Matching & Sealed Classes
    ├── Records & Text Blocks
    ├── Performance Profiling (JFR, JMC, VisualVM)
    ├── Custom Annotations & Annotation Processing
    ├── Module System (JPMS)
    └── Advanced Design Patterns & Architecture
```

### 1.2 Spring Boot Roadmap

```
🍃 Spring Boot Roadmap
├── 🟢 Cơ bản (Fresher)
│   ├── Spring Core: IoC & Dependency Injection
│   ├── Bean Lifecycle & Scopes
│   ├── Spring Boot Auto-Configuration
│   ├── Application Properties / YAML
│   ├── REST Controller (@RestController, @GetMapping...)
│   ├── Request/Response Handling
│   ├── Spring Data JPA cơ bản (CRUD Repository)
│   └── H2 / MySQL Integration
│
├── 🔵 Trung cấp (Junior)
│   ├── Validation (@Valid, custom validators)
│   ├── Exception Handling (@ControllerAdvice)
│   ├── DTO Pattern & ModelMapper/MapStruct
│   ├── Pagination & Sorting
│   ├── Spring Data JPA nâng cao (Query Methods, @Query, Specifications)
│   ├── Transactions (@Transactional)
│   ├── Logging (SLF4J, Logback)
│   ├── Spring Profiles
│   ├── Actuator (Health, Metrics)
│   └── API Documentation (Swagger/OpenAPI)
│
├── 🟡 Nâng cao (Mid-level)
│   ├── Spring Security (Authentication & Authorization)
│   ├── JWT Authentication
│   ├── OAuth2 / OpenID Connect
│   ├── Caching (Spring Cache, Redis)
│   ├── Async Processing (@Async, @Scheduled)
│   ├── WebSocket
│   ├── AOP (Aspect-Oriented Programming)
│   ├── Spring Events
│   ├── Integration Testing (@SpringBootTest)
│   └── Docker Containerization
│
└── 🔴 Chuyên sâu (Senior)
    ├── Microservices Patterns (API Gateway, Service Discovery, Circuit Breaker)
    ├── Spring Cloud (Eureka, Config Server, Gateway)
    ├── Event-Driven Architecture (Kafka, RabbitMQ)
    ├── CQRS & Event Sourcing
    ├── Reactive Programming (WebFlux, R2DBC)
    ├── gRPC Communication
    ├── Distributed Tracing (Micrometer, Zipkin)
    ├── Kubernetes Deployment
    ├── CI/CD Pipeline (Jenkins, GitHub Actions)
    └── Performance Tuning & Production Monitoring
```

---

## Phần 2 — Thẻ Khái niệm Java Core

### Nhóm 1: Cú pháp & Kiểu dữ liệu cơ bản

<details>
<summary>🟢 Variables & Data Types</summary>

#### 📝 Định nghĩa
Java là ngôn ngữ **strongly-typed** — mọi biến đều phải khai báo kiểu trước khi sử dụng. Java có 8 kiểu nguyên thuỷ (primitive types): `byte`, `short`, `int`, `long`, `float`, `double`, `char`, `boolean`. Ngoài ra có các kiểu tham chiếu (reference types) như `String`, `Array`, và các Object.

#### 💻 Ví dụ Code

```java
public class DataTypesDemo {
    public static void main(String[] args) {
        // Kiểu nguyên thuỷ (Primitive Types)
        byte tuoi = 25;             // 1 byte, phạm vi: -128 đến 127
        short soNho = 30000;        // 2 bytes
        int soNguyen = 1_000_000;   // 4 bytes, dùng _ để dễ đọc
        long soDai = 9_999_999_999L;// 8 bytes, thêm L ở cuối
        float soThuc = 3.14f;       // 4 bytes, thêm f ở cuối
        double soThucLon = 3.14159; // 8 bytes, mặc định cho số thực
        char kyTu = 'A';           // 2 bytes, Unicode
        boolean coHoc = true;      // true hoặc false

        // Kiểu tham chiếu (Reference Types)
        String hoTen = "Nguyễn Văn A";  // Chuỗi ký tự
        int[] mangSo = {1, 2, 3, 4, 5}; // Mảng

        // var — type inference (Java 10+)
        var diemTrungBinh = 8.5; // Compiler tự suy luận kiểu double

        System.out.println("Họ tên: " + hoTen);
        System.out.println("Tuổi: " + tuoi);
        System.out.println("Điểm TB: " + diemTrungBinh);
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Oracle Java Tutorial — Primitive Data Types](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html)
- [JDK 21 API — java.lang Package](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/package-summary.html)

**Ứng dụng thực tế:** Trong mọi dự án Java, hiểu rõ khi nào dùng `int` vs `long`, `float` vs `double` ảnh hưởng trực tiếp đến performance và tính chính xác (ví dụ: tính toán tài chính phải dùng `BigDecimal`, không dùng `float`/`double`).

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟢 Fresher | Sự khác nhau giữa primitive type và reference type? |
| 🟢 Fresher | `int` và `Integer` khác nhau như thế nào? (Autoboxing/Unboxing) |
| 🔵 Junior | Tại sao không nên dùng `float`/`double` cho tính toán tiền tệ? |
| 🔵 Junior | `var` hoạt động thế nào? Có phải Java trở thành dynamically-typed? |

</details>

<details>
<summary>🟢 Operators & Control Flow</summary>

#### 📝 Định nghĩa
Java hỗ trợ các toán tử: Arithmetic (`+`, `-`, `*`, `/`, `%`), Comparison (`==`, `!=`, `<`, `>`), Logical (`&&`, `||`, `!`), Bitwise (`&`, `|`, `^`), Assignment (`=`, `+=`, `-=`), và Ternary (`? :`). Control Flow bao gồm `if/else`, `switch` (enhanced switch từ Java 14+), `for`, `while`, `do-while`, `for-each`.

#### 💻 Ví dụ Code

```java
public class ControlFlowDemo {
    public static void main(String[] args) {
        int diem = 85;

        // if-else truyền thống
        if (diem >= 90) {
            System.out.println("Xuất sắc");
        } else if (diem >= 70) {
            System.out.println("Khá");
        } else {
            System.out.println("Trung bình");
        }

        // Enhanced switch (Java 14+) — không cần break
        String xepLoai = switch (diem / 10) {
            case 10, 9 -> "Xuất sắc";
            case 8     -> "Giỏi";
            case 7     -> "Khá";
            default    -> "Trung bình";
        };
        System.out.println("Xếp loại: " + xepLoai);

        // For-each loop
        int[] danhSachDiem = {7, 8, 9, 6, 10};
        int tongDiem = 0;
        for (int d : danhSachDiem) {
            tongDiem += d;
        }
        System.out.println("Tổng điểm: " + tongDiem);

        // Ternary operator
        String ketQua = (diem >= 50) ? "Đậu" : "Rớt";
        System.out.println("Kết quả: " + ketQua);
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Oracle Tutorial — Control Flow Statements](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/flow.html)
- [JEP 361 — Switch Expressions](https://openjdk.org/jeps/361)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟢 Fresher | Sự khác nhau giữa `==` và `equals()` khi so sánh String? |
| 🟢 Fresher | Enhanced switch khác gì so với switch truyền thống? |
| 🔵 Junior | Short-circuit evaluation trong `&&` và `||` hoạt động thế nào? |

</details>

<details>
<summary>🟢 Arrays & Strings</summary>

#### 📝 Định nghĩa
**Array** là cấu trúc dữ liệu có kích thước cố định, chứa các phần tử cùng kiểu. **String** trong Java là immutable (bất biến) — mỗi lần thay đổi tạo ra object mới. `StringBuilder` và `StringBuffer` dùng cho chuỗi thay đổi nhiều lần.

#### 💻 Ví dụ Code

```java
import java.util.Arrays;

public class ArrayStringDemo {
    public static void main(String[] args) {
        // Mảng 1 chiều
        String[] monHoc = {"Toán", "Lý", "Hóa", "Anh"};
        System.out.println("Số môn: " + monHoc.length);

        // Sắp xếp mảng
        int[] diem = {8, 5, 9, 3, 7};
        Arrays.sort(diem);
        System.out.println("Đã sắp xếp: " + Arrays.toString(diem));

        // Mảng 2 chiều
        int[][] bangDiem = {
            {8, 7, 9},
            {6, 8, 7}
        };

        // String là immutable
        String ten = "Java";
        String ten2 = "Java";
        System.out.println(ten == ten2);        // true — cùng String Pool
        System.out.println(ten.equals(ten2));   // true — so sánh giá trị

        // StringBuilder cho chuỗi thay đổi nhiều — hiệu suất tốt hơn
        StringBuilder sb = new StringBuilder();
        for (String mon : monHoc) {
            sb.append(mon).append(", ");
        }
        System.out.println("Các môn: " + sb.toString());

        // Các phương thức String hữu ích
        String chuoi = "  Hello Java World  ";
        System.out.println(chuoi.trim());                  // "Hello Java World"
        System.out.println(chuoi.trim().split(" ").length); // 3
        System.out.println("Java".repeat(3));               // "JavaJavaJava" (Java 11+)
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Oracle Tutorial — Arrays](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/arrays.html)
- [JDK 21 API — java.lang.String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟢 Fresher | Tại sao String là immutable? Lợi ích gì? |
| 🟢 Fresher | String Pool hoạt động như thế nào? |
| 🔵 Junior | `StringBuilder` vs `StringBuffer` — khi nào dùng cái nào? |
| 🔵 Junior | Tại sao nối chuỗi bằng `+` trong vòng lặp là anti-pattern? |

</details>

### Nhóm 2: Lập trình hướng đối tượng (OOP)

<details>
<summary>🟢 Class, Object & Encapsulation</summary>

#### 📝 Định nghĩa
**Class** là bản thiết kế, **Object** là thể hiện cụ thể. **Encapsulation** (đóng gói) là việc ẩn dữ liệu nội bộ bằng `private` và cung cấp truy cập qua getter/setter. Đây là nguyên tắc nền tảng giúp bảo vệ dữ liệu và kiểm soát logic nghiệp vụ.

#### 💻 Ví dụ Code

```java
public class SinhVien {
    // Đóng gói: các field là private
    private String maSV;
    private String hoTen;
    private double diemTB;

    // Constructor
    public SinhVien(String maSV, String hoTen, double diemTB) {
        this.maSV = maSV;
        this.hoTen = hoTen;
        setDiemTB(diemTB); // Dùng setter để validate
    }

    // Getter
    public String getHoTen() {
        return hoTen;
    }

    // Setter có validation — kiểm soát dữ liệu đầu vào
    public void setDiemTB(double diemTB) {
        if (diemTB < 0 || diemTB > 10) {
            throw new IllegalArgumentException("Điểm phải từ 0 đến 10");
        }
        this.diemTB = diemTB;
    }

    public String xepLoai() {
        if (diemTB >= 8) return "Giỏi";
        if (diemTB >= 6.5) return "Khá";
        if (diemTB >= 5) return "Trung bình";
        return "Yếu";
    }

    @Override
    public String toString() {
        return String.format("%s - %s - %.1f (%s)", maSV, hoTen, diemTB, xepLoai());
    }

    public static void main(String[] args) {
        SinhVien sv = new SinhVien("SV001", "Nguyễn Văn A", 8.5);
        System.out.println(sv); // SV001 - Nguyễn Văn A - 8.5 (Giỏi)
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Oracle Tutorial — Classes and Objects](https://docs.oracle.com/javase/tutorial/java/javaOO/index.html)
- Trong Spring Boot, mọi Entity class (`@Entity`) đều dùng encapsulation với `private` fields.

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟢 Fresher | Giải thích 4 tính chất của OOP? |
| 🟢 Fresher | Constructor là gì? Khác gì so với method? |
| 🔵 Junior | `this` keyword dùng trong những trường hợp nào? |

</details>

<details>
<summary>🟢 Inheritance & Polymorphism</summary>

#### 📝 Định nghĩa
**Inheritance** (kế thừa) cho phép class con tái sử dụng code từ class cha bằng `extends`. **Polymorphism** (đa hình) cho phép một phương thức có nhiều hành vi khác nhau — bao gồm **compile-time** (overloading) và **runtime** (overriding) polymorphism.

#### 💻 Ví dụ Code

```java
// Lớp cha
abstract class HinhHoc {
    protected String ten;

    public HinhHoc(String ten) {
        this.ten = ten;
    }

    // Method abstract — bắt buộc lớp con phải override
    public abstract double tinhDienTich();

    // Method chung — lớp con kế thừa
    public void hienThi() {
        System.out.printf("%s: diện tích = %.2f%n", ten, tinhDienTich());
    }
}

// Lớp con 1
class HinhTron extends HinhHoc {
    private double banKinh;

    public HinhTron(double banKinh) {
        super("Hình tròn"); // Gọi constructor lớp cha
        this.banKinh = banKinh;
    }

    @Override
    public double tinhDienTich() {
        return Math.PI * banKinh * banKinh;
    }
}

// Lớp con 2
class HinhChuNhat extends HinhHoc {
    private double dai, rong;

    public HinhChuNhat(double dai, double rong) {
        super("Hình chữ nhật");
        this.dai = dai;
        this.rong = rong;
    }

    @Override
    public double tinhDienTich() {
        return dai * rong;
    }

    // Overloading — cùng tên, khác tham số
    public double tinhDienTich(double heSo) {
        return dai * rong * heSo;
    }
}

public class PolymorphismDemo {
    public static void main(String[] args) {
        // Runtime polymorphism — biến kiểu cha, object kiểu con
        HinhHoc[] danhSach = {
            new HinhTron(5),
            new HinhChuNhat(4, 6)
        };

        for (HinhHoc h : danhSach) {
            h.hienThi(); // Gọi đúng phương thức của từng lớp con
        }
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Oracle Tutorial — Inheritance](https://docs.oracle.com/javase/tutorial/java/IandI/subclasses.html)
- [Oracle Tutorial — Polymorphism](https://docs.oracle.com/javase/tutorial/java/IandI/polymorphism.html)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟢 Fresher | Overloading vs Overriding khác nhau thế nào? |
| 🟢 Fresher | Tại sao Java không hỗ trợ đa kế thừa (multiple inheritance) cho class? |
| 🔵 Junior | Giải thích method dispatch tại runtime hoạt động ra sao? |
| 🟡 Mid | SOLID principles liên quan đến OOP như thế nào? |

</details>

<details>
<summary>🟢 Abstract Class & Interface</summary>

#### 📝 Định nghĩa
**Abstract class** là class không thể khởi tạo, chứa cả abstract và concrete methods. **Interface** định nghĩa contract (hợp đồng) mà class phải tuân theo — từ Java 8+ hỗ trợ `default` và `static` methods, Java 9+ hỗ trợ `private` methods.

#### 💻 Ví dụ Code

```java
// Interface — định nghĩa contract
interface ThanhToan {
    // Abstract method — bắt buộc implement
    boolean thucHienThanhToan(double soTien);

    // Default method (Java 8+) — có sẵn logic, class con có thể override
    default String layTenPhuongThuc() {
        return this.getClass().getSimpleName();
    }

    // Static method — gọi trực tiếp qua Interface
    static void inBienLai(String phuongThuc, double soTien) {
        System.out.printf("Thanh toán %,.0f VNĐ bằng %s%n", soTien, phuongThuc);
    }
}

// Interface có thể kế thừa interface khác
interface ThanhToanOnline extends ThanhToan {
    String layMaGiaoDich();
}

// Class implement nhiều interface
class MoMo implements ThanhToanOnline {
    @Override
    public boolean thucHienThanhToan(double soTien) {
        System.out.println("Xử lý thanh toán MoMo...");
        return soTien <= 50_000_000; // Giới hạn 50 triệu
    }

    @Override
    public String layMaGiaoDich() {
        return "MOMO-" + System.currentTimeMillis();
    }
}

class TienMat implements ThanhToan {
    @Override
    public boolean thucHienThanhToan(double soTien) {
        System.out.println("Nhận tiền mặt...");
        return true;
    }
}

public class InterfaceDemo {
    public static void main(String[] args) {
        // Đa hình qua interface
        ThanhToan[] cacPhuongThuc = {new MoMo(), new TienMat()};

        for (ThanhToan tt : cacPhuongThuc) {
            tt.thucHienThanhToan(100_000);
            System.out.println("Phương thức: " + tt.layTenPhuongThuc());
        }

        // Gọi static method
        ThanhToan.inBienLai("MoMo", 500_000);
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Oracle Tutorial — Interfaces](https://docs.oracle.com/javase/tutorial/java/IandI/createinterface.html)
- Trong Spring: `@Service`, `@Repository` thường implement interface để dễ test (mock) và tuân theo Dependency Inversion.

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟢 Fresher | Khi nào dùng abstract class, khi nào dùng interface? |
| 🔵 Junior | Default method trong interface giải quyết vấn đề gì? |
| 🟡 Mid | Functional Interface là gì? Tại sao `@FunctionalInterface` quan trọng? |
| 🔴 Senior | Diamond problem trong Java xử lý thế nào khi class implement 2 interface có cùng default method? |

</details>

### Nhóm 3: Collections Framework

<details>
<summary>🟢🔵 Collections Framework</summary>

#### 📝 Định nghĩa
**Java Collections Framework** là tập hợp các interface và class để lưu trữ, thao tác nhóm đối tượng. Bao gồm: `List` (có thứ tự, cho phép trùng), `Set` (không trùng), `Map` (key-value), `Queue`/`Deque` (FIFO/LIFO). Chọn đúng Collection ảnh hưởng lớn đến performance.

#### 💻 Ví dụ Code

```java
import java.util.*;

public class CollectionsDemo {
    public static void main(String[] args) {
        // === LIST — có thứ tự, cho phép trùng ===
        // ArrayList: truy cập nhanh O(1), thêm/xoá giữa chậm O(n)
        List<String> sinhVien = new ArrayList<>(List.of("An", "Bình", "Cường", "An"));
        sinhVien.add("Dũng");
        System.out.println("List: " + sinhVien); // [An, Bình, Cường, An, Dũng]

        // LinkedList: thêm/xoá đầu cuối nhanh O(1), truy cập chậm O(n)
        LinkedList<String> hangDoi = new LinkedList<>();
        hangDoi.addFirst("Khách 1");
        hangDoi.addLast("Khách 2");

        // === SET — không trùng ===
        // HashSet: O(1) cho add/remove/contains, không đảm bảo thứ tự
        Set<String> monHocDaDangKy = new HashSet<>(List.of("Toán", "Lý", "Toán"));
        System.out.println("Set: " + monHocDaDangKy); // [Toán, Lý] — loại trùng

        // TreeSet: tự sắp xếp, O(log n)
        Set<Integer> diemSapXep = new TreeSet<>(List.of(8, 3, 9, 1, 5));
        System.out.println("TreeSet: " + diemSapXep); // [1, 3, 5, 8, 9]

        // === MAP — key-value ===
        // HashMap: O(1) cho get/put, không đảm bảo thứ tự
        Map<String, Integer> bangDiem = new HashMap<>();
        bangDiem.put("Toán", 9);
        bangDiem.put("Lý", 8);
        bangDiem.put("Hóa", 7);

        // Duyệt Map
        bangDiem.forEach((mon, diem) ->
            System.out.printf("  %s: %d%n", mon, diem)
        );

        // getOrDefault — tránh NullPointerException
        int diemAnh = bangDiem.getOrDefault("Anh", 0);
        System.out.println("Điểm Anh: " + diemAnh); // 0

        // computeIfAbsent — chỉ tính nếu key chưa có
        bangDiem.computeIfAbsent("Anh", k -> 6);

        // === Unmodifiable Collections (Java 9+) ===
        List<String> danhSachCodinh = List.of("A", "B", "C"); // Immutable
        Map<String, Integer> mapCoDinh = Map.of("x", 1, "y", 2);
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Oracle Tutorial — Collections](https://docs.oracle.com/javase/tutorial/collections/index.html)
- [JDK 21 API — java.util Package](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/package-summary.html)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟢 Fresher | ArrayList vs LinkedList: khi nào dùng cái nào? |
| 🟢 Fresher | HashSet làm sao biết phần tử đã tồn tại? (`hashCode` + `equals`) |
| 🔵 Junior | HashMap hoạt động nội bộ như thế nào? (bucket, hash collision) |
| 🔵 Junior | `ConcurrentHashMap` khác `HashMap` ra sao? Khi nào dùng? |
| 🟡 Mid | Giải thích `hashCode()` contract và ảnh hưởng đến performance của HashMap |
| 🔴 Senior | Tại sao HashMap chuyển từ linked list sang red-black tree khi bucket > 8 phần tử? |

</details>

### Nhóm 4: Exception Handling

<details>
<summary>🟢🔵 Exception Handling</summary>

#### 📝 Định nghĩa
Java chia exception thành: **Checked** (bắt buộc xử lý, ví dụ `IOException`), **Unchecked/Runtime** (không bắt buộc, ví dụ `NullPointerException`), và **Error** (lỗi hệ thống, ví dụ `OutOfMemoryError`). Cơ chế `try-catch-finally` và `try-with-resources` (Java 7+) giúp xử lý lỗi an toàn.

#### 💻 Ví dụ Code

```java
import java.io.*;

// Custom Exception — tạo exception riêng cho business logic
class SoDuKhongDuException extends RuntimeException {
    private final double soDuHienTai;
    private final double soTienRut;

    public SoDuKhongDuException(double soDuHienTai, double soTienRut) {
        super(String.format("Số dư %.0f không đủ để rút %.0f", soDuHienTai, soTienRut));
        this.soDuHienTai = soDuHienTai;
        this.soTienRut = soTienRut;
    }

    public double getSoDuHienTai() { return soDuHienTai; }
}

public class ExceptionDemo {
    // Method throws checked exception
    public static String docFile(String duongDan) throws IOException {
        // try-with-resources — tự động đóng resource
        try (BufferedReader reader = new BufferedReader(new FileReader(duongDan))) {
            return reader.readLine();
        }
    }

    // Method throws custom runtime exception
    public static void rutTien(double soDu, double soTien) {
        if (soTien > soDu) {
            throw new SoDuKhongDuException(soDu, soTien);
        }
        System.out.printf("Rút %.0f thành công. Còn lại: %.0f%n", soTien, soDu - soTien);
    }

    public static void main(String[] args) {
        // Multi-catch (Java 7+)
        try {
            String noiDung = docFile("test.txt");
            System.out.println(noiDung);
        } catch (FileNotFoundException e) {
            System.out.println("Không tìm thấy file: " + e.getMessage());
        } catch (IOException e) {
            System.out.println("Lỗi đọc file: " + e.getMessage());
        } finally {
            System.out.println("Luôn chạy dù có lỗi hay không");
        }

        // Xử lý custom exception
        try {
            rutTien(1_000_000, 5_000_000);
        } catch (SoDuKhongDuException e) {
            System.out.println("Lỗi: " + e.getMessage());
            System.out.println("Số dư hiện tại: " + e.getSoDuHienTai());
        }
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Oracle Tutorial — Exceptions](https://docs.oracle.com/javase/tutorial/essential/exceptions/index.html)
- Trong Spring Boot: `@ControllerAdvice` + `@ExceptionHandler` để xử lý exception toàn cục cho REST API.

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟢 Fresher | Checked vs Unchecked Exception — khác nhau thế nào? |
| 🟢 Fresher | `finally` block luôn luôn chạy? Có trường hợp nào không? |
| 🔵 Junior | Tại sao nên tạo Custom Exception thay vì dùng `RuntimeException` chung? |
| 🟡 Mid | `try-with-resources` hoạt động nội bộ thế nào? (`AutoCloseable` interface) |

</details>

### Nhóm 5: Generics

<details>
<summary>🔵 Generics</summary>

#### 📝 Định nghĩa
**Generics** cho phép tạo class, interface, method có thể làm việc với nhiều kiểu dữ liệu mà vẫn đảm bảo type safety tại compile-time. Generics sử dụng **type erasure** — thông tin kiểu bị xoá tại runtime. Wildcards: `? extends T` (upper bound), `? super T` (lower bound).

#### 💻 Ví dụ Code

```java
import java.util.*;

// Generic class — kiểu T được xác định khi sử dụng
class KetQua<T> {
    private final boolean thanhCong;
    private final T duLieu;
    private final String loiMessage;

    private KetQua(boolean thanhCong, T duLieu, String loiMessage) {
        this.thanhCong = thanhCong;
        this.duLieu = duLieu;
        this.loiMessage = loiMessage;
    }

    // Factory methods
    public static <T> KetQua<T> thanhCong(T duLieu) {
        return new KetQua<>(true, duLieu, null);
    }

    public static <T> KetQua<T> thatBai(String loi) {
        return new KetQua<>(false, null, loi);
    }

    public T getDuLieu() {
        if (!thanhCong) throw new IllegalStateException("Không có dữ liệu — " + loiMessage);
        return duLieu;
    }

    public boolean isThanhCong() { return thanhCong; }
}

public class GenericsDemo {
    // Generic method với bounded type — T phải là Number hoặc subclass
    public static <T extends Number & Comparable<T>> T timMax(List<T> danhSach) {
        return danhSach.stream()
                .max(Comparable::compareTo)
                .orElseThrow(() -> new IllegalArgumentException("Danh sách rỗng"));
    }

    // Wildcard: ? extends — đọc an toàn
    public static double tinhTong(List<? extends Number> danhSach) {
        return danhSach.stream()
                .mapToDouble(Number::doubleValue)
                .sum();
    }

    public static void main(String[] args) {
        // Dùng với Integer
        KetQua<Integer> kq1 = KetQua.thanhCong(42);
        System.out.println("Dữ liệu: " + kq1.getDuLieu()); // 42

        // Dùng với String
        KetQua<String> kq2 = KetQua.thatBai("Không tìm thấy");
        System.out.println("Thành công: " + kq2.isThanhCong()); // false

        // Generic method
        List<Integer> soNguyen = List.of(3, 1, 4, 1, 5, 9);
        System.out.println("Max: " + timMax(soNguyen)); // 9

        // Wildcard
        List<Double> soThuc = List.of(1.5, 2.5, 3.5);
        System.out.println("Tổng: " + tinhTong(soThuc)); // 7.5
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Oracle Tutorial — Generics](https://docs.oracle.com/javase/tutorial/java/generics/index.html)
- Spring Data JPA: `JpaRepository<T, ID>` — Generic interface dùng cho mọi Entity.

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🔵 Junior | Type Erasure là gì? Tại sao không thể dùng `new T()` trong generic class? |
| 🔵 Junior | `? extends T` vs `? super T` — PECS rule (Producer Extends, Consumer Super) |
| 🟡 Mid | Reifiable types vs Non-reifiable types? Tại sao không tạo được `new T[]`? |
| 🔴 Senior | Giải thích cách Spring Framework dùng generics + reflection để vượt qua type erasure? |

</details>

### Nhóm 6: Functional Programming & Stream API

<details>
<summary>🔵🟡 Lambda, Stream API & Optional</summary>

#### 📝 Định nghĩa
**Lambda** (Java 8) là cách viết ngắn gọn cho anonymous function, kết hợp với **Functional Interface** (interface có 1 abstract method). **Stream API** cung cấp pipeline xử lý dữ liệu theo kiểu declarative (khai báo). **Optional** giúp xử lý giá trị null an toàn, tránh `NullPointerException`.

#### 💻 Ví dụ Code

```java
import java.util.*;
import java.util.stream.*;

record NhanVien(String ten, String phongBan, double luong) {}

public class StreamDemo {
    public static void main(String[] args) {
        List<NhanVien> nhanViens = List.of(
            new NhanVien("An",    "IT",      25_000_000),
            new NhanVien("Bình",  "IT",      35_000_000),
            new NhanVien("Cường", "HR",      20_000_000),
            new NhanVien("Dũng",  "IT",      45_000_000),
            new NhanVien("Em",    "HR",      22_000_000),
            new NhanVien("Phúc",  "Finance", 30_000_000)
        );

        // 1. Filter + Map + Collect — lọc nhân viên IT lương > 30tr
        List<String> itLuongCao = nhanViens.stream()
                .filter(nv -> nv.phongBan().equals("IT"))    // Lọc
                .filter(nv -> nv.luong() > 30_000_000)       // Lọc tiếp
                .map(NhanVien::ten)                          // Chuyển đổi → lấy tên
                .sorted()                                    // Sắp xếp
                .collect(Collectors.toList());                // Thu thập
        System.out.println("IT lương cao: " + itLuongCao);   // [Bình, Dũng]

        // 2. GroupingBy — nhóm theo phòng ban
        Map<String, List<NhanVien>> theoPhongBan = nhanViens.stream()
                .collect(Collectors.groupingBy(NhanVien::phongBan));
        theoPhongBan.forEach((pb, ds) ->
            System.out.printf("%s: %d người%n", pb, ds.size()));

        // 3. Reduce — tính tổng lương
        double tongLuong = nhanViens.stream()
                .mapToDouble(NhanVien::luong)
                .sum();
        System.out.printf("Tổng lương: %,.0f VNĐ%n", tongLuong);

        // 4. Statistics — thống kê
        DoubleSummaryStatistics stats = nhanViens.stream()
                .mapToDouble(NhanVien::luong)
                .summaryStatistics();
        System.out.printf("TB: %,.0f | Min: %,.0f | Max: %,.0f%n",
                stats.getAverage(), stats.getMin(), stats.getMax());

        // 5. Optional — xử lý null an toàn
        Optional<NhanVien> timThay = nhanViens.stream()
                .filter(nv -> nv.ten().equals("An"))
                .findFirst();

        // Không bao giờ dùng get() trực tiếp — dùng orElse, map, ifPresent
        String ketQua = timThay
                .map(nv -> nv.ten() + " thuộc " + nv.phongBan())
                .orElse("Không tìm thấy");
        System.out.println(ketQua);
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Oracle Tutorial — Lambda Expressions](https://docs.oracle.com/javase/tutorial/java/javaOO/lambdaexpressions.html)
- [JDK 21 API — java.util.stream](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/stream/package-summary.html)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🔵 Junior | Stream `map()` vs `flatMap()` khác nhau thế nào? |
| 🔵 Junior | Tại sao Stream chỉ có thể consume 1 lần? |
| 🟡 Mid | `parallelStream()` khi nào nên dùng, khi nào không? |
| 🟡 Mid | Giải thích internal iteration vs external iteration |
| 🔴 Senior | Stream pipeline được lazy evaluate như thế nào? Short-circuiting operations? |

</details>

### Nhóm 7: Concurrency & Multithreading

<details>
<summary>🟡🔴 Concurrency & Multithreading</summary>

#### 📝 Định nghĩa
**Multithreading** cho phép chạy nhiều luồng đồng thời trong JVM. Java cung cấp: `Thread`, `Runnable`, `ExecutorService` (thread pool), `synchronized`, `Lock`, `Atomic` classes, và `CompletableFuture` cho async programming. Java 21+ có **Virtual Threads** (Project Loom) — lightweight threads cho high-concurrency.

#### 💻 Ví dụ Code

```java
import java.util.concurrent.*;
import java.util.List;

public class ConcurrencyDemo {
    // 1. ExecutorService — quản lý thread pool
    static void demoThreadPool() throws Exception {
        ExecutorService executor = Executors.newFixedThreadPool(3);

        List<Callable<String>> tasks = List.of(
            () -> { Thread.sleep(1000); return "Task 1 xong"; },
            () -> { Thread.sleep(500);  return "Task 2 xong"; },
            () -> { Thread.sleep(800);  return "Task 3 xong"; }
        );

        // invokeAll — chờ tất cả hoàn thành
        List<Future<String>> results = executor.invokeAll(tasks);
        for (Future<String> f : results) {
            System.out.println(f.get()); // Lấy kết quả
        }

        executor.shutdown();
    }

    // 2. CompletableFuture — async/await style
    static void demoCompletableFuture() {
        CompletableFuture<String> future = CompletableFuture
            .supplyAsync(() -> {
                // Chạy async trên ForkJoinPool
                return "Dữ liệu từ API";
            })
            .thenApply(data -> data.toUpperCase())        // Biến đổi
            .thenCombine(                                 // Kết hợp 2 futures
                CompletableFuture.supplyAsync(() -> " + Cache"),
                (a, b) -> a + b
            )
            .exceptionally(ex -> "Lỗi: " + ex.getMessage()); // Xử lý lỗi

        System.out.println(future.join()); // DỮ LIỆU TỪ API + Cache
    }

    // 3. Virtual Threads (Java 21+) — nhẹ, tạo hàng triệu threads
    static void demoVirtualThreads() throws Exception {
        try (var executor = Executors.newVirtualThreadPerTaskExecutor()) {
            // Tạo 10,000 virtual threads — không thể làm với platform threads
            for (int i = 0; i < 10_000; i++) {
                final int taskId = i;
                executor.submit(() -> {
                    // Mỗi virtual thread xử lý 1 request
                    if (taskId % 2500 == 0) {
                        System.out.println("Virtual thread #" + taskId +
                            " trên " + Thread.currentThread());
                    }
                });
            }
        } // Tự động shutdown
    }

    public static void main(String[] args) throws Exception {
        demoThreadPool();
        demoCompletableFuture();
        demoVirtualThreads();
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Oracle Tutorial — Concurrency](https://docs.oracle.com/javase/tutorial/essential/concurrency/index.html)
- [JEP 444 — Virtual Threads](https://openjdk.org/jeps/444)
- Spring Boot 3.2+ hỗ trợ Virtual Threads qua `spring.threads.virtual.enabled=true`.

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟡 Mid | `synchronized` vs `ReentrantLock` — khi nào dùng cái nào? |
| 🟡 Mid | Giải thích deadlock? Làm sao tránh? |
| 🟡 Mid | `volatile` keyword giải quyết vấn đề gì? (visibility problem) |
| 🔴 Senior | Virtual Threads khác Platform Threads thế nào? Khi nào KHÔNG nên dùng Virtual Threads? |
| 🔴 Senior | Structured Concurrency (Java 21 preview) giải quyết bài toán gì? |
| 🔴 Senior | `CompletableFuture` vs Reactive (Project Reactor) — trade-offs? |

</details>

### Nhóm 8: I/O & NIO

<details>
<summary>🔵 I/O & NIO</summary>

#### 📝 Định nghĩa
**Java I/O** (java.io) là API truyền thống cho đọc/ghi file theo stream (byte-stream, character-stream). **Java NIO** (java.nio) cung cấp non-blocking I/O, `Path`, `Files`, `Channel`, `Buffer` — hiệu suất cao hơn và API hiện đại hơn. Nên dùng NIO (`java.nio.file`) cho code mới.

#### 💻 Ví dụ Code

```java
import java.nio.file.*;
import java.io.IOException;
import java.util.List;
import java.util.stream.Stream;

public class NIODemo {
    public static void main(String[] args) throws IOException {
        Path filePath = Path.of("data", "sinhvien.txt");

        // Tạo thư mục nếu chưa có
        Files.createDirectories(filePath.getParent());

        // Ghi file — đơn giản
        List<String> danhSach = List.of("An - 8.5", "Bình - 7.0", "Cường - 9.2");
        Files.write(filePath, danhSach);
        System.out.println("Đã ghi file");

        // Đọc tất cả dòng
        List<String> dongDoc = Files.readAllLines(filePath);
        dongDoc.forEach(System.out::println);

        // Đọc file lớn bằng Stream — lazy loading, tiết kiệm bộ nhớ
        try (Stream<String> lines = Files.lines(filePath)) {
            long soDongDiemCao = lines
                .filter(line -> {
                    double diem = Double.parseDouble(line.split(" - ")[1]);
                    return diem >= 8.0;
                })
                .count();
            System.out.println("Số sinh viên điểm >= 8: " + soDongDiemCao);
        }

        // Liệt kê file trong thư mục
        try (Stream<Path> paths = Files.list(Path.of("data"))) {
            paths.forEach(p -> System.out.println("File: " + p.getFileName()));
        }

        // Kiểm tra file
        System.out.println("Tồn tại: " + Files.exists(filePath));
        System.out.println("Kích thước: " + Files.size(filePath) + " bytes");

        // Xoá file
        Files.deleteIfExists(filePath);
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Oracle Tutorial — File I/O (NIO.2)](https://docs.oracle.com/javase/tutorial/essential/io/fileio.html)
- [JDK 21 API — java.nio.file.Files](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/nio/file/Files.html)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🔵 Junior | `java.io` vs `java.nio` — khác nhau cơ bản? |
| 🔵 Junior | Tại sao dùng `try-with-resources` khi đọc/ghi file? |
| 🟡 Mid | Blocking I/O vs Non-blocking I/O — hoạt động thế nào? |

</details>

### Nhóm 9: JVM Internals & Memory Management

<details>
<summary>🟡🔴 JVM Internals & Memory Management</summary>

#### 📝 Định nghĩa
**JVM** (Java Virtual Machine) biên dịch bytecode thành machine code tại runtime qua **JIT compiler**. Bộ nhớ JVM chia thành: **Heap** (objects), **Stack** (local variables, method calls), **Metaspace** (class metadata). **Garbage Collector** (GC) tự động thu hồi bộ nhớ — G1 là mặc định, ZGC cho low-latency.

#### 💻 Ví dụ Code

```java
public class JVMDemo {
    public static void main(String[] args) {
        // Xem thông tin bộ nhớ
        Runtime runtime = Runtime.getRuntime();
        long maxMemory = runtime.maxMemory() / (1024 * 1024);       // -Xmx
        long totalMemory = runtime.totalMemory() / (1024 * 1024);   // Heap đã cấp
        long freeMemory = runtime.freeMemory() / (1024 * 1024);     // Heap trống

        System.out.printf("Max: %d MB | Total: %d MB | Free: %d MB%n",
                maxMemory, totalMemory, freeMemory);

        // Demo: tạo nhiều objects để thấy GC hoạt động
        System.out.println("Đang tạo objects...");
        for (int i = 0; i < 1_000_000; i++) {
            // Objects này sẽ được GC thu hồi vì không có reference
            byte[] data = new byte[100];
        }

        // Gợi ý GC chạy (không đảm bảo GC sẽ chạy)
        System.gc();

        long freeAfterGC = runtime.freeMemory() / (1024 * 1024);
        System.out.printf("Free sau GC: %d MB%n", freeAfterGC);

        // String Pool — demo interning
        String s1 = new String("Hello");   // Tạo object mới trên heap
        String s2 = "Hello";               // Từ String Pool
        String s3 = s1.intern();           // Đưa vào Pool, trả reference pool

        System.out.println(s1 == s2);  // false — khác reference
        System.out.println(s2 == s3);  // true  — cùng pool reference
    }
}

/*
 * Các JVM flags thường dùng:
 * -Xms512m          Heap khởi tạo 512MB
 * -Xmx2g            Heap tối đa 2GB
 * -XX:+UseG1GC      Dùng G1 Garbage Collector (mặc định)
 * -XX:+UseZGC       Dùng ZGC (low-latency, Java 15+)
 * -XX:+PrintGCDetails  In chi tiết GC
 * -XX:MetaspaceSize=256m  Metaspace ban đầu
 */
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Oracle — JVM Specification](https://docs.oracle.com/javase/specs/jvms/se21/html/index.html)
- [Oracle — G1 Garbage Collector](https://docs.oracle.com/en/java/javase/21/gctuning/garbage-first-g1-garbage-collector1.html)
- Trong production: dùng **JFR** (Java Flight Recorder) và **JMC** (Java Mission Control) để profiling.

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟡 Mid | Giải thích cấu trúc bộ nhớ JVM (Heap, Stack, Metaspace)? |
| 🟡 Mid | Garbage Collection hoạt động thế nào? Young Gen vs Old Gen? |
| 🔴 Senior | So sánh G1, ZGC, Shenandoah — khi nào dùng loại nào? |
| 🔴 Senior | Làm thế nào để debug memory leak trong production? |
| 🔴 Senior | ClassLoader hierarchy hoạt động ra sao? Custom ClassLoader khi nào cần? |

</details>

### Nhóm 10: Modern Java Features (Java 17–21+)

<details>
<summary>🔵🟡🔴 Modern Java Features</summary>

#### 📝 Định nghĩa
Java phát triển nhanh với release 6 tháng/lần. Các tính năng quan trọng: **Records** (Java 16) — immutable data classes, **Sealed Classes** (Java 17) — giới hạn inheritance, **Pattern Matching** (Java 16–21) — kiểm tra và cast type an toàn, **Text Blocks** (Java 15) — chuỗi nhiều dòng.

#### 💻 Ví dụ Code

```java
import java.util.List;

// Record (Java 16+) — tự sinh constructor, getters, equals, hashCode, toString
record SanPham(String ten, double gia, String danhMuc) {
    // Compact constructor — validation
    SanPham {
        if (gia < 0) throw new IllegalArgumentException("Giá phải >= 0");
        ten = ten.trim(); // Có thể thay đổi tham số trong compact constructor
    }

    // Có thể thêm method
    String hienThiGia() {
        return String.format("%s: %,.0f VNĐ", ten, gia);
    }
}

// Sealed class (Java 17+) — chỉ cho phép các class cụ thể kế thừa
sealed interface HinhDang permits HinhTron2D, HinhVuong, HinhTamGiac {}

record HinhTron2D(double banKinh) implements HinhDang {}
record HinhVuong(double canh) implements HinhDang {}
record HinhTamGiac(double day, double cao) implements HinhDang {}

public class ModernJavaDemo {
    // Pattern matching cho instanceof (Java 16+)
    static String moTa(Object obj) {
        if (obj instanceof String s && !s.isEmpty()) {
            return "Chuỗi: " + s.toUpperCase();
        } else if (obj instanceof Integer i && i > 0) {
            return "Số dương: " + i;
        } else {
            return "Kiểu khác: " + obj;
        }
    }

    // Pattern matching cho switch (Java 21+)
    static double tinhDienTich(HinhDang hinh) {
        return switch (hinh) {
            case HinhTron2D h   -> Math.PI * h.banKinh() * h.banKinh();
            case HinhVuong h    -> h.canh() * h.canh();
            case HinhTamGiac h  -> 0.5 * h.day() * h.cao();
        };
        // Không cần default vì sealed — compiler biết đã cover hết
    }

    public static void main(String[] args) {
        // Text Blocks (Java 15+) — chuỗi nhiều dòng
        String json = """
                {
                    "ten": "iPhone 15",
                    "gia": 25000000,
                    "danhMuc": "Điện thoại"
                }
                """;
        System.out.println(json);

        // Record
        var sp = new SanPham("iPhone 15", 25_000_000, "Điện thoại");
        System.out.println(sp);              // SanPham[ten=iPhone 15, gia=2.5E7, ...]
        System.out.println(sp.hienThiGia()); // iPhone 15: 25,000,000 VNĐ

        // Pattern matching switch
        List<HinhDang> cacHinh = List.of(
            new HinhTron2D(5), new HinhVuong(4), new HinhTamGiac(6, 3)
        );
        cacHinh.forEach(h ->
            System.out.printf("%s → Diện tích: %.2f%n", h, tinhDienTich(h))
        );
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [JEP 395 — Records](https://openjdk.org/jeps/395)
- [JEP 409 — Sealed Classes](https://openjdk.org/jeps/409)
- [JEP 441 — Pattern Matching for switch](https://openjdk.org/jeps/441)
- Spring Boot 3.x yêu cầu Java 17+ — Records thường dùng cho DTOs.

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🔵 Junior | Record khác class thường thế nào? Khi nào nên dùng? |
| 🟡 Mid | Sealed class giải quyết vấn đề gì trong thiết kế domain? |
| 🟡 Mid | Pattern matching cho switch giúp gì so với visitor pattern? |
| 🔴 Senior | Giải thích deconstruction patterns (Java 21) và ứng dụng? |

</details>

### Nhóm 11: Design Patterns

<details>
<summary>🟡🔴 Design Patterns</summary>

#### 📝 Định nghĩa
**Design Patterns** là các giải pháp thiết kế đã được chứng minh cho các bài toán phổ biến. Chia thành 3 nhóm: **Creational** (Singleton, Factory, Builder), **Structural** (Adapter, Decorator, Proxy), **Behavioral** (Observer, Strategy, Template Method). Spring Framework sử dụng rất nhiều patterns.

#### 💻 Ví dụ Code

```java
import java.util.*;
import java.util.function.Supplier;

// === BUILDER PATTERN — xây dựng object phức tạp từng bước ===
class HttpRequest {
    private final String method;
    private final String url;
    private final Map<String, String> headers;
    private final String body;

    private HttpRequest(Builder builder) {
        this.method = builder.method;
        this.url = builder.url;
        this.headers = Map.copyOf(builder.headers);
        this.body = builder.body;
    }

    static class Builder {
        private String method = "GET";
        private String url;
        private Map<String, String> headers = new HashMap<>();
        private String body;

        Builder url(String url) { this.url = url; return this; }
        Builder method(String m) { this.method = m; return this; }
        Builder header(String k, String v) { headers.put(k, v); return this; }
        Builder body(String body) { this.body = body; return this; }

        HttpRequest build() {
            Objects.requireNonNull(url, "URL là bắt buộc");
            return new HttpRequest(this);
        }
    }

    @Override
    public String toString() {
        return method + " " + url + " | Headers: " + headers;
    }
}

// === STRATEGY PATTERN — chọn thuật toán tại runtime ===
// Dùng Functional Interface thay cho class hierarchy
@FunctionalInterface
interface ChietKhau {
    double tinhGia(double giaGoc);
}

class GioHang {
    private final List<Double> sanPhams = new ArrayList<>();
    private ChietKhau chieuKhau = gia -> gia; // Mặc định: không giảm

    void them(double gia) { sanPhams.add(gia); }

    void setChietKhau(ChietKhau ck) { this.chieuKhau = ck; }

    double tongTien() {
        return sanPhams.stream()
                .mapToDouble(chieuKhau::tinhGia)
                .sum();
    }
}

public class DesignPatternDemo {
    public static void main(String[] args) {
        // Builder
        var request = new HttpRequest.Builder()
                .url("https://api.example.com/users")
                .method("POST")
                .header("Content-Type", "application/json")
                .header("Authorization", "Bearer token123")
                .body("{\"name\": \"An\"}")
                .build();
        System.out.println(request);

        // Strategy — thay đổi hành vi tại runtime
        GioHang gh = new GioHang();
        gh.them(100_000);
        gh.them(200_000);

        System.out.println("Không giảm: " + gh.tongTien());

        gh.setChietKhau(gia -> gia * 0.9);  // Giảm 10%
        System.out.println("Giảm 10%: " + gh.tongTien());

        gh.setChietKhau(gia -> gia > 150_000 ? gia * 0.8 : gia); // Giảm 20% cho đơn > 150k
        System.out.println("Giảm 20% (>150k): " + gh.tongTien());
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Refactoring.Guru — Design Patterns in Java](https://refactoring.guru/design-patterns/java)
- Spring dùng: Singleton (Bean mặc định), Factory (BeanFactory), Proxy (AOP), Template Method (JdbcTemplate), Observer (ApplicationEvent).

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟡 Mid | Singleton thread-safe: những cách nào? Enum Singleton ưu điểm gì? |
| 🟡 Mid | Factory Method vs Abstract Factory — khác nhau? |
| 🔴 Senior | Spring Framework sử dụng những design patterns nào? Cho ví dụ cụ thể? |
| 🔴 Senior | Khi nào KHÔNG nên dùng design patterns? (Over-engineering) |

</details>

### Nhóm 12: Testing

<details>
<summary>🔵🟡 Testing với JUnit 5 & Mockito</summary>

#### 📝 Định nghĩa
**JUnit 5** là framework testing tiêu chuẩn cho Java gồm 3 module: JUnit Platform, JUnit Jupiter (API mới), JUnit Vintage (tương thích JUnit 4). **Mockito** dùng để tạo mock objects, giúp test đơn vị không phụ thuộc vào dependencies bên ngoài (database, API).

#### 💻 Ví dụ Code

```java
import org.junit.jupiter.api.*;
import org.junit.jupiter.params.ParameterizedTest;
import org.junit.jupiter.params.provider.CsvSource;
import static org.junit.jupiter.api.Assertions.*;

// Class cần test
class MayTinh {
    double chia(double a, double b) {
        if (b == 0) throw new ArithmeticException("Không thể chia cho 0");
        return a / b;
    }

    String xepLoai(double diem) {
        if (diem < 0 || diem > 10) throw new IllegalArgumentException("Điểm không hợp lệ");
        if (diem >= 8) return "Giỏi";
        if (diem >= 6.5) return "Khá";
        if (diem >= 5) return "Trung bình";
        return "Yếu";
    }
}

// Test class
class MayTinhTest {
    private MayTinh mayTinh;

    @BeforeEach // Chạy trước mỗi test
    void setUp() {
        mayTinh = new MayTinh();
    }

    @Test
    @DisplayName("Chia 2 số dương cho kết quả đúng")
    void chia_SoDuong_TraVeKetQuaDung() {
        assertEquals(2.5, mayTinh.chia(5, 2));
    }

    @Test
    @DisplayName("Chia cho 0 phải throw ArithmeticException")
    void chia_ChoCho0_ThrowException() {
        assertThrows(ArithmeticException.class, () -> mayTinh.chia(10, 0));
    }

    // Parameterized test — test nhiều trường hợp cùng lúc
    @ParameterizedTest
    @CsvSource({
        "9.0,  Giỏi",
        "8.0,  Giỏi",
        "7.0,  Khá",
        "6.5,  Khá",
        "5.0,  Trung bình",
        "3.0,  Yếu"
    })
    @DisplayName("Xếp loại đúng theo điểm")
    void xepLoai_DiemHopLe_TraVeXepLoaiDung(double diem, String expected) {
        assertEquals(expected, mayTinh.xepLoai(diem));
    }

    @Test
    void xepLoai_DiemAm_ThrowException() {
        assertThrows(IllegalArgumentException.class, () -> mayTinh.xepLoai(-1));
    }

    @Test
    @DisplayName("Nhóm assertions — kiểm tra nhiều điều kiện")
    void kiemTraNhieuDieuKien() {
        assertAll("Xếp loại biên",
            () -> assertEquals("Giỏi", mayTinh.xepLoai(8.0)),
            () -> assertEquals("Khá", mayTinh.xepLoai(6.5)),
            () -> assertEquals("Trung bình", mayTinh.xepLoai(5.0))
        );
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [JUnit 5 User Guide](https://junit.org/junit5/docs/current/user-guide/)
- [Mockito Documentation](https://site.mockito.org/)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🔵 Junior | Unit Test vs Integration Test — khác nhau? |
| 🔵 Junior | `@Mock` vs `@Spy` trong Mockito? |
| 🟡 Mid | Test coverage bao nhiêu % là đủ? Khi nào test trở nên vô nghĩa? |
| 🟡 Mid | TDD (Test-Driven Development) workflow như thế nào? |

</details>

---

## Phần 3 — Thẻ Khái niệm Spring Boot

> **So sánh framework cạnh tranh:** Spring Boot vs **Quarkus** (cloud-native, GraalVM native), **Micronaut** (compile-time DI, nhẹ hơn). Spring Boot có hệ sinh thái lớn nhất, cộng đồng đông nhất, và được sử dụng rộng rãi nhất trong enterprise.

### Nhóm A: Spring Core & IoC

<details>
<summary>🟢 IoC Container & Dependency Injection</summary>

#### 📝 Định nghĩa
**IoC** (Inversion of Control) là nguyên tắc thiết kế: thay vì object tự tạo dependencies, **Spring Container** tạo và inject chúng. **Dependency Injection** (DI) là implementation cụ thể: **Constructor Injection** (khuyến nghị), **Setter Injection**, **Field Injection** (`@Autowired` — không khuyến nghị).

#### 💻 Ví dụ Code

```java
import org.springframework.stereotype.*;
import org.springframework.beans.factory.annotation.Autowired;

// Interface — contract
interface ThongBaoService {
    void gui(String nguoiNhan, String noiDung);
}

// Implementation 1
@Service // Đánh dấu là Spring Bean
class EmailService implements ThongBaoService {
    @Override
    public void gui(String nguoiNhan, String noiDung) {
        System.out.printf("📧 Gửi email tới %s: %s%n", nguoiNhan, noiDung);
    }
}

// Implementation 2
@Service
class SmsService implements ThongBaoService {
    @Override
    public void gui(String nguoiNhan, String noiDung) {
        System.out.printf("📱 Gửi SMS tới %s: %s%n", nguoiNhan, noiDung);
    }
}

// === CONSTRUCTOR INJECTION — cách được khuyến nghị ===
@Service
class DonHangService {
    private final ThongBaoService thongBaoService;

    // Spring tự inject — không cần @Autowired khi chỉ có 1 constructor
    // Dùng @Qualifier để chọn implementation cụ thể
    public DonHangService(@Qualifier("emailService") ThongBaoService thongBaoService) {
        this.thongBaoService = thongBaoService;
    }

    public void datHang(String maKH) {
        // Business logic...
        thongBaoService.gui(maKH, "Đơn hàng đã được đặt thành công!");
    }
}

/*
 * Tại sao Constructor Injection tốt hơn:
 * 1. Dependencies là final → immutable, thread-safe
 * 2. Không thể tạo object thiếu dependency → fail fast
 * 3. Dễ test — chỉ cần truyền mock qua constructor
 * 4. Không cần Spring để test (plain Java constructor)
 */
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Spring Framework Docs — IoC Container](https://docs.spring.io/spring-framework/reference/core/beans.html)
- [Spring Boot Reference](https://docs.spring.io/spring-boot/reference/)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟢 Fresher | IoC và Dependency Injection khác nhau thế nào? |
| 🟢 Fresher | `@Component`, `@Service`, `@Repository`, `@Controller` khác nhau? |
| 🔵 Junior | Tại sao Constructor Injection được khuyến nghị hơn Field Injection? |
| 🟡 Mid | Giải thích Bean lifecycle: instantiation → population → initialization → destruction? |

</details>

<details>
<summary>🟢🔵 Bean Scopes & Configuration</summary>

#### 📝 Định nghĩa
**Bean Scope** xác định lifecycle và khả năng chia sẻ của Bean: `singleton` (mặc định — 1 instance/container), `prototype` (instance mới mỗi lần request), `request` (1 per HTTP request), `session` (1 per session). **Configuration** có thể khai báo qua `@Configuration` + `@Bean`, hoặc `application.properties`/`application.yml`.

#### 💻 Ví dụ Code

```java
import org.springframework.context.annotation.*;
import org.springframework.beans.factory.config.ConfigurableBeanFactory;

// Java-based Configuration
@Configuration
public class AppConfig {

    // Singleton — mặc định, chỉ tạo 1 lần
    @Bean
    public EmailClient emailClient() {
        return new EmailClient("smtp.gmail.com", 587);
    }

    // Prototype — mỗi lần inject tạo instance mới
    @Bean
    @Scope(ConfigurableBeanFactory.SCOPE_PROTOTYPE)
    public BaoCaoBuilder baoCaoBuilder() {
        return new BaoCaoBuilder();
    }

    // Conditional Bean — chỉ tạo khi profile = "production"
    @Bean
    @Profile("production")
    public DataSource productionDataSource() {
        return new HikariDataSource(productionConfig());
    }

    @Bean
    @Profile("dev")
    public DataSource devDataSource() {
        return new H2DataSource(); // Dùng H2 in-memory cho dev
    }
}
```

```yaml
# application.yml — cấu hình ứng dụng
spring:
  application:
    name: my-app
  profiles:
    active: dev         # Profile đang dùng

  datasource:
    url: jdbc:mysql://localhost:3306/mydb
    username: root
    password: ${DB_PASSWORD}  # Đọc từ environment variable

server:
  port: 8080

# Custom properties
app:
  jwt:
    secret: ${JWT_SECRET:defaultSecret}  # Giá trị mặc định nếu không set
    expiration: 86400000
```

```java
// Đọc custom properties
@Component
@ConfigurationProperties(prefix = "app.jwt") // Bind tự động
public class JwtConfig {
    private String secret;
    private long expiration;

    // Getters & Setters
    public String getSecret() { return secret; }
    public void setSecret(String secret) { this.secret = secret; }
    public long getExpiration() { return expiration; }
    public void setExpiration(long expiration) { this.expiration = expiration; }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Spring Boot — Externalized Configuration](https://docs.spring.io/spring-boot/reference/features/external-config.html)
- [Spring — Bean Scopes](https://docs.spring.io/spring-framework/reference/core/beans/factory-scopes.html)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟢 Fresher | Singleton scope nghĩa là gì trong Spring? Khác gì Singleton pattern? |
| 🔵 Junior | `@Configuration` vs `@Component` — khác nhau? (CGLIB proxy) |
| 🔵 Junior | Thứ tự ưu tiên configuration: properties file → YAML → env vars → CLI args? |
| 🟡 Mid | Khi nào cần `@ConfigurationProperties` thay vì `@Value`? |

</details>

### Nhóm B: Spring Boot Basics

<details>
<summary>🟢 Auto-Configuration & Starters</summary>

#### 📝 Định nghĩa
**Auto-Configuration** là cơ chế Spring Boot tự cấu hình ứng dụng dựa trên classpath dependencies. Khi thêm `spring-boot-starter-web`, Spring Boot tự cấu hình embedded Tomcat, DispatcherServlet, Jackson. **Starters** là bộ dependency packages đi kèm cho từng use case (web, data, security...).

#### 💻 Ví dụ Code

```java
import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

// @SpringBootApplication = @Configuration + @EnableAutoConfiguration + @ComponentScan
@SpringBootApplication
public class MyApplication {
    public static void main(String[] args) {
        SpringApplication.run(MyApplication.class, args);
    }
}

/*
 * Starters phổ biến:
 * spring-boot-starter-web        → REST APIs, embedded Tomcat
 * spring-boot-starter-data-jpa   → JPA + Hibernate
 * spring-boot-starter-security   → Spring Security
 * spring-boot-starter-validation → Bean Validation
 * spring-boot-starter-test       → JUnit 5, Mockito, AssertJ
 * spring-boot-starter-actuator   → Health checks, metrics
 *
 * Xem auto-configuration nào đang active:
 * application.properties → debug=true
 * Hoặc chạy: java -jar app.jar --debug
 */
```

```xml
<!-- pom.xml — Maven dependencies -->
<parent>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-parent</artifactId>
    <version>3.3.0</version>
</parent>

<dependencies>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-data-jpa</artifactId>
    </dependency>
    <!-- Chỉ cần thêm dependency → Auto-Configuration lo phần còn lại -->
</dependencies>
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Spring Boot — Auto-Configuration](https://docs.spring.io/spring-boot/reference/using/auto-configuration.html)
- [Spring Initializr](https://start.spring.io/) — tạo project Spring Boot nhanh

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟢 Fresher | `@SpringBootApplication` bao gồm những annotation nào? |
| 🔵 Junior | Auto-Configuration hoạt động bên trong thế nào? (`META-INF/spring/org.springframework.boot.autoconfigure.AutoConfiguration.imports`) |
| 🟡 Mid | Làm sao tắt một auto-configuration cụ thể? (`@EnableAutoConfiguration(exclude = ...)`) |

</details>

### Nhóm C: REST API Development

<details>
<summary>🟢🔵 REST Controller & Exception Handling</summary>

#### 📝 Định nghĩa
Spring Boot dùng `@RestController` để tạo RESTful endpoints. Các annotation mapping: `@GetMapping`, `@PostMapping`, `@PutMapping`, `@DeleteMapping`. **`@ControllerAdvice`** xử lý exception tập trung cho toàn bộ API. **DTO Pattern** tách biệt entity (DB model) và response/request object.

#### 💻 Ví dụ Code

```java
import org.springframework.web.bind.annotation.*;
import org.springframework.http.*;
import jakarta.validation.Valid;
import jakarta.validation.constraints.*;
import java.util.*;

// DTO — Request
record TaoSinhVienRequest(
    @NotBlank(message = "Tên không được trống")
    String hoTen,

    @Email(message = "Email không hợp lệ")
    String email,

    @Min(value = 0, message = "Điểm tối thiểu là 0")
    @Max(value = 10, message = "Điểm tối đa là 10")
    double diemTB
) {}

// DTO — Response
record SinhVienResponse(Long id, String hoTen, String email, double diemTB, String xepLoai) {}

// REST Controller
@RestController
@RequestMapping("/api/v1/sinh-vien")
public class SinhVienController {

    private final SinhVienService sinhVienService;

    public SinhVienController(SinhVienService sinhVienService) {
        this.sinhVienService = sinhVienService;
    }

    // GET — lấy danh sách có phân trang
    @GetMapping
    public ResponseEntity<Page<SinhVienResponse>> layDanhSach(
            @RequestParam(defaultValue = "0") int page,
            @RequestParam(defaultValue = "10") int size,
            @RequestParam(defaultValue = "hoTen") String sortBy) {
        return ResponseEntity.ok(sinhVienService.layDanhSach(page, size, sortBy));
    }

    // GET — lấy theo ID
    @GetMapping("/{id}")
    public ResponseEntity<SinhVienResponse> layTheoId(@PathVariable Long id) {
        return ResponseEntity.ok(sinhVienService.layTheoId(id));
    }

    // POST — tạo mới, @Valid kích hoạt validation
    @PostMapping
    public ResponseEntity<SinhVienResponse> taoMoi(@Valid @RequestBody TaoSinhVienRequest request) {
        SinhVienResponse response = sinhVienService.taoMoi(request);
        return ResponseEntity.status(HttpStatus.CREATED).body(response);
    }

    // PUT — cập nhật
    @PutMapping("/{id}")
    public ResponseEntity<SinhVienResponse> capNhat(
            @PathVariable Long id,
            @Valid @RequestBody TaoSinhVienRequest request) {
        return ResponseEntity.ok(sinhVienService.capNhat(id, request));
    }

    // DELETE
    @DeleteMapping("/{id}")
    public ResponseEntity<Void> xoa(@PathVariable Long id) {
        sinhVienService.xoa(id);
        return ResponseEntity.noContent().build();
    }
}

// === Global Exception Handler ===
@RestControllerAdvice
public class GlobalExceptionHandler {

    // Xử lý resource không tìm thấy
    @ExceptionHandler(ResourceNotFoundException.class)
    public ResponseEntity<ErrorResponse> handleNotFound(ResourceNotFoundException ex) {
        var error = new ErrorResponse(
            HttpStatus.NOT_FOUND.value(),
            ex.getMessage(),
            LocalDateTime.now()
        );
        return ResponseEntity.status(HttpStatus.NOT_FOUND).body(error);
    }

    // Xử lý validation errors
    @ExceptionHandler(MethodArgumentNotValidException.class)
    public ResponseEntity<ErrorResponse> handleValidation(MethodArgumentNotValidException ex) {
        String message = ex.getBindingResult().getFieldErrors().stream()
            .map(e -> e.getField() + ": " + e.getDefaultMessage())
            .collect(Collectors.joining(", "));

        var error = new ErrorResponse(400, message, LocalDateTime.now());
        return ResponseEntity.badRequest().body(error);
    }
}

record ErrorResponse(int status, String message, LocalDateTime timestamp) {}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Spring MVC — Annotated Controllers](https://docs.spring.io/spring-framework/reference/web/webmvc/mvc-controller.html)
- [Spring Boot — Error Handling](https://docs.spring.io/spring-boot/reference/web/servlet.html#web.servlet.spring-mvc.error-handling)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟢 Fresher | `@Controller` vs `@RestController` khác nhau? |
| 🟢 Fresher | `@RequestBody` vs `@RequestParam` vs `@PathVariable`? |
| 🔵 Junior | Tại sao dùng DTO thay vì trả Entity trực tiếp? |
| 🔵 Junior | HTTP status codes nào nên dùng cho từng loại response? |
| 🟡 Mid | Làm sao thiết kế REST API versioning? (URL path vs Header vs Query param) |

</details>

### Nhóm D: Data Access (JPA/Hibernate)

<details>
<summary>🟢🔵🟡 Spring Data JPA & Hibernate</summary>

#### 📝 Định nghĩa
**JPA** (Java Persistence API) là specification, **Hibernate** là implementation phổ biến nhất. **Spring Data JPA** thêm layer trừu tượng: chỉ cần khai báo interface, Spring tự sinh implementation. Hỗ trợ: query methods, `@Query` (JPQL/native), Specifications, Pagination.

#### 💻 Ví dụ Code

```java
import jakarta.persistence.*;
import org.springframework.data.jpa.repository.*;
import org.springframework.data.domain.*;
import java.util.*;

// Entity — mapping với bảng database
@Entity
@Table(name = "sinh_vien")
public class SinhVien {

    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    @Column(nullable = false, length = 100)
    private String hoTen;

    @Column(unique = true)
    private String email;

    private double diemTB;

    @Enumerated(EnumType.STRING)
    private TrangThai trangThai = TrangThai.DANG_HOC;

    @ManyToOne(fetch = FetchType.LAZY) // LAZY — không load Lop khi query SinhVien
    @JoinColumn(name = "lop_id")
    private Lop lop;

    @CreationTimestamp
    private LocalDateTime ngayTao;

    // Constructors, Getters, Setters...
}

enum TrangThai { DANG_HOC, DA_TOT_NGHIEP, NGHI_HOC }

// Repository — Spring Data JPA tự sinh implementation
public interface SinhVienRepository extends JpaRepository<SinhVien, Long> {

    // Query method — Spring tự sinh SQL từ tên method
    List<SinhVien> findByHoTenContainingIgnoreCase(String keyword);

    List<SinhVien> findByDiemTBGreaterThanEqual(double diem);

    Optional<SinhVien> findByEmail(String email);

    // JPQL — Java Persistence Query Language
    @Query("SELECT sv FROM SinhVien sv WHERE sv.lop.ten = :tenLop AND sv.diemTB >= :diem")
    List<SinhVien> timSinhVienGioi(@Param("tenLop") String tenLop, @Param("diem") double diem);

    // Native SQL — cho query phức tạp
    @Query(value = "SELECT * FROM sinh_vien WHERE diem_tb >= :diem ORDER BY diem_tb DESC LIMIT :limit",
           nativeQuery = true)
    List<SinhVien> topSinhVien(@Param("diem") double diem, @Param("limit") int limit);

    // Phân trang
    Page<SinhVien> findByTrangThai(TrangThai trangThai, Pageable pageable);

    // Modifying query
    @Modifying
    @Query("UPDATE SinhVien sv SET sv.trangThai = :trangThai WHERE sv.diemTB < :diem")
    int capNhatTrangThai(@Param("trangThai") TrangThai trangThai, @Param("diem") double diem);
}

// Service layer — business logic + transaction
@Service
@Transactional(readOnly = true) // Mặc định read-only cho performance
public class SinhVienService {

    private final SinhVienRepository repo;

    public SinhVienService(SinhVienRepository repo) {
        this.repo = repo;
    }

    public Page<SinhVienResponse> layDanhSach(int page, int size, String sortBy) {
        Pageable pageable = PageRequest.of(page, size, Sort.by(sortBy));
        return repo.findAll(pageable).map(this::toResponse);
    }

    @Transactional // Override: cho phép write
    public SinhVienResponse taoMoi(TaoSinhVienRequest request) {
        // Kiểm tra email trùng
        if (repo.findByEmail(request.email()).isPresent()) {
            throw new DuplicateResourceException("Email đã tồn tại: " + request.email());
        }

        SinhVien sv = new SinhVien();
        sv.setHoTen(request.hoTen());
        sv.setEmail(request.email());
        sv.setDiemTB(request.diemTB());

        return toResponse(repo.save(sv));
    }

    private SinhVienResponse toResponse(SinhVien sv) {
        return new SinhVienResponse(sv.getId(), sv.getHoTen(), sv.getEmail(),
                sv.getDiemTB(), tinhXepLoai(sv.getDiemTB()));
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Spring Data JPA Reference](https://docs.spring.io/spring-data/jpa/reference/)
- [Hibernate ORM Documentation](https://hibernate.org/orm/documentation/)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟢 Fresher | JPA vs Hibernate — cái nào là specification, cái nào là implementation? |
| 🔵 Junior | `FetchType.LAZY` vs `FetchType.EAGER` — khi nào dùng? N+1 problem là gì? |
| 🔵 Junior | `@Transactional` hoạt động thế nào? Propagation levels? |
| 🟡 Mid | Cách tối ưu JPA query: EntityGraph, JOIN FETCH, batch size? |
| 🟡 Mid | First-level cache (Persistence Context) vs Second-level cache? |
| 🔴 Senior | Optimistic Locking (`@Version`) vs Pessimistic Locking — khi nào dùng? |

</details>

### Nhóm E: Spring Security

<details>
<summary>🟡 Spring Security & JWT</summary>

#### 📝 Định nghĩa
**Spring Security** là framework bảo mật toàn diện cho Authentication (xác thực — ai?) và Authorization (phân quyền — được làm gì?). **JWT** (JSON Web Token) là stateless token thường dùng cho REST API — token chứa thông tin user, server không cần lưu session.

#### 💻 Ví dụ Code

```java
import org.springframework.security.config.annotation.web.builders.HttpSecurity;
import org.springframework.security.config.annotation.web.configuration.EnableWebSecurity;
import org.springframework.security.config.http.SessionCreationPolicy;
import org.springframework.context.annotation.Bean;
import org.springframework.context.annotation.Configuration;

@Configuration
@EnableWebSecurity
public class SecurityConfig {

    private final JwtAuthFilter jwtAuthFilter;

    public SecurityConfig(JwtAuthFilter jwtAuthFilter) {
        this.jwtAuthFilter = jwtAuthFilter;
    }

    @Bean
    public SecurityFilterChain securityFilterChain(HttpSecurity http) throws Exception {
        return http
            .csrf(csrf -> csrf.disable())                // Tắt CSRF cho REST API
            .sessionManagement(session ->
                session.sessionCreationPolicy(SessionCreationPolicy.STATELESS)) // Không dùng session
            .authorizeHttpRequests(auth -> auth
                .requestMatchers("/api/v1/auth/**").permitAll()      // Public endpoints
                .requestMatchers("/api/v1/admin/**").hasRole("ADMIN") // Chỉ ADMIN
                .requestMatchers(HttpMethod.GET, "/api/v1/san-pham/**").permitAll()
                .anyRequest().authenticated()                         // Còn lại phải đăng nhập
            )
            .addFilterBefore(jwtAuthFilter, UsernamePasswordAuthenticationFilter.class)
            .build();
    }

    @Bean
    public PasswordEncoder passwordEncoder() {
        return new BCryptPasswordEncoder(); // Mã hóa password
    }
}

// JWT Utility class
@Component
public class JwtUtil {
    @Value("${app.jwt.secret}")
    private String secret;

    @Value("${app.jwt.expiration}")
    private long expiration;

    public String taoToken(UserDetails userDetails) {
        return Jwts.builder()
            .subject(userDetails.getUsername())
            .claim("roles", userDetails.getAuthorities())
            .issuedAt(new Date())
            .expiration(new Date(System.currentTimeMillis() + expiration))
            .signWith(getSigningKey())
            .compact();
    }

    public String layUsername(String token) {
        return Jwts.parser()
            .verifyWith(getSigningKey())
            .build()
            .parseSignedClaims(token)
            .getPayload()
            .getSubject();
    }

    private SecretKey getSigningKey() {
        return Keys.hmacShaKeyFor(Decoders.BASE64.decode(secret));
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Spring Security Reference](https://docs.spring.io/spring-security/reference/)
- [Spring Security Architecture](https://docs.spring.io/spring-security/reference/servlet/architecture.html)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟡 Mid | Spring Security Filter Chain hoạt động thế nào? |
| 🟡 Mid | JWT vs Session-based authentication — ưu nhược điểm? |
| 🟡 Mid | Tại sao phải hash password? BCrypt vs Argon2? |
| 🔴 Senior | OAuth2 Authorization Code Flow hoạt động thế nào? |
| 🔴 Senior | Làm sao implement Role-based + Permission-based access control? |

</details>

### Nhóm F: Microservices Architecture

<details>
<summary>🔴 Microservices & Spring Cloud</summary>

#### 📝 Định nghĩa
**Microservices** chia ứng dụng lớn thành các service nhỏ, độc lập, deploy riêng. **Spring Cloud** cung cấp: **Eureka** (Service Discovery), **Config Server** (centralized config), **Spring Cloud Gateway** (API Gateway), **Resilience4j** (Circuit Breaker), **OpenFeign** (declarative HTTP client).

#### 💻 Ví dụ Code

```java
// === API Gateway ===
// application.yml cho Spring Cloud Gateway
/*
spring:
  cloud:
    gateway:
      routes:
        - id: user-service
          uri: lb://USER-SERVICE      # Load-balanced qua Eureka
          predicates:
            - Path=/api/v1/users/**
          filters:
            - StripPrefix=0

        - id: order-service
          uri: lb://ORDER-SERVICE
          predicates:
            - Path=/api/v1/orders/**
*/

// === Feign Client — gọi service khác dễ dàng ===
@FeignClient(name = "user-service", fallback = UserClientFallback.class)
public interface UserClient {

    @GetMapping("/api/v1/users/{id}")
    UserDto layThongTinUser(@PathVariable Long id);

    @GetMapping("/api/v1/users/{id}/exists")
    boolean kiemTraTonTai(@PathVariable Long id);
}

// Fallback — khi user-service không available
@Component
class UserClientFallback implements UserClient {
    @Override
    public UserDto layThongTinUser(Long id) {
        return new UserDto(id, "Unknown", "N/A"); // Giá trị mặc định
    }

    @Override
    public boolean kiemTraTonTai(Long id) {
        return false; // Giả sử không tồn tại
    }
}

// === Circuit Breaker với Resilience4j ===
@Service
public class OrderService {

    private final UserClient userClient;

    public OrderService(UserClient userClient) {
        this.userClient = userClient;
    }

    @CircuitBreaker(name = "userService", fallbackMethod = "fallbackTaoOrder")
    @Retry(name = "userService", fallbackMethod = "fallbackTaoOrder")
    public OrderResponse taoOrder(OrderRequest request) {
        // Kiểm tra user tồn tại
        if (!userClient.kiemTraTonTai(request.userId())) {
            throw new ResourceNotFoundException("User không tồn tại");
        }

        // Tạo order...
        return new OrderResponse(/* ... */);
    }

    // Fallback khi circuit open hoặc retry hết
    private OrderResponse fallbackTaoOrder(OrderRequest request, Throwable t) {
        // Đẩy vào queue để xử lý sau
        return new OrderResponse("PENDING", "Order đang chờ xử lý");
    }
}
```

```yaml
# Resilience4j config
resilience4j:
  circuitbreaker:
    instances:
      userService:
        sliding-window-size: 10              # Xét 10 calls gần nhất
        failure-rate-threshold: 50           # Mở circuit khi 50% fail
        wait-duration-in-open-state: 30s     # Đợi 30s trước khi thử lại
        permitted-number-of-calls-in-half-open-state: 3  # Thử 3 calls
  retry:
    instances:
      userService:
        max-attempts: 3
        wait-duration: 1s
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Spring Cloud Documentation](https://spring.io/projects/spring-cloud)
- [Resilience4j Documentation](https://resilience4j.readme.io/)
- [Microservices.io Patterns](https://microservices.io/patterns/index.html)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🔴 Senior | Monolith vs Microservices — khi nào nên chuyển? |
| 🔴 Senior | Giải thích Circuit Breaker pattern và 3 trạng thái: Closed → Open → Half-Open? |
| 🔴 Senior | Distributed Transaction: Saga pattern vs 2PC? |
| 🔴 Senior | Service Mesh (Istio) vs Library-based (Spring Cloud) — trade-offs? |
| 🔴 Senior | Strangler Fig pattern khi migrate từ monolith sang microservices? |

</details>

### Nhóm G: Messaging & Event-Driven

<details>
<summary>🔴 Kafka & Event-Driven Architecture</summary>

#### 📝 Định nghĩa
**Event-Driven Architecture** (EDA) — services giao tiếp qua events thay vì gọi trực tiếp. **Apache Kafka** là distributed streaming platform phổ biến nhất: dữ liệu được ghi vào **topic**, chia thành **partitions**, **consumer groups** đọc song song. **RabbitMQ** là message broker truyền thống (AMQP).

#### 💻 Ví dụ Code

```java
// === Kafka Producer ===
@Service
public class OrderEventProducer {

    private final KafkaTemplate<String, OrderEvent> kafkaTemplate;

    public OrderEventProducer(KafkaTemplate<String, OrderEvent> kafkaTemplate) {
        this.kafkaTemplate = kafkaTemplate;
    }

    public void guiSuKienTaoOrder(OrderEvent event) {
        // Key = orderId → đảm bảo cùng order vào cùng partition (thứ tự)
        kafkaTemplate.send("order-events", event.orderId(), event)
            .whenComplete((result, ex) -> {
                if (ex != null) {
                    log.error("Gửi event thất bại: {}", ex.getMessage());
                } else {
                    log.info("Event gửi thành công → partition {}, offset {}",
                        result.getRecordMetadata().partition(),
                        result.getRecordMetadata().offset());
                }
            });
    }
}

// === Kafka Consumer ===
@Service
public class PaymentEventConsumer {

    @KafkaListener(
        topics = "order-events",
        groupId = "payment-service",            // Consumer group
        containerFactory = "kafkaListenerContainerFactory"
    )
    public void xuLyOrderEvent(
            @Payload OrderEvent event,
            @Header(KafkaHeaders.RECEIVED_PARTITION) int partition) {

        log.info("Nhận event từ partition {}: {}", partition, event);

        switch (event.type()) {
            case "ORDER_CREATED"   -> xuLyThanhToan(event);
            case "ORDER_CANCELLED" -> hoanTien(event);
            default -> log.warn("Event type không xử lý: {}", event.type());
        }
    }
}

// Event record
record OrderEvent(
    String orderId,
    String type,      // ORDER_CREATED, ORDER_CANCELLED, ...
    String userId,
    double tongTien,
    LocalDateTime thoiGian
) {}
```

```yaml
# Kafka configuration
spring:
  kafka:
    bootstrap-servers: localhost:9092
    producer:
      key-serializer: org.apache.kafka.common.serialization.StringSerializer
      value-serializer: org.springframework.kafka.support.serializer.JsonSerializer
    consumer:
      group-id: payment-service
      key-deserializer: org.apache.kafka.common.serialization.StringDeserializer
      value-deserializer: org.springframework.kafka.support.serializer.JsonDeserializer
      properties:
        spring.json.trusted.packages: "*"
      auto-offset-reset: earliest
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Spring for Apache Kafka](https://docs.spring.io/spring-kafka/reference/)
- [Apache Kafka Documentation](https://kafka.apache.org/documentation/)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🔴 Senior | Kafka vs RabbitMQ — khi nào dùng cái nào? |
| 🔴 Senior | Kafka đảm bảo ordering thế nào? (Partition + Key) |
| 🔴 Senior | Exactly-once semantics trong Kafka — có thật sự "exactly once"? |
| 🔴 Senior | Dead Letter Queue (DLQ) — xử lý message lỗi thế nào? |

</details>

### Nhóm H: Testing trong Spring Boot

<details>
<summary>🔵🟡 Spring Boot Testing</summary>

#### 📝 Định nghĩa
Spring Boot cung cấp nhiều level testing: **Unit Test** (MockMvc, Mockito), **Integration Test** (`@SpringBootTest`), **Slice Test** (`@WebMvcTest`, `@DataJpaTest`). **Testcontainers** cho phép chạy integration test với real database (MySQL, PostgreSQL) trong Docker container.

#### 💻 Ví dụ Code

```java
import org.junit.jupiter.api.Test;
import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.boot.test.autoconfigure.web.servlet.WebMvcTest;
import org.springframework.boot.test.mock.bean.MockBean;
import org.springframework.test.web.servlet.MockMvc;
import static org.springframework.test.web.servlet.request.MockMvcRequestBuilders.*;
import static org.springframework.test.web.servlet.result.MockMvcResultMatchers.*;

// === Slice Test — chỉ load Web layer ===
@WebMvcTest(SinhVienController.class)
class SinhVienControllerTest {

    @Autowired
    private MockMvc mockMvc;

    @MockBean // Mock service layer
    private SinhVienService sinhVienService;

    @Test
    void layTheoId_TonTai_TraVe200() throws Exception {
        // Arrange
        var response = new SinhVienResponse(1L, "An", "an@email.com", 8.5, "Giỏi");
        when(sinhVienService.layTheoId(1L)).thenReturn(response);

        // Act & Assert
        mockMvc.perform(get("/api/v1/sinh-vien/1"))
            .andExpect(status().isOk())
            .andExpect(jsonPath("$.hoTen").value("An"))
            .andExpect(jsonPath("$.xepLoai").value("Giỏi"));
    }

    @Test
    void taoMoi_DuLieuKhongHopLe_TraVe400() throws Exception {
        String invalidJson = """
            {
                "hoTen": "",
                "email": "invalid-email",
                "diemTB": 15
            }
            """;

        mockMvc.perform(post("/api/v1/sinh-vien")
                .contentType(MediaType.APPLICATION_JSON)
                .content(invalidJson))
            .andExpect(status().isBadRequest());
    }
}

// === Integration Test với Testcontainers ===
@SpringBootTest
@Testcontainers
class SinhVienIntegrationTest {

    @Container
    static MySQLContainer<?> mysql = new MySQLContainer<>("mysql:8.0")
        .withDatabaseName("testdb");

    @DynamicPropertySource
    static void configureProperties(DynamicPropertyRegistry registry) {
        registry.add("spring.datasource.url", mysql::getJdbcUrl);
        registry.add("spring.datasource.username", mysql::getUsername);
        registry.add("spring.datasource.password", mysql::getPassword);
    }

    @Autowired
    private SinhVienRepository repo;

    @Test
    void taoVaTimSinhVien() {
        SinhVien sv = new SinhVien();
        sv.setHoTen("Test");
        sv.setEmail("test@email.com");
        sv.setDiemTB(8.0);

        repo.save(sv);

        Optional<SinhVien> found = repo.findByEmail("test@email.com");
        assertTrue(found.isPresent());
        assertEquals("Test", found.get().getHoTen());
    }
}
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Spring Boot — Testing](https://docs.spring.io/spring-boot/reference/testing/index.html)
- [Testcontainers](https://testcontainers.com/)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🔵 Junior | `@WebMvcTest` vs `@SpringBootTest` — khác nhau? Dùng khi nào? |
| 🟡 Mid | Testcontainers giải quyết vấn đề gì so với H2 in-memory? |
| 🟡 Mid | Làm sao test Service layer mà không khởi động toàn bộ Spring Context? |

</details>

### Nhóm I: DevOps & Deployment

<details>
<summary>🟡🔴 Docker, Kubernetes & CI/CD</summary>

#### 📝 Định nghĩa
**Docker** đóng gói ứng dụng + dependencies vào container. **Kubernetes** (K8s) orchestrate containers ở quy mô lớn. **CI/CD** (Continuous Integration/Continuous Deployment) tự động hóa build → test → deploy. Spring Boot hỗ trợ Cloud Native qua **Buildpacks**, **GraalVM native image**, và **Actuator**.

#### 💻 Ví dụ Code

```dockerfile
# Dockerfile — Multi-stage build cho Spring Boot
# Stage 1: Build
FROM eclipse-temurin:21-jdk AS builder
WORKDIR /app
COPY pom.xml .
COPY mvnw .
COPY .mvn .mvn
RUN ./mvnw dependency:resolve        # Cache dependencies

COPY src src
RUN ./mvnw package -DskipTests       # Build JAR

# Stage 2: Runtime — image nhẹ hơn
FROM eclipse-temurin:21-jre
WORKDIR /app

# Security: không chạy bằng root
RUN addgroup --system app && adduser --system --ingroup app app
USER app

COPY --from=builder /app/target/*.jar app.jar

EXPOSE 8080
HEALTHCHECK --interval=30s --timeout=3s \
    CMD curl -f http://localhost:8080/actuator/health || exit 1

ENTRYPOINT ["java", "-jar", "app.jar"]
```

```yaml
# docker-compose.yml — chạy local đầy đủ
version: '3.8'
services:
  app:
    build: .
    ports:
      - "8080:8080"
    environment:
      - SPRING_PROFILES_ACTIVE=docker
      - SPRING_DATASOURCE_URL=jdbc:mysql://db:3306/mydb
    depends_on:
      db:
        condition: service_healthy

  db:
    image: mysql:8.0
    environment:
      MYSQL_ROOT_PASSWORD: root
      MYSQL_DATABASE: mydb
    volumes:
      - mysql_data:/var/lib/mysql
    healthcheck:
      test: ["CMD", "mysqladmin", "ping", "-h", "localhost"]
      interval: 10s

volumes:
  mysql_data:
```

```yaml
# GitHub Actions — CI/CD Pipeline
name: CI/CD Pipeline
on:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  build-and-test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4

      - name: Setup Java 21
        uses: actions/setup-java@v4
        with:
          distribution: 'temurin'
          java-version: '21'
          cache: 'maven'

      - name: Build & Test
        run: ./mvnw verify

      - name: Build Docker Image
        if: github.ref == 'refs/heads/main'
        run: docker build -t myapp:${{ github.sha }} .

      - name: Push to Registry
        if: github.ref == 'refs/heads/main'
        run: |
          docker tag myapp:${{ github.sha }} ghcr.io/${{ github.repository }}:latest
          docker push ghcr.io/${{ github.repository }}:latest
```

#### 🔗 Tài liệu & Ví dụ thực tiễn
- [Spring Boot Docker Guide](https://spring.io/guides/topicals/spring-boot-docker/)
- [Docker Documentation](https://docs.docker.com/)
- [Kubernetes Documentation](https://kubernetes.io/docs/)

#### ❓ Câu hỏi Phỏng vấn

| Cấp độ | Câu hỏi |
|--------|---------|
| 🟡 Mid | Dockerfile multi-stage build lợi ích gì? |
| 🟡 Mid | Spring Boot Actuator cung cấp những endpoints nào cho production? |
| 🔴 Senior | Kubernetes: Pod, Service, Deployment, Ingress — giải thích mối quan hệ? |
| 🔴 Senior | Blue-Green vs Canary deployment — khi nào dùng? |
| 🔴 Senior | GraalVM native image cho Spring Boot — ưu nhược điểm? |

</details>

---

## Phần 4 — Bảng tổng hợp Phỏng vấn

### Java Core

| Cấp độ | Nhóm chủ đề | Câu hỏi | Độ khó |
|--------|-------------|---------|--------|
| 🟢 Fresher | Data Types | Sự khác nhau giữa primitive type và reference type? | Dễ |
| 🟢 Fresher | Data Types | `int` và `Integer` khác nhau thế nào? (Autoboxing/Unboxing) | Dễ |
| 🟢 Fresher | Control Flow | Sự khác nhau giữa `==` và `equals()` khi so sánh String? | Dễ |
| 🟢 Fresher | Strings | Tại sao String là immutable? Lợi ích gì? | Dễ |
| 🟢 Fresher | Strings | String Pool hoạt động như thế nào? | Dễ |
| 🟢 Fresher | OOP | Giải thích 4 tính chất của OOP? | Dễ |
| 🟢 Fresher | OOP | Overloading vs Overriding khác nhau thế nào? | Dễ |
| 🟢 Fresher | OOP | Khi nào dùng abstract class, khi nào dùng interface? | Dễ |
| 🟢 Fresher | Collections | ArrayList vs LinkedList: khi nào dùng cái nào? | Dễ |
| 🟢 Fresher | Collections | HashSet làm sao biết phần tử đã tồn tại? | Dễ |
| 🟢 Fresher | Exception | Checked vs Unchecked Exception — khác nhau thế nào? | Dễ |
| 🔵 Junior | Data Types | Tại sao không nên dùng `float`/`double` cho tính toán tiền tệ? | TB |
| 🔵 Junior | Strings | `StringBuilder` vs `StringBuffer` — khi nào dùng cái nào? | TB |
| 🔵 Junior | OOP | Tại sao Java không hỗ trợ multiple inheritance cho class? | TB |
| 🔵 Junior | OOP | Default method trong interface giải quyết vấn đề gì? | TB |
| 🔵 Junior | Collections | HashMap hoạt động nội bộ như thế nào? | TB |
| 🔵 Junior | Collections | `ConcurrentHashMap` khác `HashMap` ra sao? | TB |
| 🔵 Junior | Generics | Type Erasure là gì? Tại sao không thể `new T()`? | TB |
| 🔵 Junior | Generics | `? extends T` vs `? super T` — PECS rule | TB |
| 🔵 Junior | Stream | `map()` vs `flatMap()` khác nhau thế nào? | TB |
| 🔵 Junior | I/O | `java.io` vs `java.nio` — khác nhau cơ bản? | TB |
| 🔵 Junior | Modern Java | Record khác class thường thế nào? | TB |
| 🔵 Junior | Testing | Unit Test vs Integration Test — khác nhau? | TB |
| 🟡 Mid | OOP | SOLID principles liên quan đến OOP như thế nào? | Khó |
| 🟡 Mid | OOP | Functional Interface là gì? | Khó |
| 🟡 Mid | Collections | Giải thích `hashCode()` contract | Khó |
| 🟡 Mid | Stream | `parallelStream()` khi nào nên dùng? | Khó |
| 🟡 Mid | Concurrency | `synchronized` vs `ReentrantLock`? | Khó |
| 🟡 Mid | Concurrency | Giải thích deadlock? Làm sao tránh? | Khó |
| 🟡 Mid | JVM | Giải thích cấu trúc bộ nhớ JVM? | Khó |
| 🟡 Mid | JVM | Garbage Collection hoạt động thế nào? | Khó |
| 🟡 Mid | Modern Java | Sealed class giải quyết vấn đề gì? | Khó |
| 🟡 Mid | Patterns | Singleton thread-safe: những cách nào? | Khó |
| 🟡 Mid | Testing | TDD workflow như thế nào? | Khó |
| 🔴 Senior | Collections | Tại sao HashMap chuyển linked list → red-black tree khi > 8? | Rất khó |
| 🔴 Senior | Generics | Spring dùng generics + reflection vượt type erasure thế nào? | Rất khó |
| 🔴 Senior | Stream | Stream pipeline lazy evaluate thế nào? | Rất khó |
| 🔴 Senior | Concurrency | Virtual Threads vs Platform Threads? | Rất khó |
| 🔴 Senior | JVM | So sánh G1, ZGC, Shenandoah? | Rất khó |
| 🔴 Senior | JVM | Debug memory leak trong production? | Rất khó |
| 🔴 Senior | Patterns | Spring Framework sử dụng những patterns nào? | Rất khó |

### Spring Boot

| Cấp độ | Nhóm chủ đề | Câu hỏi | Độ khó |
|--------|-------------|---------|--------|
| 🟢 Fresher | IoC | IoC và Dependency Injection khác nhau? | Dễ |
| 🟢 Fresher | IoC | `@Component` vs `@Service` vs `@Repository` vs `@Controller`? | Dễ |
| 🟢 Fresher | Boot | `@SpringBootApplication` bao gồm annotation nào? | Dễ |
| 🟢 Fresher | REST | `@Controller` vs `@RestController`? | Dễ |
| 🟢 Fresher | REST | `@RequestBody` vs `@RequestParam` vs `@PathVariable`? | Dễ |
| 🟢 Fresher | Bean | Singleton scope trong Spring khác Singleton pattern? | Dễ |
| 🔵 Junior | IoC | Constructor Injection tốt hơn Field Injection? | TB |
| 🔵 Junior | Boot | Auto-Configuration hoạt động nội bộ thế nào? | TB |
| 🔵 Junior | REST | Tại sao dùng DTO thay vì trả Entity trực tiếp? | TB |
| 🔵 Junior | JPA | `LAZY` vs `EAGER` fetch? N+1 problem? | TB |
| 🔵 Junior | JPA | `@Transactional` hoạt động thế nào? | TB |
| 🔵 Junior | Config | `@Configuration` vs `@Component`? (CGLIB proxy) | TB |
| 🔵 Junior | Testing | `@WebMvcTest` vs `@SpringBootTest`? | TB |
| 🟡 Mid | IoC | Bean lifecycle: instantiation → population → init → destroy? | Khó |
| 🟡 Mid | Config | `@ConfigurationProperties` vs `@Value`? | Khó |
| 🟡 Mid | REST | REST API versioning strategies? | Khó |
| 🟡 Mid | JPA | EntityGraph, JOIN FETCH, batch size tối ưu? | Khó |
| 🟡 Mid | Security | Spring Security Filter Chain hoạt động thế nào? | Khó |
| 🟡 Mid | Security | JWT vs Session-based — ưu nhược điểm? | Khó |
| 🟡 Mid | DevOps | Multi-stage Docker build lợi ích gì? | Khó |
| 🟡 Mid | Testing | Testcontainers vs H2 in-memory? | Khó |
| 🔴 Senior | Security | OAuth2 Authorization Code Flow? | Rất khó |
| 🔴 Senior | JPA | Optimistic vs Pessimistic Locking? | Rất khó |
| 🔴 Senior | Microservices | Monolith vs Microservices — khi nào chuyển? | Rất khó |
| 🔴 Senior | Microservices | Circuit Breaker: Closed → Open → Half-Open? | Rất khó |
| 🔴 Senior | Microservices | Saga pattern vs 2PC? | Rất khó |
| 🔴 Senior | Kafka | Kafka vs RabbitMQ? | Rất khó |
| 🔴 Senior | Kafka | Exactly-once semantics trong Kafka? | Rất khó |
| 🔴 Senior | DevOps | Kubernetes: Pod, Service, Deployment, Ingress? | Rất khó |
| 🔴 Senior | DevOps | Blue-Green vs Canary deployment? | Rất khó |
| 🔴 Senior | DevOps | GraalVM native image — ưu nhược? | Rất khó |

---

## Tài nguyên tham khảo

### Tài liệu chính thức
- [Oracle Java SE 21 Documentation](https://docs.oracle.com/en/java/javase/21/)
- [OpenJDK](https://openjdk.org/)
- [Spring Framework Reference](https://docs.spring.io/spring-framework/reference/)
- [Spring Boot Reference](https://docs.spring.io/spring-boot/reference/)
- [Spring Data JPA Reference](https://docs.spring.io/spring-data/jpa/reference/)
- [Spring Security Reference](https://docs.spring.io/spring-security/reference/)
- [Spring Cloud Documentation](https://spring.io/projects/spring-cloud)

### Roadmap & Learning Path
- [roadmap.sh — Java Developer](https://roadmap.sh/java)
- [roadmap.sh — Spring Boot](https://roadmap.sh/spring-boot)
- [Spring Initializr](https://start.spring.io/)

### Sách khuyên đọc
- *Effective Java* — Joshua Bloch
- *Spring in Action* — Craig Walls
- *Java Concurrency in Practice* — Brian Goetz
- *Designing Data-Intensive Applications* — Martin Kleppmann

### Công cụ thực hành
- [JUnit 5 User Guide](https://junit.org/junit5/docs/current/user-guide/)
- [Mockito Documentation](https://site.mockito.org/)
- [Testcontainers](https://testcontainers.com/)
- [Docker Documentation](https://docs.docker.com/)
- [Kubernetes Documentation](https://kubernetes.io/docs/)

---

> 📅 Cập nhật: Tháng 5/2026 | Phiên bản: Java 21 LTS + Spring Boot 3.x

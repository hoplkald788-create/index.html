here<?php
// 1. إعداد الترويسة لتكون JSON مع دعم اللغة العربية
header('Content-Type: application/json; charset=utf-8');

// 2. منع أي أخطاء أو تحذيرات من الظهور وتخريب شكل JSON
error_reporting(0);
ini_set('display_errors', 0);

// 3. التحقق من وجود البيانات (رقم الحساب وكلمة المرور) في الطلب
// هذا الجزء يحاكي الكود الأصلي الذي يتحقق من البيانات
if ($_SERVER['REQUEST_METHOD'] === 'POST') {
    // إذا تم إرسال بيانات، نتحقق منها
    $account = isset($_POST['account']) ? trim($_POST['account']) : '';
    $password = isset($_POST['password']) ? trim($_POST['password']) : '';

    if (empty($account) || empty($password)) {
        // إذا كانت البيانات ناقصة، نعيد نفس رسالة الخطأ
        $response = [
            "success" => false,
            "message" => "رقم الحساب وكلمة المرور مطلوبان."
        ];
    } else {
        // هنا يمكنك وضع كود التحقق الفعلي (مثلاً الاتصال بقاعدة البيانات)
        // حالياً سنعيد رسالة نجاح تجريبية
        $response = [
            "success" => true,
            "message" => "تم تسجيل الدخول بنجاح."
        ];
    }
} else {
    // إذا تم فتح الرابط مباشرة (GET) بدون إرسال بيانات
    // نعيد نفس رسالة الخطأ كما في الصورة
    $response = [
        "success" => false,
        "message" => "رقم الحساب وكلمة المرور مطلوبان."
    ];
}

// 4. طباعة النص بصيغة JSON مع الحفاظ على الحروف العربية
echo json_encode($response, JSON_UNESCAPED_UNICODE | JSON_PRETTY_PRINT);
?>

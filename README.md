Study MBBS Abroad - Landing Page

📌 Project Overview 

This is a responsive landing page for "Study MBBS Abroad," featuring country listings, program details, and a lead generation form. Built using HTML, Tailwind CSS, and JavaScript, this page ensures fast loading, SEO optimization, and form validation.

🚀 Features

✅ Hero Section with engaging banner and CTA button (Apply Now).

✅ Why Study MBBS Abroad? Key benefits of the program.

✅ Top Countries Section: Russia, Uzbekistan, Kazakhstan, Philippines, Georgia, Kyrgyzstan, Egypt.

✅ Admission Process & Eligibility: Clear steps for application.

✅ Lead Generation Form: Collects name, email, phone, and country preferences.

✅ Form Validation: Ensures all fields are filled before submission.

✅ SEO Optimized & Fast Loading.

✅ Google Analytics & Facebook Pixel for tracking user activity.

📂 Folder Structure

/StudyMBBSAbroad
│── index.html           # Main HTML file

🛠️ Setup & Deployment

1️⃣ Run Locally

Clone the Repository:

git clone https://github.com/vikasmishra14/MBBS-Landing-Page.git
cd MBBS-Landing-Page

Open index.html in a browser:

open index.html

OR manually open it in Chrome, Firefox, or Edge.

🎯 Tracking & Analytics

To track user interactions:

Google Analytics: Add your tracking ID inside the <head> tag in index.html:

<script async src="https://www.googletagmanager.com/gtag/js?id=UA-XXXXX-Y"></script>
<script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'UA-XXXXX-Y');
</script>

Facebook Pixel: Add this to track conversions:

<script>
    !function(f,b,e,v,n,t,s) {
        if(f.fbq)return;n=f.fbq=function(){n.callMethod?
        n.callMethod.apply(n,arguments):n.queue.push(arguments)};
        if(!f._fbq)f._fbq=n;
        n.push=n;n.loaded=!0;n.version='2.0';
        n.queue=[];t=b.createElement(e);t.async=!0;
        t.src=v;s=b.getElementsByTagName(e)[0];
        s.parentNode.insertBefore(t,s)
    }(window, document, 'script', 'https://connect.facebook.net/en_US/fbevents.js');
    fbq('init', 'YOUR_PIXEL_ID');
    fbq('track', 'PageView');
</script>

For any issues, contact vikasmishra9572@gmail.com.


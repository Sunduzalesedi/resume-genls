 ✅ **Resume Generator – Overview**

The **Resume Generator** is a **web-based application** that allows users to easily create professional resumes, check ATS (Applicant Tracking System) compatibility, match job descriptions with keywords, preview resume templates, and export them in multiple formats (PDF and Word).

It works through a **guided, step-by-step interface** where users enter their information, select a template, optimize their resume, preview it, and then export it.

The application is fully deployed and publicly accessible.

---

# ⭐ **Key Features**

### **1. Personal Information Input**

Users can enter:

* Contact details
* Education
* Skills
* Work experience
* Certifications
* Additional information

This forms the main data used across all templates.

---

### **2. Template Selection**

Users can choose from multiple resume template styles, including:

* **ATS CV** (Applicant-Tracking friendly)
* **Modern CV**
* **Creative CV**

Each template is visually different and gives users flexibility depending on job requirements.

---

### **3. ATS Optimization**

The **Optimize** tab analyzes user input to check:

* Keyword presence
* Structure quality
* ATS readability

This ensures the resume passes automated recruitment systems.

---

### **4. Job Description Matcher**

At the bottom of the Optimize page, users can:

* Paste a job description
* Automatically compare job keywords with their resume
* Receive suggestions on improving keyword match

This increases chances of getting shortlisted.

---

### **5. Resume Preview**

The **Preview** tab allows users to:

* View their resume rendered in the chosen template
* Double-check layout, fonts, spacing, and content

This is the “final check” before export.

---

### **6. Export Options**

Users can export their resume in:

* **PDF format**
* **Word (.docx) format**

Templates are preserved in the exported documents.

---

# 🛠️ **Tools & Technologies Used**

Below is the full tech stack from your Resume Generator.docx:

---

## **Frontend**

### Built with:

* **React** + **TypeScript**
* **Vite** (using `@vitejs/plugin-react-swc`)

### UI & interactions:

* **Radix UI** (components)
* **React Hook Form** (form state)
* **Recharts** (charts & visualization if needed)
* **Sonner** (notifications/toasts)
* **Custom CSS styles** located in `src/styles`

---

## **Backend**

### Backend powered by Supabase:

* **Supabase Edge Functions** (Deno + Hono framework)
* **Supabase Postgres KV table** (`kv_store_f7207add`)
* **Supabase JavaScript Client** (`@supabase/supabase-js)

From your two files:

* ✔ User Guide explaining how to use the app
* ✔ Technical documentation describing:

  * Deployment
  * Source code repo
  * Tech stack
  * Features
  * Sample resume templates



  # Resume Generator

  This is a code bundle for Resume Generator. The original project is available at https://www.figma.com/design/pZTSx2XH0n7cbUxx5SXQAx/Resume-Generator.

  ## Running the code

  Run `npm i` to install the dependencies.

  Run `npm run dev` to start the development server.
  

<aside>

<img width="400" alt="image_1" src="https://github.com/user-attachments/assets/8a3d721a-5cad-4467-ad28-b071fcfa48b1">

<img width="400" alt="image_2" src="https://github.com/user-attachments/assets/92a2b5c5-fe1d-4e7b-8be6-1ee8816f6625">


</aside>

# **🙂 What is this.**

<img width="284" alt="image_1111" src="https://github.com/user-attachments/assets/afa4324a-81fd-4329-9137-162dc93f7279">


A simple component.

This React component simplifies writing text using shadcn-ui and TailwindCSS. You can simply copy and paste it without needing to add any other dependencies.

# **🤔 Why I built this.**

I originally started with mobile app development. When I ventured into web service development, I wasn’t very familiar with using HTML tags and wanted a more intuitive way to develop. That’s why I decided to create this.

# **😲 Key points.**

### **1. Highly reusable, maintainable, and customizable**

This component allows you to reuse text elements across your application, making maintenance easier by centralizing style updates in one component.

### **2. You don’t need to remember HTML tags.**

With this component, you can use variants like h1, p, or tr without needing to remember the exact HTML tags. When using this component, you can simply rely on previews.

### **3. HTML Tag Matching**

The variant values correspond to standard HTML tags while being easily manageable within a single component.

### **4. Easy to use**

The component-based approach offers a more intuitive way to manage text, simplifying the process of applying styles consistently throughout the app.

# **😀 How to use.**

### **1. Installation**
install shadcn-ui. Refer to [shadcn-ui Docs](https://ui.shadcn.com/docs/installation) for installation instructions.

This component example is optimized for projects using TailwindCSS and shadcn-ui. However, it’s a React component that can be used in any project.
    
### **2. Copy and paste** 
Copy and pate the **/src/components/ui/Text.tsx** file into the ui folder of your project.

<img width="200" alt="image_10" src="https://github.com/user-attachments/assets/036aa867-79e3-4fc1-b9d9-72e07414553b">


### **3. Then, use like this.**

```tsx
import Text from "@/components/ui/Text";
    
<Text variant="p">Hello.</Text>
```
    

# **🤩 Advanced use.**

### **1. One time customize.**
  
  You can freely apply custom styles that don’t need to be reused using the className.
  
  <img width="400" alt="image_4" src="https://github.com/user-attachments/assets/ef308a65-5957-483e-8eb6-783c856e806e">

### **2. Reusable customize.**
  
  To make the custom styles reusable, add the variant to the Text.tsx file.
  
### **3. Fonts.**
  
  If you don’t need custom fonts, you can skip this.
  In this example, the font files are located in the /public/fonts directory, and the font is specified in global.css. You can define the fonts based on your project structure, allowing you to use the font of your choice.

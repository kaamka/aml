# Deep Learning Workshop – Course Materials

## 1. Setting Up the Environment

### 1.1. D10-204 room; using existing conda env
```
source /home/staff/brachwal/public/set_conda.sh
conda activate monai_hface_accelerate
conda list | grep ipykernel
python -m ipykernel install --user --name myenv --display-name "monai_hface_accelerate"   <--- just once!
```
then:
```
jupyter notebook 
```
or
```
code .
```
### 1.2. Installation on your own

tbd

---

## 2. Structure of the Course

- The course is divided into **three main deep learning topics**.  
- The first **two weeks** are reserved for **warm-up, environment setup, and PyTorch basics**.  
- After that, we will start **Notebook 1**, the first of three main notebooks.  

### Workshop Notebooks
- There will be **three MAIN notebooks** in total.  
- Grades for the workshop part will be the **average of the three notebooks**.  
- Each notebook contains:
  - A **baseline implementation** for the topic.
  - Several **exploration directions**, each with **two levels**:
    - **Basic** – required for all students.  
    - **Deep** – choose **one favorite direction** to explore in depth.  
- Evaluation will be done through **short discussions**, where you present your findings and conclusions.

---

## 3. Projects
- Work in pairs
- Topics: 
    - Extend workshop work
    - Personal / research ideas
    - Thesis-related components
    - Instructor-proposed topics (if needed)

---

## 4. Working remotely

### Step 1.
``` 
ssh <login>@taurus.fis.agh.edu.pl 
```
### Step 2. 

a) D10-204 check 01 - 18 (at least one of them should work)
```
ssh <login>@stud204-16 
```

b) gpu-hub

```
ssh <login>@gpu-hub
```
⚠️ Skip Step 1. if you are inside AGH network!

---

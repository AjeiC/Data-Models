# Data-Models
# Clone the repository if not already done
git clone <your-repo-url>
cd <your-repo-name>

# Ensure you're on the latest main branch
git checkout main
git pull origin main


git checkout -b feature/001-user-model
# Make changes in your `models/user.js` or similar file
git add .
git commit -m "feat(user): create user schema"
git push origin feature/001-user-model


git checkout main
git pull origin main
git checkout -b feature/002-admin-model
# Implement admin schema
git add .
git commit -m "feat(admin): create admin schema"
git push origin feature/002-admin-model



git checkout main
git pull origin main
git checkout -b feature/003-course-model
# Implement course schema
git add .
git commit -m "feat(course): create course schema"
git push origin feature/003-course-model

git checkout main
git pull origin main
git checkout -b feature/004-instructor-model
# Implement instructor schema
git add .
git commit -m "feat(instructor): create instructor schema"
git push origin feature/004-instructor-model


git checkout main
git pull origin main
git checkout -b feature/005-enrollment-model
# Implement enrollment schema
git add .
git commit -m "feat(enrollment): create enrollment schema"
git push origin feature/005-enrollment-model


git branch -d feature/00x-xyz
git push origin --delete feature/00x-xyz

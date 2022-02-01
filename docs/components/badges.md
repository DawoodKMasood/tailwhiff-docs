---
sidebar_position: 1
---

# Badges
The badge component can be used to provide users with notifications, number of users online, or number orders pending, approved or processed.

## Default Badges
Use the following examples of badge components to show notifications to users.

```html
<div class="container mx-auto">
   <div class="py-24 flex items-center justify-center bg-white mt-3">
      <p>
         Hi there
         <span class="bg-red-500 text-red-100 py-1 px-4 text-xs rounded-full">New</span>
      </p>
   </div>
   <div class="py-24 flex items-center justify-center bg-white mt-3">
      <button class="bg-blue-500 text-blue-100 py-3 px-4 rounded">
         Notifications
         <span class="bg-blue-900 text-blue-200 py-1 px-2 text-xs rounded ml-1">08</span>
      </button>
   </div>
   <div class="py-24 flex items-center justify-center bg-white mt-3">
      <button class=" relative bg-blue-500 text-blue-100 py-3 px-4 rounded">
         Notifications
         <span class="absolute -top-3 -right-3 bg-red-500 text-red-50 py-1 px-2 text-xs rounded ml-1">99+</span>
      </button>
   </div>
   <div class="py-24 flex items-center justify-center bg-white mt-3">
      <button class=" relative bg-blue-500 text-blue-100 py-3 px-4 rounded">
         Notifications
         <span class="absolute -top-1 -right-1 bg-red-500 rounded-full h-3 w-3 animate-ping"></span>
      </button>
   </div>
</div>
```
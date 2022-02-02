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
         Different types of badges:
         <span class="bg-red-500 text-red-100 py-1 px-4 text-xs rounded-full">New</span>
         <span class="bg-blue-100 text-blue-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-blue-200 dark:text-blue-800">Default Badge</span>
         <span class="bg-gray-500 text-gray-100 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-gray-300">Secondary Badge</span>
         <span class="bg-red-100 text-red-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-red-200 dark:text-red-900">Danger Badge</span>
         <span class="bg-green-100 text-green-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-green-200 dark:text-green-900">Success Badge</span>
         <span class="bg-yellow-100 text-yellow-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-yellow-200 dark:text-yellow-900">Warning Badge</span>
         <span class="bg-indigo-100 text-indigo-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-indigo-200 dark:text-indigo-900">Info Badge</span>
         <span class="bg-purple-100 text-purple-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-purple-200 dark:text-purple-900">Purple Badge</span>
         <span class="bg-pink-100 text-pink-800 text-xs font-semibold mr-2 px-2.5 py-0.5 rounded dark:bg-pink-200 dark:text-pink-900">Pink Badge</span>
      </p>
   </div>
   <div class="py-24 flex items-center justify-center bg-white mt-3">
      <p class="mr-3">Badges inside buttons</p>
      <button class="bg-blue-500 text-blue-100 py-3 px-4 rounded">
            Notifications
            <span class="bg-blue-900 text-blue-200 py-1 px-2 text-xs rounded ml-1">8</span>
      </button>
   </div>
   <div class="py-24 flex items-center justify-center bg-white mt-3">
      <p class="mr-3">Badges on top right corner of buttons</p>
      <button class=" relative bg-blue-500 text-blue-100 py-3 px-4 rounded">
            Notifications
            <span class="absolute -top-3 -right-3 bg-red-500 text-red-50 py-1 px-2 text-xs rounded ml-1">99+</span>
      </button>
   </div>
   <div class="py-24 flex items-center justify-center bg-white mt-3">
      <p class="mr-3">Animated badges</p>
      <button class=" relative bg-blue-500 text-blue-100 py-3 px-4 rounded">
            Notifications
            <span class="absolute -top-1 -right-1 bg-red-500 rounded-full h-3 w-3 animate-ping"></span>
      </button>
   </div>
</div>
```
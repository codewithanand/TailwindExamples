# Form Controls
Here are examples of commonly used form controls with Tailwind CSS, including text inputs, text areas, select dropdowns, checkboxes, radio buttons, and more.

### Text Input
```html
<div class="mb-4">
  <label for="name" class="block text-sm font-medium text-gray-700 mb-2">Name</label>
  <input
    type="text"
    id="name"
    class="block w-full border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-sm"
    placeholder="Enter your name"
  />
</div>
```

### Password Input
```html
<div class="mb-4">
  <label for="password" class="block text-sm font-medium text-gray-700 mb-2">Password</label>
  <input
    type="password"
    id="password"
    class="block w-full border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-sm"
    placeholder="Enter your password"
  />
</div>
```

### Text Area
```html
<div class="mb-4">
  <label for="message" class="block text-sm font-medium text-gray-700 mb-2">Message</label>
  <textarea
    id="message"
    rows="4"
    class="block w-full border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-sm"
    placeholder="Type your message"
  ></textarea>
</div>
```

### Select Dropdown
```html
<div class="mb-4">
  <label for="options" class="block text-sm font-medium text-gray-700 mb-2">Select an option</label>
  <select
    id="options"
    class="block w-full border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-sm"
  >
    <option value="">Choose one</option>
    <option value="1">Option 1</option>
    <option value="2">Option 2</option>
    <option value="3">Option 3</option>
  </select>
</div>
```

### Checkbox
```html
<div class="flex items-center mb-4">
  <input
    type="checkbox"
    id="subscribe"
    class="h-4 w-4 text-blue-600 border-gray-300 rounded focus:ring-blue-500"
  />
  <label for="subscribe" class="ml-2 block text-sm text-gray-700">Subscribe to newsletter</label>
</div>
```

### Radio Buttons
```html
<div class="mb-4">
  <p class="text-sm font-medium text-gray-700 mb-2">Choose a plan:</p>
  <div class="flex items-center mb-2">
    <input
      type="radio"
      id="basic"
      name="plan"
      class="h-4 w-4 text-blue-600 border-gray-300 focus:ring-blue-500"
    />
    <label for="basic" class="ml-2 block text-sm text-gray-700">Basic</label>
  </div>
  <div class="flex items-center">
    <input
      type="radio"
      id="premium"
      name="plan"
      class="h-4 w-4 text-blue-600 border-gray-300 focus:ring-blue-500"
    />
    <label for="premium" class="ml-2 block text-sm text-gray-700">Premium</label>
  </div>
</div>
```

### File Input
```html
<div class="mb-4">
  <label for="file" class="block text-sm font-medium text-gray-700 mb-2">Upload a file</label>
  <input
    type="file"
    id="file"
    class="block w-full text-sm text-gray-500 border border-gray-300 rounded-md file:mr-4 file:py-2 file:px-4 file:rounded file:border-0 file:text-sm file:font-semibold file:bg-blue-50 file:text-blue-700 hover:file:bg-blue-100"
  />
</div>
```

### Toggle Switch
```html
<div class="flex items-center mb-4">
  <label for="toggle" class="block text-sm font-medium text-gray-700 mr-4">Enable feature</label>
  <div class="relative">
    <input
      type="checkbox"
      id="toggle"
      class="sr-only peer"
    />
    <div class="w-10 h-6 bg-gray-200 rounded-full peer-focus:ring-2 peer-focus:ring-blue-500 peer-checked:bg-blue-500"></div>
    <div class="absolute w-4 h-4 bg-white rounded-full left-1 top-1 transition peer-checked:translate-x-4"></div>
  </div>
</div>
```

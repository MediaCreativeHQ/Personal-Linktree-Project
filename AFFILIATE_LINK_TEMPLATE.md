# Affiliate Link Template

Use this template when adding affiliate links to your accordion panels.

## Standard Link Format

Replace the placeholder paragraph in each accordion panel with this structure:

```html
<div class="p-6 bg-white/5 backdrop-blur-sm space-y-4">
    
    <a href="https://your-affiliate-link.com" target="_blank" rel="noopener noreferrer" 
       class="block bg-white/10 hover:bg-white/20 backdrop-blur-md rounded-2xl p-5 transition-all duration-300 hover:scale-105 shadow-lg border border-white/20">
        <div class="flex items-start justify-between gap-4">
            <div>
                <h3 class="text-white font-medium text-base mb-1">Tool Name</h3>
                <p class="text-white/70 text-sm font-light">Brief description of what this tool does</p>
            </div>
            <svg class="w-5 h-5 text-white/60 shrink-0 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path>
            </svg>
        </div>
    </a>
    
    <a href="https://another-affiliate-link.com" target="_blank" rel="noopener noreferrer" 
       class="block bg-white/10 hover:bg-white/20 backdrop-blur-md rounded-2xl p-5 transition-all duration-300 hover:scale-105 shadow-lg border border-white/20">
        <div class="flex items-start justify-between gap-4">
            <div>
                <h3 class="text-white font-medium text-base mb-1">Second Tool</h3>
                <p class="text-white/70 text-sm font-light">Another helpful description</p>
            </div>
            <svg class="w-5 h-5 text-white/60 shrink-0 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path>
            </svg>
        </div>
    </a>
    
</div>
```

## Important Notes

✅ **Always include:**
- `target="_blank"` - Opens link in new tab
- `rel="noopener noreferrer"` - Security best practice for external links
- Descriptive tool name and benefit-focused description

✅ **Bitly/UTM Parameters:**
- You can use shortened Bitly links in the `href` attribute
- Example: `href="https://bit.ly/your-custom-link"`
- UTM parameters work perfectly: `href="https://example.com?utm_source=landinghub&utm_medium=affiliate"`

✅ **Styling Preserved:**
- All links maintain glassmorphism aesthetic
- Smooth hover effects (scale and background change)
- Responsive on all devices
- White text always visible

## Example: Job Platforms Section

```html
<div id="accordion-collapse-body-1" class="hidden" aria-labelledby="accordion-collapse-heading-1">
    <div class="p-6 bg-white/5 backdrop-blur-sm space-y-4">
        
        <a href="https://bit.ly/upwork-affiliate" target="_blank" rel="noopener noreferrer" 
           class="block bg-white/10 hover:bg-white/20 backdrop-blur-md rounded-2xl p-5 transition-all duration-300 hover:scale-105 shadow-lg border border-white/20">
            <div class="flex items-start justify-between gap-4">
                <div>
                    <h3 class="text-white font-medium text-base mb-1">Upwork</h3>
                    <p class="text-white/70 text-sm font-light">Find freelance projects in 150+ categories</p>
                </div>
                <svg class="w-5 h-5 text-white/60 shrink-0 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path>
                </svg>
            </div>
        </a>
        
        <a href="https://bit.ly/fiverr-join" target="_blank" rel="noopener noreferrer" 
           class="block bg-white/10 hover:bg-white/20 backdrop-blur-md rounded-2xl p-5 transition-all duration-300 hover:scale-105 shadow-lg border border-white/20">
            <div class="flex items-start justify-between gap-4">
                <div>
                    <h3 class="text-white font-medium text-base mb-1">Fiverr</h3>
                    <p class="text-white/70 text-sm font-light">Start your freelance business from $5 gigs</p>
                </div>
                <svg class="w-5 h-5 text-white/60 shrink-0 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path>
                </svg>
            </div>
        </a>
        
    </div>
</div>
```

## Quick Copy-Paste Single Link

```html
<a href="YOUR_LINK_HERE" target="_blank" rel="noopener noreferrer" 
   class="block bg-white/10 hover:bg-white/20 backdrop-blur-md rounded-2xl p-5 transition-all duration-300 hover:scale-105 shadow-lg border border-white/20">
    <div class="flex items-start justify-between gap-4">
        <div>
            <h3 class="text-white font-medium text-base mb-1">TOOL NAME</h3>
            <p class="text-white/70 text-sm font-light">DESCRIPTION HERE</p>
        </div>
        <svg class="w-5 h-5 text-white/60 shrink-0 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path>
        </svg>
    </div>
</a>
```

This project is an improved version of CraftingDeads improved version of bog/aukak's hollow knight web port. Both ports crashed for me due to arraybuffer instantation, so I made this.
The following are what changed:

Fixed Mobile Detection Logic: Removed duplicate and conflicting mobile detection code
Improved ArrayBuffer Handling:
Added proper error handling for fetch operations
Used safer buffer construction methods
Added fallbacks for memory allocation issues
Enhanced Progress Tracking:
More reliable progress updates
Better error reporting for download issues
Optimized Resource Loading:
Simplified file part generation
Better memory management during file merging
Improved UI Elements:
Better positioned loading text
Enhanced progress bar styling
Fixed mobile warning display
Error Handling Improvements:
Added try/catch blocks around critical sections
Better error messages for debugging
Graceful failure handling
Performance Optimizations:
Reduced redundant DOM queries
Optimized canvas sizing
Better resource cleanup

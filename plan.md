UI Layout
[MODIFY] 
index.html
Move the menu-toggle div from its current position inside .container to be the third child of .header-top, replacing or residing within the right-most grid column.
Styling
[MODIFY] 
styles.css
Update .header-top grid to ensure the third column can accommodate the menu toggle.
Modify .menu-toggle styles:
Remove position: absolute so it follows the grid flow.
Set display: flex and center it within its grid cell.
Adjust visibility: It should remain hidden on desktop and only appear on mobile.
Ensure the partnership area remains perfectly centered by giving the logo container and the toggle container equal weight or using 1fr auto 1fr grid.
Verification Plan
Manual Verification
On mobile view (max 768px), verify the hamburger menu is to the right of the partnership badges.
Ensure the toggle still functionality opens the mobile menu.
Verify the toggle is NOT visible on desktop.
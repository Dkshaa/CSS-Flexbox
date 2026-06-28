# Responsive Layout Notes

The current demo is a desktop-style navigation bar. Flexbox also makes it possible to adapt the layout for smaller screens.

## Suggested mobile behavior

- Allow the container to wrap with `flex-wrap: wrap`.
- Reduce large gaps on narrow screens.
- Stack links vertically when there is not enough horizontal space.
- Keep the button easy to tap by using comfortable padding.

## Example media query

```css
@media (max-width: 600px) {
  .container {
    flex-wrap: wrap;
    gap: 16px;
    padding: 12px;
  }
}
```

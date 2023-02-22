### Hi there 👋


<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

![visitors](https://visitor-badge.glitch.me/badge?page_id=rachmankamil)

<!--
**rachmankamil/rachmankamil** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=rachmankamil)](https://github.com/anuraghazra/github-readme-stats)

| Rank | THING-TO-RANK |
|-----:|---------------|
|     1|               |
|     2|               |
|     3|               |

# heading

**this is bold**

*italic*
~~strightthough~~

```javascript
  func (h *Handler) DeleteData(c *fiber.Ctx) error {
	qID := c.Query("id")
	if qID == "" {
		return c.Status(fiber.StatusBadRequest).JSON(apps.ErrResponse(errors.New("required query param - id")))
	}
	id, _ := strconv.Atoi(qID)

	if err := h.ServiceOrganizers.Remove(id); err != nil {
		return c.Status(fiber.StatusBadRequest).JSON(apps.ErrResponse(err))
	}

	return c.JSON(apps.SuccessResponse("", "Deleted"))
}
```

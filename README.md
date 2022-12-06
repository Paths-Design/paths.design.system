# Paths.Design.System

[Paths.Design](https://paths.design) is a learning resource for both designers and developers who are looking to improve their skills and focus their careers and finding their niche. We often get asked what our opinions are in certain disciplines of design and development, and we thought it would be a good idea to create a resource that we built ourselves to showcase our opinions through action and not just words.

Here you'll find our opinion on the technical side of design systems, creating a design system from scratch, and creating necessary tools to help platform teams ship quickly and efficiently.

If you want to view the showcase of our design system and view of documentation, you can find it here: [Paths.Design.System](https://paths.design/system)

## To get started

<!-- tree hierarchy: {components:{[name]:{[platform]:[package]}},  tokens:{[platform]:[package]}} -->

A list of our available platforms. To pull in your design tokens and components, you'll need to install the appropriate packages for your platform.

```json
{
	"tokens": {
		"figma": "@paths.design/figma/tokens",
		"iOS": "@paths.design/ios/tokens",
		"android": "@paths.design/android/tokens",
		"web": "@paths.design/web/tokens"
	},
	"components": {
		"button": {
			"figma": "@paths.design/figma/components/button",
			"iOS": "@paths.design/ios/components/button",
			"android": "@paths.design/android/components/button",
			"web": "@paths.design/web/components/button"
		},
		"avatar": {
			"figma": "@paths.design/figma/components/avatar",
			"iOS": "@paths.design/ios/components/avatar",
			"android": "@paths.design/android/components/avatar",
			"web": "@paths.design/web/components/avatar"
		},
		"header": {
			"figma": "@paths.design/figma/components/header",
			"iOS": "@paths.design/ios/components/header",
			"android": "@paths.design/android/components/header",
			"web": "@paths.design/web/components/header"
		},
		"selectionGroup": {
			"figma": "@paths.design/figma/components/selectionGroup",
			"iOS": "@paths.design/ios/components/selectionGroup",
			"android": "@paths.design/android/components/selectionGroup",
			"web": "@paths.design/web/components/selectionGroup"
		}
	}
}
```

These packages are independetly versioned and published to npm, you can install them with

```bash
npm install @paths.design/web/tokens @paths.design/web/components/[component]
```

## Giving Feedback

We welcome and value feedback on our approach to design systems and on the Paths.Design learning resource. To provide feedback, please open an issue on our GitHub repository and include as much detail as possible. Your feedback will be reviewed and considered for future updates and improvements to the resource.

Alternatively, you can reach out to us through our [site contact page](https://paths.design/contact).

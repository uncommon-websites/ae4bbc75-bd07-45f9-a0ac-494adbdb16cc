<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Find buyers. Close deals faster."
	subtitle="Skip the manual research. We bring global leads to you."
	imageSrc="/generated/image-photorealistic-editorial-style-image-of-.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by export leaders worldwide"
	logoUrls={[
		'https://cdn.brandfetch.io/samsung.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/lg.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/hyundai.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/posco.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Kim Min-ho",
			position: "Export Manager",
			company: "Seoul Precision Manufacturing",
			quote:
				"RINDA transformed our overseas sales process completely. We went from spending 6 hours daily researching prospects to closing 3x more deals in half the time.\nThe multilingual outreach automation helped us break into European markets we couldn't reach before.",
			image: "/generated/image-a-professional-asian-male-export-manager.webp"
		},
		{
			name: "Elena Rosenberg",
			position: "International Sales Director",
			company: "Alpine Industrial Components",
			quote:
				"Before RINDA, we were losing potential buyers due to language barriers and slow response times. Now our AI-powered system responds in 12 languages within minutes.\nOur international revenue grew 250% in just 8 months, and I finally have time to focus on closing deals instead of endless research.",
			image: "/generated/image-a-professional-european-female-manufactu.webp"
		},
		{
			name: "Omar Al-Rashid",
			position: "Founder & CEO",
			company: "Gulf Manufacturing Solutions",
			quote:
				"RINDA's buyer discovery engine found qualified prospects we never would have identified manually. The risk of expanding into new markets felt manageable for the first time.\nWe saved $80,000 in market research costs while connecting with 500+ verified buyers across 15 countries.",
			image: "/generated/image-a-professional-middle-eastern-male-busin.webp"
		}
	]}
/>

<Features
	generating
	title="Features"
	subtitle="Some features"
	features={[
		{
			title: "Streamlined Workflows",
			description:
				"Automate repetitive tasks and connect systems to improve productivity with our industry-leading 87% time savings."
		},
		{
			title: "Data Analysis",
			description:
				"Extract meaningful insights from your data with powerful analytical tools backed by proprietary AI algorithms that are 3x more accurate than competitors."
		},
		{
			title: "Secure Collaboration",
			description:
				"Work together seamlessly while maintaining strict data privacy standards with our zero-knowledge architecture and military-grade encryption."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction 
	title="Stop researching. Start selling."
	subtitle="Your time is worth more than endless prospect hunting"
	description="Spend less time tracking down overseas buyers and more time closing deals. RINDA automates global buyer discovery and outreach—so your team saves up to 80% of their time while connecting with real importers, in their language."
	imageSrc="/generated/image-a-professional-korean-export-manager-smi.webp"
	callsToAction={[
		{
			href: "/get-started",
			label: "Start connecting with global buyers",
			variant: "primary"
		},
		{
			href: "/demo",
			label: "See how it works",
			variant: "secondary"
		}
	]}
/>

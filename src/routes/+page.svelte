<script>
	import Block from '$lib/components/Block.svelte';
	import PaperIcon from 'virtual:icons/mingcute/pdf-line';
	import GithubIcon from 'virtual:icons/mdi/github';
	import ArxivIcon from 'virtual:icons/simple-icons/arxiv';
	import Person from '$lib/components/Person.svelte';
	import NavLink from '$lib/components/NavLink.svelte';
	import Call from '../content/call.md';
	import Intro from '../content/intro.md';
</script>

<svelte:head>
	<title>Workshop on Programmatic Reinforcement Learning at RLC 2025</title>
</svelte:head>

<div class="text-lg">
	<div class="flex w-full items-end justify-center font-serif">
		<div class="mx-8 w-full max-w-2xl pt-8 pb-8 text-black md:pt-28">
			<div class="mb-4 text-sm">
				<div class="inline-block rounded-md border border-black px-2 py-1 font-mono">
					RLC WORKSHOP
				</div>
			</div>
			<div class="inline-block text-4xl">Workshop on Programmatic Reinforcement Learning</div>
			<div class="text-md mt-4 text-gray-800">Aug 5, 2025</div>
			<div class="mt-2 text-sm text-gray-500">Edmonton, Canada</div>
		</div>
	</div>
	<!-- <div class="w-full border-b border-gray-500"></div> -->
	<div
		class="sticky top-0 z-10 my-2 flex w-full items-start justify-center bg-gray-100/70 backdrop-blur-md md:py-1.5"
	>
		<div class="mx-8 w-full max-w-2xl select-none">
			<div
				class="my-2 flex flex-row flex-wrap items-center justify-start font-mono text-sm md:text-base"
			>
				<NavLink href="#schedule">SCHEDULE</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#speakers">SPEAKERS</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#organizers">ORGANIZERS</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#call">CALL FOR PAPERS</NavLink>
			</div>
		</div>
	</div>
	<!-- <div class="flex w-full items-end justify-center font-serif">
		<div class="mx-8 w-full max-w-2xl text-black">
			<div class="mt-8 mb-8 flex text-sm md:text-base"></div>
		</div>
	</div> -->
	<Block padding="py-8" class="md:text-justify">
		<Intro />
	</Block>
	<Block>
		<h1 class="mb-6 text-2xl font-bold" id="schedule">Tentative Schedule</h1>
		<div>
			<table class="w-full border-collapse border border-gray-300 text-sm">
				<thead>
					<tr class="bg-gray-100">
						<th class="border border-gray-300 px-4 py-2 text-left whitespace-nowrap">Time</th>
						<th class="w-full border border-gray-300 px-4 py-2 text-left">Event</th>
					</tr>
				</thead>
				<tbody>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">9:00--9:10</td>
						<td class="w-full border border-gray-300 px-4 py-2"><strong>Opening remarks</strong></td
						>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">9:10--9:40</td>
						<td class="w-full border border-gray-300 px-4 py-2"><strong>Invited talk 1</strong></td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">9:40--10:10</td>
						<td class="w-full border border-gray-300 px-4 py-2"><strong>Invited talk 2</strong></td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">10:10--10:45</td>
						<td class="w-full border border-gray-300 px-4 py-2"><strong>Oral talks</strong></td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">10:45--11:00</td>
						<td class="w-full border border-gray-300 px-4 py-2"><strong>Coffee break</strong></td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">11:00--11:30</td>
						<td class="w-full border border-gray-300 px-4 py-2"><strong>Invited talk 3</strong></td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">11:30--12:00</td>
						<td class="w-full border border-gray-300 px-4 py-2"><strong>Invited talk 4</strong></td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">12:00--13:00</td>
						<td class="w-full border border-gray-300 px-4 py-2"><strong>Lunch</strong></td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">13:00--14:00</td>
						<td class="w-full border border-gray-300 px-4 py-2"
							><strong>Poster session 1</strong></td
						>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">14:00--14:30</td>
						<td class="w-full border border-gray-300 px-4 py-2"><strong>Invited talk 5</strong></td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">14:30--15:00</td>
						<td class="w-full border border-gray-300 px-4 py-2"><strong>Invited talk 6</strong></td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">15:00--16:00</td>
						<td class="w-full border border-gray-300 px-4 py-2"
							><strong>Poster session 2</strong></td
						>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">16:00--16:15</td>
						<td class="w-full border border-gray-300 px-4 py-2"><strong>Coffee break</strong></td>
					</tr>
					<tr class="odd:bg-white even:bg-gray-50">
						<td class="border border-gray-300 px-4 py-2 whitespace-nowrap">16:15--17:00</td>
						<td class="w-full border border-gray-300 px-4 py-2"
							><strong>Panel discussion</strong></td
						>
					</tr>
				</tbody>
			</table>
		</div>
		<div class="mt-4 text-sm text-gray-600 italic">
			<p>All times are in Pacific Time (PT).</p>
		</div>
	</Block>
	<Block padding="pb-4">
		<h1 class="mb-4 text-2xl font-bold" id="speakers">Speakers</h1>
	</Block>
	<Block>
		<div class="flex flex-col items-center justify-center">
			<div class="flex flex-wrap justify-center">
				<Person
					name="Sheila McIlraith"
					affiliation="University of Toronto"
					link="https://www.cs.toronto.edu/~sheila/"
					image="https://www.cs.toronto.edu/~sheila/img/McIlraith2-lowres.jpg"
				></Person>
				<Person
					name="David Silver"
					affiliation="Google DeepMind / University College London"
					link="https://www.davidsilver.uk/"
					image="https://www.davidsilver.uk/wp-content/uploads/2020/03/Dave_Silver_Headshot.jpg"
				></Person>
				<Person
					name="Swarat Chaudhuri"
					affiliation="UT Austin / Google DeepMind"
					link="https://www.cs.utexas.edu/~swarat/"
					image="https://www.cs.utexas.edu/~swarat/images/swarat-ut-headshot.jpeg"
				></Person>
				<Person
					name="Armando Solar-Lezama"
					affiliation="MIT"
					link="https://people.csail.mit.edu/asolar/"
					image="https://people.csail.mit.edu/asolar/images/asolar_head.jpg"
				></Person>
			</div>
		</div></Block
	>
	<Block padding="pb-4">
		<h1 class="mb-4 text-2xl font-bold" id="organizers">Organizers</h1>
	</Block>
	<Block size="max-w-4xl">
		<div class="flex flex-col items-center justify-center">
			<div class="flex flex-wrap justify-center">
				<Person
					name="Shao-Hua Sun"
					affiliation="National Taiwan University"
					link="https://shaohua0116.github.io/"
					image="./imgs/sun.png"
				></Person>
				<Person
					name="Levi Lelis"
					affiliation="University of Alberta"
					link="https://webdocs.cs.ualberta.ca/~santanad/"
					image="https://webdocs.cs.ualberta.ca/~santanad/img/levi_amii.jpg"
				></Person>
				<Person
					name="Xinyun Chen"
					affiliation="Google DeepMind"
					link="https://jungyhuk.github.io/"
					image="https://jungyhuk.github.io/imgs/Xinyun.jpg"
				></Person>
				<Person
					name="Shreyas Kapur"
					affiliation="UC Berkeley"
					link="https://shreyaskapur.com/"
					image="./imgs/shreyas.jpg"
				></Person>
				<Person
					name="Jiayuan Mao"
					affiliation="MIT"
					link="https://jiayuanm.com/"
					image="https://jiayuanm.com/static/img/avatar24.jpg"
				></Person>
				<Person
					name="Ching-An Cheng"
					affiliation="Microsoft Research"
					link="https://www.chinganc.com/"
					image="https://www.chinganc.com/static/images/ching-an-cheng.jpg"
				></Person>
				<Person
					name="Anqi Li"
					affiliation="NVIDIA"
					link="https://anqili.github.io/"
					image="https://anqili.github.io/theme/images/anqi_li.jpg"
				></Person>
				<Person
					name="Kuang-Huei Lee"
					affiliation="Google DeepMind"
					link="https://kuanghuei.github.io/"
					image="./imgs/kuang.png"
				></Person>
				<Person
					name="Leslie Kaelbling"
					affiliation="MIT"
					link="https://people.csail.mit.edu/lpk/"
					image="https://siebelschool.illinois.edu/_sitemanager/viewphoto.aspx?id=10406&s=300"
				></Person>
			</div>
		</div>
	</Block>
	<Block>
		<h1 class="mb-4 text-2xl font-bold" id="call">Call For Papers</h1>
		<div class="text-base">
			<Call />
		</div>
	</Block>

	<div class="mt-8 flex w-full justify-center bg-gray-100 pt-4 font-sans">
		<div class="mx-8 w-full max-w-3xl">
			<div class="flex w-full flex-col items-center justify-start">
				<div class="mt-4 mb-8 text-2xl text-gray-500">
					<a
						href="https://github.com/pr4al-workshop/pr4al-workshop.github.io"
						target="_blank"
						rel="noreferrer"
						class="mr-2"
					>
						<GithubIcon class="inline-block hover:text-black" />
					</a>
				</div>
			</div>
			<div class="mb-24 text-sm text-gray-600">
				This website is licensed under a <a
					class="underline"
					href="http://creativecommons.org/licenses/by-sa/4.0/"
					target="_blank"
					rel="noreferrer">Creative Commons Attribution-ShareAlike 4.0 International License</a
				>
				and is based on the
				<a class="underline" href="https://leela-interp.github.io/" target="_blank" rel="noreferrer"
					>Leela Interp</a
				> project. That means you're free to borrow the source code of this website with attribution.
			</div>
		</div>
	</div>
</div>

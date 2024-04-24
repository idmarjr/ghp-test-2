<script>
	import barao_de_maua from '$lib/img/users/barao_de_maua.svg';
	import faculdade_unica from '$lib/img/users/faculdade_unica.svg';
	import feevale from '$lib/img/users/feevale.svg';
	import iesb from '$lib/img/users/iesb.svg';
	import ifac from '$lib/img/users/ifac.svg';
	import ifba from '$lib/img/users/ifba.svg';
	import iff from '$lib/img/users/iff.svg';
	import ifg from '$lib/img/users/ifg.svg';
	import ifmg from '$lib/img/users/ifmg.svg';
	import ifms from '$lib/img/users/ifms.svg';
	import ifpb from '$lib/img/users/ifpb.svg';
	import ifpr from '$lib/img/users/ifpr.svg';
	import ifro from '$lib/img/users/ifro.svg';
	import ifrs from '$lib/img/users/ifrs.svg';
	import ifsc from '$lib/img/users/ifsc.svg';
	import ifsp from '$lib/img/users/ifsp.svg';
	import ufba from '$lib/img/users/ufba.svg';
	import ufc from '$lib/img/users/ufc.svg';
	import ufms from '$lib/img/users/ufms.svg';
	import ufpel from '$lib/img/users/ufpel.svg';
	import ufs from '$lib/img/users/ufs.svg';
	import ufsc from '$lib/img/users/ufsc.svg';
	import unemat from '$lib/img/users/unemat.svg';
	import uni_cruzeiro_do_sul from '$lib/img/users/uni_cruzeiro_do_sul.svg';
	import unibrasil from '$lib/img/users/unibrasil.svg';
	import unicesumar from '$lib/img/users/unicesumar.svg';
	import unisal from '$lib/img/users/unisal.svg';
	import unisinos from '$lib/img/users/unisinos.svg';
	import univille from '$lib/img/users/univille.svg';
	import uvv from '$lib/img/users/uvv.svg';

	let users = [
		{ name: "userNameHere", src: ufba },
		{ name: "userNameHere", src: ufc },
		{ name: "userNameHere", src: ufms },
		{ name: "userNameHere", src: ufpel },
		{ name: "userNameHere", src: ufsc },
		{ name: "userNameHere", src: ufs },
		{ name: "userNameHere", src: barao_de_maua },
		{ name: "userNameHere", src: faculdade_unica },
		{ name: "userNameHere", src: feevale },
		{ name: "userNameHere", src: iesb },
		{ name: "userNameHere", src: unemat },
		{ name: "userNameHere", src: uni_cruzeiro_do_sul },
		{ name: "userNameHere", src: unibrasil },
		{ name: "userNameHere", src: unicesumar },
		{ name: "userNameHere", src: unisal },
		{ name: "userNameHere", src: unisinos },
		{ name: "userNameHere", src: univille },
		{ name: "userNameHere", src: uvv },
		{ name: "userNameHere", src: ifac },
		{ name: "userNameHere", src: ifba },
		{ name: "userNameHere", src: iff },
		{ name: "userNameHere", src: ifg },
		{ name: "userNameHere", src: ifmg },
		{ name: "userNameHere", src: ifms },
		{ name: "userNameHere", src: ifpb },
		{ name: "userNameHere", src: ifpr },
		{ name: "userNameHere", src: ifro },
		{ name: "userNameHere", src: ifrs },
		{ name: "userNameHere", src: ifsc },
		{ name: "userNameHere", src: ifsp },
	];
</script>

<section id="WhoUse">
	<div class="bg-white border-b-2">
		<div class="mx-auto max-w-7xl px-6 py-24">
			<h2 class="mb-24 text-3xl font-bold text-center tracking-tight text-gray-900 sm:text-4xl">Who use it</h2>
			<div class="
				grid
				grid-cols-6
				mx-auto
				max-w-6xl
				items-center
				gap-x-8
				gap-y-12
				lg:grid-cols-5"
			>
				{#each users as user}
					<img
						class="col-span-2 w-full object-contain lg:col-span-1"
						src={user.src}
						alt={user.name}
						title={user.name}
					/>
				{/each}
		</div>
	</div>
</section>
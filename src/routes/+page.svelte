<script>
	import Person1 from '$lib/assets/Person1.jpg';
	import Person2 from '$lib/assets/Person2.webp';
	import Person3 from '$lib/assets/Person3.webp';
	import Person4 from '$lib/assets/Person4.jpg';
</script>

<div class="mx-auto max-w-4xl">
	<div class="mb-6 flex items-center justify-between">
		<div class="flex flex-col">
			<h1 class="text-2xl font-semibold">User Accounts</h1>
			<p class="text-sm text-gray-500">View accounts of registered users</p>
		</div>

		<button
			class="flex items-center gap-2 rounded-xl bg-blue-600 px-5 py-2 text-sm text-white hover:bg-blue-700">
			CSV
		</button>
	</div>

	<div class="flex justify-center">
		<div class="w-full max-w-4xl overflow-hidden rounded-2xl bg-white shadow">
			<table class="w-full text-left">
				<tbody>
					<tr class="bg-blue-600 text-sm text-white">
						<td class="px-6 py-3 font-bold">ID</td>
						<td class="px-6 py-3 font-bold">FULL NAME</td>
						<td class="px-6 py-3 font-bold">USER ROLE</td>
						<td class="px-6 py-3 font-bold">CREATED AT</td>
						<td class="px-6 py-3 font-bold">STATUS</td>
					</tr>

					<tr class="border-t border-gray-200">
						<td class="px-6 py-4">3</td>
						<td class="flex items-center gap-3 px-6 py-4">
							<img src={Person4} alt="" class="h-10 w-10 rounded-full" />
							Markus Smith
						</td>
						<td class="px-6 py-4 text-gray-600">Administrator</td>
						<td class="px-6 py-4 text-gray-600">Sep 28, 2022</td>
						<td class="px-6 py-4">
							<span class="rounded-full bg-green-100 px-3 py-1 text-xs text-green-700">Active</span>
						</td>
					</tr>

					<tr class="border-t border-gray-200">
						<td class="px-6 py-4">7</td>
						<td class="flex items-center gap-3 px-6 py-4">
							<img src={Person1} alt="" class="h-10 w-10 rounded-full" />
							James Carter
						</td>
						<td class="px-6 py-4 text-gray-600">Author</td>
						<td class="px-6 py-4 text-gray-600">Sep 28, 2022</td>
						<td class="px-6 py-4">
							<span class="rounded-full bg-green-100 px-3 py-1 text-xs text-green-700">Active</span>
						</td>
					</tr>

					<tr class="border-t border-gray-200">
						<td class="px-6 py-4">12</td>
						<td class="flex items-center gap-3 px-6 py-4">
							<img src={Person2} alt="" class="h-10 w-10 rounded-full" />
							Elvis Son
						</td>
						<td class="px-6 py-4 text-gray-600">Editor</td>
						<td class="px-6 py-4 text-gray-600">Sep 28, 2022</td>
						<td class="px-6 py-4">
							<span class="rounded-full bg-yellow-100 px-3 py-1 text-xs text-yellow-700"
								>Suspended</span
							>
						</td>
					</tr>

					<tr class="border-t border-gray-200">
						<td class="px-6 py-4">66</td>
						<td class="flex items-center gap-3 px-6 py-4">
							<img src={Person3} alt="" class="h-10 w-10 rounded-full" />
							Dana White
						</td>
						<td class="px-6 py-4 text-gray-600">Administrator</td>
						<td class="px-6 py-4 text-gray-600">Sep 28, 2022</td>
						<td class="px-6 py-4">
							<span class="rounded-full bg-red-100 px-3 py-1 text-xs text-red-600">Inactive</span>
						</td>
					</tr>
				</tbody>
			</table>
		</div>
	</div>
</div>

<script lang="ts">
  import XLogo from '../lib/assets/XLogo.svg';
  import DiscordLogo from '../lib/assets/DiscordLogo.svg';
  import IconBtn from './IconBtn.svelte';
</script>

<div class="w-full max-w-[425px] pb-[80px] sm:pt-[80px] lg:pl-[140px] lg:pt-6">
  <h3 class="text-base font-semibold">Join the Digital Revolution</h3>
  <p class="text-sm">Become a part of shaping the future of the digital landscape with Frequency.</p>
  <div class="mt-4 flex gap-4" aria-label="Social Links">
    <IconBtn label="X/Twitter" imgSrc={XLogo} href={'https://twitter.com/one_frequency'} />
    <IconBtn label="Discord" imgSrc={DiscordLogo} href="https://discord.com/invite/JchmHX5afV" />
  </div>
</div>

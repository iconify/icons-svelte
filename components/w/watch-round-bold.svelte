<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-3qw545f.css';
import '../../css/b/bf9x-hh2k.css';
import '../../css/c/crrii6bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-3qw545f"/><path class="bf9x-hh2k"/><path class="crrii6bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:watch-round-bold" {...props}></Icon>

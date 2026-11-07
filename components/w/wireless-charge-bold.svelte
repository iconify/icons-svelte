<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmr5y1isy.css';
import '../../css/i/i_u1m3bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fmr5y1isy"/><path class="i_u1m3bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wireless-charge-bold" {...props}></Icon>

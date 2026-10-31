<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzb_m2b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzb_m2b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tv-fill-round" {...props}></Icon>

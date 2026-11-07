<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1ax0lebc.css';
import '../../css/n/nyn0a-12z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1ax0lebc"/><path class="nyn0a-12z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-off-bold" {...props}></Icon>

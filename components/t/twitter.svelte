<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niq-ey43z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="niq-ey43z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:twitter" {...props}></Icon>

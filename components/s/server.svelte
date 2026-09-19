<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s20g6541r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s20g6541r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:server" {...props}></Icon>

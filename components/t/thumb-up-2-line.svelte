<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i82l_mncq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i82l_mncq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:thumb-up-2-line" {...props}></Icon>

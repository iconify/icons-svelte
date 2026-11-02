<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrt6ifbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrt6ifbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-3-fill" {...props}></Icon>

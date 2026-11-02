<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfry4lb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfry4lb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:square-arrow-right-fill" {...props}></Icon>

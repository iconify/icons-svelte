<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lim_l8bmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lim_l8bmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:textalign-justifyleft" {...props}></Icon>

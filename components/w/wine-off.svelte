<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm-l3gteu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm-l3gteu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wine-off" {...props}></Icon>

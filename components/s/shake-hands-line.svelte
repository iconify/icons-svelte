<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omt6qbbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omt6qbbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shake-hands-line" {...props}></Icon>

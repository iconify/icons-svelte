<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe2119bqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pe2119bqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:server-check" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhj959bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhj959bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:smart-home-check" {...props}></Icon>

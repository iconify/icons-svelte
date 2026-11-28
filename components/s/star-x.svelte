<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4z1vmbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4z1vmbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:star-x" {...props}></Icon>

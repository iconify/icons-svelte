<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll70l5bpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll70l5bpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:slider-horizontal" {...props}></Icon>

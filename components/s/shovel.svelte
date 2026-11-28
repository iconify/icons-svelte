<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1n6pzbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1n6pzbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:shovel" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvtqlkbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvtqlkbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:ruler-combined-outline" {...props}></Icon>

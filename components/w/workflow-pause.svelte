<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryb1uac7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryb1uac7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:workflow-pause" {...props}></Icon>

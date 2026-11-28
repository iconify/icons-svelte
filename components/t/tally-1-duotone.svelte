<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz948sdil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz948sdil primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tally-1-duotone" {...props}></Icon>

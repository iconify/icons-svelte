<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f19j1cczl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f19j1cczl primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:spade-duotone" {...props}></Icon>

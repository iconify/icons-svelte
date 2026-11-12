<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txhr-1syo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="txhr-1syo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:sublimetext" {...props}></Icon>

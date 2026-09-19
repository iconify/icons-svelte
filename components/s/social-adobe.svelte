<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3com816r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="d3com816r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-adobe" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0_u48bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1536};
const content = `<path class="u0_u48bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:step-backward" {...props}></Icon>

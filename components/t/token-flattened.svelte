<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoko6whnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xoko6whnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-flattened" {...props}></Icon>

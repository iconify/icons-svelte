<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj5aerbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pj5aerbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:rows-16" {...props}></Icon>

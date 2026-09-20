<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs0j5rbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cs0j5rbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:spiral-shape-remix" {...props}></Icon>

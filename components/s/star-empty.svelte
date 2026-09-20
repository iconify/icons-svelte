<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3q92ubcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u3q92ubcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:star-empty" {...props}></Icon>

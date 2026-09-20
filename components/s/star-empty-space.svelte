<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4k2mib2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t4k2mib2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:star-empty-space" {...props}></Icon>

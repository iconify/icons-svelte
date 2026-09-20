<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9f-ncbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s9f-ncbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-date" {...props}></Icon>

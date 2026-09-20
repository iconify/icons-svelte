<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jczgum2rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jczgum2rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-array" {...props}></Icon>

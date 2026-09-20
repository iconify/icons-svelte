<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjz8ocn6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hjz8ocn6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-histogram" {...props}></Icon>

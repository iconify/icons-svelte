<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khsclibwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="khsclibwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:star-plus-empty" {...props}></Icon>

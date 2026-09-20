<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2--wegar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q2--wegar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-exception" {...props}></Icon>

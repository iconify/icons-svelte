<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3uwggbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x3uwggbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-rank-features" {...props}></Icon>

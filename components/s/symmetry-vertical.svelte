<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5iyaibai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c5iyaibai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:symmetry-vertical" {...props}></Icon>

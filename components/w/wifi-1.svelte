<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7b6kccap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l7b6kccap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:wifi-1" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-by3r7ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c-by3r7ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:text-center" {...props}></Icon>

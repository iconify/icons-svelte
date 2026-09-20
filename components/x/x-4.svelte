<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd4icx4ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cd4icx4ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:x-4" {...props}></Icon>

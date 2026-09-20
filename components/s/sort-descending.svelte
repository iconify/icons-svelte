<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m08s8b8qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="m08s8b8qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:sort-descending" {...props}></Icon>

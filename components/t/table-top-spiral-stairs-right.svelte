<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1p8qwb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="a1p8qwb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-spiral-stairs-right" {...props}></Icon>

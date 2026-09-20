<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb521_b-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="zb521_b-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-spiral-stairs-round-up" {...props}></Icon>

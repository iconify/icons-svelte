<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueos75g2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ueos75g2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-horizontal-rotate-clockwise" {...props}></Icon>

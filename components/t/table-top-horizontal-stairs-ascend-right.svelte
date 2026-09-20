<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfftsmbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="bfftsmbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-horizontal-stairs-ascend-right" {...props}></Icon>

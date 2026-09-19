<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy1u78bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jy1u78bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:waterfalls-h" {...props}></Icon>

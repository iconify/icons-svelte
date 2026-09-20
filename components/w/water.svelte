<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-w4dlcpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="j-w4dlcpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:water" {...props}></Icon>

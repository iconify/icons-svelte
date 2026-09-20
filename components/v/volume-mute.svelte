<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryz1rabnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ryz1rabnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:volume-mute" {...props}></Icon>

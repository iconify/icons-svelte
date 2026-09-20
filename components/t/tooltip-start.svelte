<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pme8--b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="pme8--b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tooltip-start" {...props}></Icon>

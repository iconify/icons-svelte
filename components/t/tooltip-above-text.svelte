<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx8vpfx_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="cx8vpfx_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tooltip-above-text" {...props}></Icon>

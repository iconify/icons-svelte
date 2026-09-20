<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9zfdl87i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="i9zfdl87i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tooltip-above-help" {...props}></Icon>

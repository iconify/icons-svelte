<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmf80-bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="dmf80-bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:tooltip-above-alert" {...props}></Icon>

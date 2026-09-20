<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5tyarwmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="a5tyarwmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:weight" {...props}></Icon>

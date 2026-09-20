<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc75c6viz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="uc75c6viz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:water-fill" {...props}></Icon>

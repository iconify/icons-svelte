<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soiqe4ggu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="soiqe4ggu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:slider-right" {...props}></Icon>

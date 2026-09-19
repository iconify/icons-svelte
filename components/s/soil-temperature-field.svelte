<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9m3lvswz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u9m3lvswz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:soil-temperature-field" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwzq6cb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dwzq6cb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:show-data-cards" {...props}></Icon>

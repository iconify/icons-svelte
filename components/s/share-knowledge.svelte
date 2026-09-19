<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypdwcgblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ypdwcgblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:share-knowledge" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao8jygbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ao8jygbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:skip-forward" {...props}></Icon>

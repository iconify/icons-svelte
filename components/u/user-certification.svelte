<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byc7-gb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="byc7-gb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-certification" {...props}></Icon>

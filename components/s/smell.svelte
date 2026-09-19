<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvkkn3b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zvkkn3b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:smell" {...props}></Icon>

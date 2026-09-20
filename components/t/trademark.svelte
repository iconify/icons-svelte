<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1y2nlbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c1y2nlbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:trademark" {...props}></Icon>

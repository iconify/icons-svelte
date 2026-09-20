<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg62jd46k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mg62jd46k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vomiting-face" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piz04983m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="piz04983m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:twitter" {...props}></Icon>

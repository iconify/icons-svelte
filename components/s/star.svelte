<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duug3hbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="duug3hbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:star" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz8scbmzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gz8scbmzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:zoom-in" {...props}></Icon>

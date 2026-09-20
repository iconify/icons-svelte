<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvvtuibkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wvvtuibkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:star" {...props}></Icon>

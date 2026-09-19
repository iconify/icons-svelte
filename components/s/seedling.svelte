<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw_lpwbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iw_lpwbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:seedling" {...props}></Icon>

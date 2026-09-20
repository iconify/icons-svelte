<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwkp1t3mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hwkp1t3mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:shuttle-van-solid" {...props}></Icon>

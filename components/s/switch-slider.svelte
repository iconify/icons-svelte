<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztm9i2xkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ztm9i2xkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:switch-slider" {...props}></Icon>

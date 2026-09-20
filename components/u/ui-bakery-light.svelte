<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkh80fwxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hkh80fwxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ui-bakery-light" {...props}></Icon>

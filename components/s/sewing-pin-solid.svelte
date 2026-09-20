<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfylbybhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yfylbybhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:sewing-pin-solid" {...props}></Icon>

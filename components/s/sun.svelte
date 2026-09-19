<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v09i1dt_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v09i1dt_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:sun" {...props}></Icon>

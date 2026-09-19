<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf0npmbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="sf0npmbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:sort-amount-desc" {...props}></Icon>

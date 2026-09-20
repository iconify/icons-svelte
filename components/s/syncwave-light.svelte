<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onhg1w-oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="onhg1w-oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:syncwave-light" {...props}></Icon>

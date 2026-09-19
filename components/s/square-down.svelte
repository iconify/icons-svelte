<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk-6h0bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":400};
const content = `<path class="gk-6h0bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:square-down" {...props}></Icon>

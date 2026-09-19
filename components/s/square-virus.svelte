<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4_mopsql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="k4_mopsql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-virus" {...props}></Icon>

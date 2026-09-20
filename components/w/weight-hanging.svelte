<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq2_2eb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dq2_2eb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:weight-hanging" {...props}></Icon>

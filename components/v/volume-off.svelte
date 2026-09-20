<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-m3seolj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="x-m3seolj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:volume-off" {...props}></Icon>

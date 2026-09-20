<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynpe42bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ynpe42bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:street-road" {...props}></Icon>

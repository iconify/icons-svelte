<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuf1hebgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yuf1hebgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:steps-14" {...props}></Icon>

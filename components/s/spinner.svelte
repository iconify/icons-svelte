<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_-n7mbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h_-n7mbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:spinner" {...props}></Icon>

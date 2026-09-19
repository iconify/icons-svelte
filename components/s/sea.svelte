<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h707ewmae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="h707ewmae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sea" {...props}></Icon>

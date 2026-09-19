<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfwg66b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vfwg66b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:xmen" {...props}></Icon>

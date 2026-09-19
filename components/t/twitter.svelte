<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk80sglnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":830,"height":810};
const content = `<path class="mk80sglnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:twitter" {...props}></Icon>

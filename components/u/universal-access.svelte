<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i72_afoiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="i72_afoiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:universal-access" {...props}></Icon>

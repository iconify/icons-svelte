<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0-u5qtei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="m0-u5qtei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:tag" {...props}></Icon>

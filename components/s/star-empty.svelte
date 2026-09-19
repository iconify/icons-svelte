<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv4q92b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="pv4q92b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:star-empty" {...props}></Icon>

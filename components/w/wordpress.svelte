<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic942e1qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ic942e1qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:wordpress" {...props}></Icon>

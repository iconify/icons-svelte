<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnjlkttce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xnjlkttce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:settong" {...props}></Icon>

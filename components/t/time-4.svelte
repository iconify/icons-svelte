<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_weoss7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_weoss7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:time-4" {...props}></Icon>

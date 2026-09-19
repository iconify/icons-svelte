<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdjmgxbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":384};
const content = `<path class="sdjmgxbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:volume-mute" {...props}></Icon>

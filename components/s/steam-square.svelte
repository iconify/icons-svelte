<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrwisccxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":440,"height":448};
const content = `<path class="qrwisccxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:steam-square" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aje1gjofx.css';
import '../../css/x/xur4k61po.css';
import '../../css/w/wtc6rtblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aje1gjofx"/><path class="xur4k61po"/><path class="wtc6rtblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:server" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it1t7rbgl.css';
import '../../css/q/q4xrfybks.css';
import '../../css/w/wj41wcbwv.css';
import '../../css/b/btuq2abvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="it1t7rbgl"/><path class="q4xrfybks"/><path class="wj41wcbwv"/><path class="btuq2abvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:weather-vane-48-bold" {...props}></Icon>

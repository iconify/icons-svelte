<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmyz5cbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="mmyz5cbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:trafficlight" {...props}></Icon>

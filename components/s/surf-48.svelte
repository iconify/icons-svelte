<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgpvo8_dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qgpvo8_dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:surf-48" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf73wyzyl.css';
import '../../css/m/m3ucd-ekr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yf73wyzyl"/><path class="m3ucd-ekr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:towels-48" {...props}></Icon>

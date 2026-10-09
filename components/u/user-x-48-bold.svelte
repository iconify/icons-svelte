<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm2jupbhh.css';
import '../../css/a/acmio-sok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xm2jupbhh"/><path class="acmio-sok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-x-48-bold" {...props}></Icon>

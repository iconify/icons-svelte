<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np--nab8s.css';
import '../../css/b/b31s_0bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="np--nab8s"/><path class="b31s_0bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:send-horizontal-48-bold" {...props}></Icon>

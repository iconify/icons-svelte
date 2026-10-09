<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqe3gulqh.css';
import '../../css/q/qo5uhcrjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fqe3gulqh"/><path class="qo5uhcrjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:supply-chain-48" {...props}></Icon>

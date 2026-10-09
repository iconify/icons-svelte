<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8z5zjbsy.css';
import '../../css/q/qfevtc50w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k8z5zjbsy"/><path class="qfevtc50w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:toggle-left-48" {...props}></Icon>

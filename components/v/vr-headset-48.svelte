<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj4_8bb8s.css';
import '../../css/a/a5tfz-sap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uj4_8bb8s"/><path class="a5tfz-sap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:vr-headset-48" {...props}></Icon>

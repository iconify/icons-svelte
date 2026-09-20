<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzo_s6m5m.css';
import '../../css/m/mfabyo3pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="hzo_s6m5m"/><path class="mfabyo3pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:train" {...props}></Icon>

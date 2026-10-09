<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlsrljbwz.css';
import '../../css/q/qnv2-7buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rlsrljbwz"/><path class="qnv2-7buh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shield-alert-48" {...props}></Icon>

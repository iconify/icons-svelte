<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx_rtncis.css';
import '../../css/e/e0nmxkmog.css';
import '../../css/y/ygtv74bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mx_rtncis"/><path class="e0nmxkmog"/><path class="ygtv74bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:server-alert-48-bold" {...props}></Icon>

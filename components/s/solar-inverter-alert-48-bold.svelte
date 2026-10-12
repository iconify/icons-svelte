<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz238rb6s.css';
import '../../css/y/yvwzr-bcl.css';
import '../../css/y/ygtv74bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tz238rb6s"/><path class="yvwzr-bcl"/><path class="ygtv74bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-inverter-alert-48-bold" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9514n9ut.css';
import '../../css/x/xdk69eb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h9514n9ut"/><path class="xdk69eb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:variable-resistor-48-bold" {...props}></Icon>

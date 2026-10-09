<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bosmi-hbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bosmi-hbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wifi-low-48" {...props}></Icon>

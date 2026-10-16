<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guu8cvajv.css';
import '../../css/d/dfl7556qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="guu8cvajv"/><path class="dfl7556qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:siren-48-bold" {...props}></Icon>

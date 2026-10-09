<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp-8xbcar.css';
import '../../css/g/gkoq5rb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mp-8xbcar"/><path class="gkoq5rb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-inverter-48" {...props}></Icon>

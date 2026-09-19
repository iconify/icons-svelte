<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt50z_byh.css';
import '../../css/v/v1lzvlbpn.css';
import '../../css/h/h65up44bo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gt50z_byh"/><path class="v1lzvlbpn"/><path class="h65up44bo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:rstudio" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2qslhbnv.css';
import '../../css/h/h8poafcho.css';
import '../../css/d/dh2skybyq.css';
import '../../css/u/ub3e2sbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2qslhbnv"/><path class="h8poafcho"/><path class="dh2skybyq"/><path class="ub3e2sbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:usb" {...props}></Icon>

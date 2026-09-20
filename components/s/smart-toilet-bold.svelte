<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy7fz0b3h.css';
import '../../css/s/snw44201m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy7fz0b3h"/><path class="snw44201m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:smart-toilet-bold" {...props}></Icon>

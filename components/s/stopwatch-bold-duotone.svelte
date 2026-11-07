<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szjj1eb9x.css';
import '../../css/y/y7btgy5eh.css';
import '../../css/i/isfz-28nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szjj1eb9x"/><path class="y7btgy5eh"/><path class="isfz-28nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stopwatch-bold-duotone" {...props}></Icon>

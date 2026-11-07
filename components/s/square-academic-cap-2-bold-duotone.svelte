<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glh9vkb1x.css';
import '../../css/k/kp08yd09g.css';
import '../../css/w/wz2bj5btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glh9vkb1x"/><path class="kp08yd09g"/><path class="wz2bj5btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-academic-cap-2-bold-duotone" {...props}></Icon>

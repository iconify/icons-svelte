<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/e/ewpaxfbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="ewpaxfbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:usb-square-bold-duotone" {...props}></Icon>

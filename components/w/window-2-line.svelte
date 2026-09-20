<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd-uecbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd-uecbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:window-2-line" {...props}></Icon>

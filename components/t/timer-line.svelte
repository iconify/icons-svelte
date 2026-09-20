<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz2ter_xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz2ter_xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:timer-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4i3t7bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4i3t7bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:smartphone-apps-line" {...props}></Icon>

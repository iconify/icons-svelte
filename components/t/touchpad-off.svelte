<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6_s2nbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6_s2nbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:touchpad-off" {...props}></Icon>

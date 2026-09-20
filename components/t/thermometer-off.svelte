<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmeoeo7up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmeoeo7up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:thermometer-off" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt69m96hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt69m96hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wifi-alert" {...props}></Icon>

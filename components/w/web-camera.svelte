<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx7pczt_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx7pczt_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:web-camera" {...props}></Icon>

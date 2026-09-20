<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otb_05e1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otb_05e1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tilde-off" {...props}></Icon>

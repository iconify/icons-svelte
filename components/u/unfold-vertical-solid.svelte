<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4l0_wrne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4l0_wrne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:unfold-vertical-solid" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywepqte8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywepqte8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:video-off" {...props}></Icon>

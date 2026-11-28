<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkluktbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkluktbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:video-star" {...props}></Icon>

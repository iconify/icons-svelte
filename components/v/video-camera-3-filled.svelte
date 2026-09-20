<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-qns-azb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-qns-azb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:video-camera-3-filled" {...props}></Icon>

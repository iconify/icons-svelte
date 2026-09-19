<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am58adb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path clip-rule="evenodd" class="am58adb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:vroundswitch-on" {...props}></Icon>

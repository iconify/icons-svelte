<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymd4orbxh.css';
import '../../css/m/m7rus1bei.css';
import '../../css/v/vaiokxbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse transform="rotate(-45 256.001 304)" class="ymd4orbxh"/><path class="m7rus1bei"/><path class="vaiokxbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:train" {...props}></Icon>

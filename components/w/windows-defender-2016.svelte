<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttfp4kbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ttfp4kbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:windows-defender-2016" {...props}></Icon>

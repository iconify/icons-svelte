<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6wzr80le.css';
import '../../css/y/yt-9su_gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="f6wzr80le"/><path class="yt-9su_gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:shape-file" {...props}></Icon>

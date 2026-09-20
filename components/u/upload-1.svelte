<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s58i6g_jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s58i6g_jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:upload-1" {...props}></Icon>

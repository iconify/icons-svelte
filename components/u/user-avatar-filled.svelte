<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkwx1nbmk.css';
import '../../css/a/aq4pnbcei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wkwx1nbmk"/><path class="aq4pnbcei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-avatar-filled" {...props}></Icon>

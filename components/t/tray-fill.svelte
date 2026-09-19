<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycf3u1r9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ycf3u1r9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tray-fill" {...props}></Icon>

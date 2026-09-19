<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewppc3bhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ewppc3bhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tray-2" {...props}></Icon>

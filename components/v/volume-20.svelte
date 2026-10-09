<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcyh21bht.css';
import '../../css/i/iuy7adb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dcyh21bht"/><path class="iuy7adb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volume-20" {...props}></Icon>

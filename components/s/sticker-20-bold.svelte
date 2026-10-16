<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgevkmbzk.css';
import '../../css/b/bwnp5t_qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sgevkmbzk"/><path class="bwnp5t_qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sticker-20-bold" {...props}></Icon>

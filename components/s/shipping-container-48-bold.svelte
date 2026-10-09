<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huq5bhbzx.css';
import '../../css/j/javtcmypx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="huq5bhbzx"/><path class="javtcmypx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shipping-container-48-bold" {...props}></Icon>

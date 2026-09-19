<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jev2d4znk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jev2d4znk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:tray-arrow-down-fill" {...props}></Icon>

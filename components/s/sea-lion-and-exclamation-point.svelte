<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqoh3l0wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iqoh3l0wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sea-lion-and-exclamation-point" {...props}></Icon>

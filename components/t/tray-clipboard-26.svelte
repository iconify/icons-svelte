<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6e5nze2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="y6e5nze2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:tray-clipboard-26" {...props}></Icon>

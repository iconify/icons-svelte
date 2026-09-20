<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4oqyxb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4oqyxb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:usb-glyph" {...props}></Icon>

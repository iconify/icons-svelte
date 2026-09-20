<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxmue0b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxmue0b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wayland" {...props}></Icon>

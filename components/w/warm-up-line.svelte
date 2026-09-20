<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6wgv3bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6wgv3bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:warm-up-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkv2i5z9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkv2i5z9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sandglass-2-line" {...props}></Icon>

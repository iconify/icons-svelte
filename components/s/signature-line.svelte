<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wparaabjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wparaabjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:signature-line" {...props}></Icon>

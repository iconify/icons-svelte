<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2288-utt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2288-utt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:semicircle-dash-line" {...props}></Icon>

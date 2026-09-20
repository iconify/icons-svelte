<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us-21_hyf.css';
import '../../css/p/p-8ny1bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us-21_hyf"/><path class="p-8ny1bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:video-line" {...props}></Icon>

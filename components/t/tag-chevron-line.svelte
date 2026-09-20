<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjm2_8ziu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjm2_8ziu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tag-chevron-line" {...props}></Icon>

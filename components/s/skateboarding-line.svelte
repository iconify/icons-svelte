<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xicf-7g9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xicf-7g9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:skateboarding-line" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqm4_kbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqm4_kbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xido" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzl1hcbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzl1hcbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sector-line" {...props}></Icon>

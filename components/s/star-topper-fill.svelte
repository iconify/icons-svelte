<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq0x9-boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq0x9-boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:star-topper-fill" {...props}></Icon>

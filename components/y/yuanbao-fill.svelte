<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw85rxb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw85rxb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:yuanbao-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdrsw6b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdrsw6b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-horizontal-fill" {...props}></Icon>

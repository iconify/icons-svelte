<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnt5xlejy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnt5xlejy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-2-line" {...props}></Icon>

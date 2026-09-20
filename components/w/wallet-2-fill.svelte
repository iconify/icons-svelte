<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1-z5nbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1-z5nbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-2-fill" {...props}></Icon>

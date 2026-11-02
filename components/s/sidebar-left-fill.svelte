<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1-0pxo2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1-0pxo2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sidebar-left-fill" {...props}></Icon>

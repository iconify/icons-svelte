<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmb7ilbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmb7ilbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tree-3-fill" {...props}></Icon>

<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg3ymujxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bg3ymujxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:split-cells-vertical" {...props}></Icon>

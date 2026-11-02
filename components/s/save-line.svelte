<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy7qs5byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy7qs5byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:save-line" {...props}></Icon>

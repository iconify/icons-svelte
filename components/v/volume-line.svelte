<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og74i3xnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og74i3xnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:volume-line" {...props}></Icon>

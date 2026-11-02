<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux_szwjre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux_szwjre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:screwdriver-fill" {...props}></Icon>

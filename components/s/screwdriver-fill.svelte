<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me3_0igul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="me3_0igul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:screwdriver-fill" {...props}></Icon>

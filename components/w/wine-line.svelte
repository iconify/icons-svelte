<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4t0clw7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4t0clw7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wine-line" {...props}></Icon>

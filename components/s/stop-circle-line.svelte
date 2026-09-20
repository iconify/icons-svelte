<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf2faab1e.css';
import '../../css/u/unpwu6t-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf2faab1e"/><path class="unpwu6t-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stop-circle-line" {...props}></Icon>

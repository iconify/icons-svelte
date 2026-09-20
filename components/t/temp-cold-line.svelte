<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-2su8v_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-2su8v_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:temp-cold-line" {...props}></Icon>

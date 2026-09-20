<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_dc70buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_dc70buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:smile-beam" {...props}></Icon>

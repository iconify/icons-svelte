<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-_rut9uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-_rut9uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toggle-right-line" {...props}></Icon>

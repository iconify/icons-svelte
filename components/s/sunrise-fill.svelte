<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmaew0blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wmaew0blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sunrise-fill" {...props}></Icon>

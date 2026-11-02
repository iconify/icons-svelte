<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyoulr1uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyoulr1uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-4-line" {...props}></Icon>

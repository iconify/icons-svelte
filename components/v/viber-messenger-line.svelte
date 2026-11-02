<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxval3blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxval3blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:viber-messenger-line" {...props}></Icon>
